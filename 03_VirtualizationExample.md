# 가상화기술 사례(VMWare ESXi, Oracle VirtualBox) - 설치 및 사용법

## 하이퍼바이저 사용법
### VMware ESXi
- VMWare사의 대표적인 타입1 하이퍼바이저
    - vSphere 제품군 중 하나
    - cf. Dell-EMC-VMWare-SpringSource
- 리눅스 커널기반의 하이퍼바이저(리눅스커널 + 하이퍼바이저)
    - 네이티브로 인스톨해야 함
- 별도의 관리툴(vCenter)을 가지고 있음

### 버추얼박스(VirtualBox)
- 오라클(구 썬마이크로시스템즈)에서 만듦
- GPL기반의 타입2기반 오픈소스 하이퍼바이저
- 윈도우/맥/리눅스버전 제공

### 우분투 설치(install)
- 우분투 서버 다운로드(http://www.ubuntu.com)
    - 현재 최신버전 16.04
    - .iso파일
- 하이퍼바이저에 새로운 VM(가상머신) 생성
    - CPU/메모리/디스크 설정
    - OS설정(Linux/Ubuntu Server 64bit) 선택
    - 이미지 지정
    - 가상머신 실행
    - 우분투 설치
        -아이디/비밀번호 등록
        
### 우분투 설정(set up)
- 최신 패치 설치    
    - sudo apt-get update
- SSH 서버 설치
    - sudo apt-get install openssh-server
- 윈도우용 putty
    - ssh 클라이언트
        - IP주소/포트(22) 지정
        - IP주소
            1) NAT : 주소 공유
            2) 브릿지(Bridged) : 독립주소 받기