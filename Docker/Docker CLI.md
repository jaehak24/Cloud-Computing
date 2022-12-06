# Docker CLI(Command Line Interface)


## 도커 실행 로드맵
![image](https://user-images.githubusercontent.com/65396939/205804642-598eecd1-3c02-436f-aaf2-432e0e3e41bc.png)


### 도커 버전 확인
    docker --version
실행결과:

![image](https://user-images.githubusercontent.com/65396939/205806783-69576ae0-b077-4e12-8cef-c6750da069ab.png)


### 도커 최신 이미지 받아오기

    docker image pull [레지스트리 아이디]/[이미지 이름]:[version]
    
실행 예제:

![image](https://user-images.githubusercontent.com/65396939/205807088-5940ea61-1cad-490a-8665-3b213bdadf3a.png)


### 도커 이미지 확인

    docker iamge ls
    
실행 예제: 

![image](https://user-images.githubusercontent.com/65396939/205807163-d4a0691b-94a3-463b-a512-2a0f418ef859.png)


### 도커 이미지 실행
    docker container run [OPTIONS] [IMAGE NAME] [COMMAND] [ARGS]
    
실행 예제:
![image](https://user-images.githubusercontent.com/65396939/205807382-96be9b24-549e-4691-b09a-76eb44c789dc.png)


### 컨테이너 리스트 출력
    docker container ps -a
    
실행 화면: 
![image](https://user-images.githubusercontent.com/65396939/205807455-638e5b19-98f8-421a-a8fa-ca8dfeff1c15.png)

### 컨테이너 삭제
    docker container rm [CONTAINER_NAME]
    
실행 화면:
1. 삭제 커멘드
  ![image](https://user-images.githubusercontent.com/65396939/205807592-11c0ba31-03c0-4c13-bfa8-883b1c5f3250.png)

2. 리스트 확인(jaehak24 삭제된 걸 확인 가능)
![image](https://user-images.githubusercontent.com/65396939/205807606-6d3fe1a5-6aae-4397-a7dd-aa8153412a11.png)


# 도커 이미지 만들기

## 1. 구동한 Docker Container를 이미지로 만드는 방법

### Step 1 구동한 Docker Container를 이미지로 만들기
    docker container commit [CONTAINER_NAME] [만들 IMAGE_NAME]
### Step 2 생성된 이미지를 포트에서 웹 서버로 구동해 확인
    docker run --name my_web2 -p [PORT_NO]:80 [만든 IMAGE_NAME]
    
    
## 2. Docker Image 빌드를 위한 파일인 DockerFile로 만드는 방법

DockerFile은 이미지 파일의 설명서라고 생각하면 됨





