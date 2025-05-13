# Git Action 테스트 - 연습 기록장

### ✅ CI/CD란?

CI/CD란 Continuous Integration, Continuous Deployment라는 의미를 가지고 있다. 쉽게 표현하자면 **CI/CD는 테스트(Test), 통합(Merge), 배포(Deploy)의 과정을 자동화하는 걸 의미**한다.

### ✅ CI/CD 흐름을 이해하기 위한 Github Actions 개념 정리

**Github Actions**를 **로직을 실행시킬 수 있는 일종의 컴퓨터**라고 생각하면 된다. CI/CD 과정에서 Github Actions는 “빌드, 테스트, 배포”에 대한 로직을 실행시키는 역할을 하게 된다. 

### ✅ CI/CD 전체 흐름

CI/CD의 구성 방식은 다양하지만 일반적으로 아래의 흐름을 가진다. 

<img width="704" alt="image" src="https://github.com/user-attachments/assets/36bf2e35-d338-476c-9bf8-65c5b01c23e1" />


1. 코드 작성 후 Commit
2. Github에 Push
3. Push를 감지해서 Github Actions에 작성한 로직이 실행
    1. 빌드(Build)
    2. 테스트(Test)
    3. 서버로 배포(Deploy)
4. 서버에서 배포된 최신 코드로 서버를 재실행
