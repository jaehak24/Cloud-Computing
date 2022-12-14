## Docker
![image](https://user-images.githubusercontent.com/65396939/205780705-c29fbd7e-f753-4271-b05e-349108325c7d.png)


# Container
## 컨테이너의 장점

### 장점 1. 의존성 충돌 문제를 해결해준다.
    1. 개발 환경과 배포 환경을 일치시킨다.
    2. 수평 확장을 쉽게 해준다.
    3. 각 서버에 새로운 내용을 배포하기 쉽게 만들어준다. 
--> 컨테이너 기술은 애플리케이션을 컨테이너 내에 구성. 즉, 실행 중인 애플리케이션은 OS나, 의존성을 공유하지 않고
    각자 고유의 의존성을 포함하고 있다.
    
###개발 환경과 배포 환경을 일치
    이전의 방식으로는 서버에 프로그램, 파일, 데이터베이스 등 모든 것들을 올렷다면 이제는 컨텐이너에 담긴 애플리케이션을 
    실행하는 방식으로 서비스를 제공

    ex> 주로 EC 2 상에 도커를 설치하거나, 도커 컨테이너를 EC2 서버에서 실행할 
    수 있게 하는 서비스인 ECS를 이용하여 배포

### 수평 확장을 쉽게 해준다.
    한 어플리케이션에 있어서도 여러 명의 사용자들이 참여하기에 이에 대한 수평적 배분(로드 밸런싱==수평 확장)이 이뤄줘야 한다.
    이를 위해서 컨테이너는 여러 서버에 컨테이너를 각자 배당해 사용자마다 애플리케이션이 사용되게끔 진행된다. 또한 여러 버전의
    애플리케이션에서도 이와 같은 방식을 채택한다면 버전 간 충돌도 방지할 수 있다.
    
## 이미지
    애플리케이션이 독립적으로 실행되게끔 해주는 일종의 VM이다.

## 컨테이너
    실행되는 모든 컨테이너는 이미지로부터 생성. 
    이미지는 애플리케이션 및 애플리케이션 구성을 함께 담아놓은 템플릿

## 레지스트리
    이미지는 레지스트리에 저장.
    도커 CLI(Command Line)에서 이미지를 이용해 컨테이너를 생성할 때, 호스트 컴퓨터에 이미지가 존재하지 않는다면
    기존 레지스트리로부터 다운로드 받게 됩니다.
