# Cloud-Computing

    1. SAAS(Sofware as Service): 클라우드가 사용자에게 소프트웨어를 제공하는 형태
    2. Paas(Platform as Service): 사용자가 가상화된 클라우드 위에 사용자가 원하는 서비스를 개발할 수 있도록
    개발 환경을 구축해주는 형태
    3. Iaas(InfraStructure as Service): 가상화, 스토레지, 네트워크, 서버 등을 사용자에게 제공하여 사용자가
    오버헤드 없이 컴퓨팅의 리소스를 사용할 수 있게 해준다.

#  클라우드 컴퓨팅 구성
![AWS 기준](https://user-images.githubusercontent.com/65396939/205218379-5cc35a62-3ea8-4735-a110-bc5696172cf9.png)
 
 
 # Deploy
    개발한 프로그램을 사용자들이 접근할 수 있는 단계로 만들어주는 과정
    
    1. Development
        1-1 Local 컴퓨터 환경에서 개발 및 테스트
        1-2 Sample Data를 이용
        1-3 변경사항이 있어도 문제가 되지 않음
    2. Integration
        2-1 각 개발자들의 작업을 통합
        2-2 코드간 Conflict가 없는지 확인하는 단계
        2-3 작성한 코드가 다른 코드에 문제를 발생시시키지 않는지 확인
    3. Staging
        3-1 Production과 단계와 가장 유사한 환경에서 테스트
        3-2 복제된 실제 데이터를 이용해서 테스트
        3-3 모든 관계자들에게 검증하는 단계
    4. Production
        4-1 개발황경과는 구분 된 환경
        4-2 실제 데이터를 이용
        4-3 실제로 서비스가 제공되는 단계


 # EC 2
    아마존 웹 서비스에서 제공하는 클라우드 컴퓨팅 시스템(->아마존 클라우트 서버 컴퓨터 1대를 대여하는 것)
    PC방 사용 요금과 같이 아마존 서버 컴퓨터를 사용한 만큼의 금액을 지불하는 방식(elastic)
    
    EC 2의 장점
    1. 다양한 운영체제, 하드웨어 지원
    
  ## AMI(Amazon Machine Image)
  EC 2를 서비스를 활용하기 위해서는 작업 환경에 Instance를 불러와야 한다. 이 과정에 있어서 AMI는 Instance의 운영체제, 하드웨어 등 가상환경을 구성해주는 역할을 한다.
  ![image](https://user-images.githubusercontent.com/65396939/205220395-cbc14854-e944-406e-8488-2b6af3d73fb0.png)
<AMI 선택환면>                                                                                


# RDS(Relational Database Service)
1. 다양한 데이터베이스 엔진 제공
![image](https://user-images.githubusercontent.com/65396939/205222089-e62efcf6-9c86-4862-9de8-  7bb1f9e6a444.png)
2. 데이터베이스 유지 보수, 관리가 용이

# S3

    
  
