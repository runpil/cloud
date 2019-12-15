# 클라우드의 개념 및 종류

## 클라우드(Cloud)의 개념
### SPI 모델
- 가장 일반적인 클라우드 구분법
- IaaS(Infrastructure as a Service)
    - 서버 자원(CPU/메모리/디스크/네ㅌ워크), ...
    - 아마존 AWS EC2
- PaaS(Platform as a Service)
    - OS + Runtime(Java) + Platform(Sprint, Hadoop, DBMS, ...)
    - 아마존 AWS EMR
- SaaS(Software as a Service)
    - Google Drive, MSOffice.com, ...
- 클라우드를 구축하기 위한 요소기술(Enabling Technology)에 가상화기술과 도커와 같은 컨테이너기반 기술이 있다.
---

## 가상화(Virtualization)
### 가상화(Virtualization)
- 컴퓨터 자원(CPU, 메모리, 저장장치, 네트워크 등)의 추상화
### 가상화의 레벨
- API(Aplication Programming Interface)
    - 응용프로그램 레벨의 함수/메소드, 언어독립적인 경우도 있음
- ABI(Application Binary Interface)
    - 플랫폼과 소프트웨어 사이의 인터페이스 정의
    - API보다 낮은 레벨
    - API는 유지되면서 ABI는 변경되는 경우
        - 코드는 유지하면서 재컴파일
- ISA(Instruction Set Architecture)
    - 하드웨어와 소프트웨어 사이의 인터페이스 정의    
### Scale-Up vs Scale-Out
---
## 클라우드/가상화 적용사례
### 클라우드 서비스
- 아마존 AAWS(Amazon Web Service)
    - EC2/EMR(ElasticMapReduce)/S3/RDS/...
    - Elastic Computing Cloud/Elastic MapReduce
    - Simple Storage Service, Relational Database Service
- MS 애저(Azure)
- 드랍박스, N드라이브, 다음클라우드, U클라우드, ...
- 구글드라이브
    - 클라우드 디스크+오피스+PDF viewer, ...
- OpenStack
    - IaaS스타일의 오픈소스 클라우드 구축 플랫폼
    - KVM을 기본 하이퍼바이저로 사용