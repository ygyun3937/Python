###### 출처 : https://goddaehee.tistory.com/251
### Window10 Docker 설치

#
#### 1. 도커란?
##### - 컨테이너 기반의 오픈소스 가상화 플랫폼
##### - 컨테이너 : 다양한 OS에 여러 Application이 올려져 있는 것
##### - 프로그램(소프트웨어)을 담는 격리된 공간

#
#### 2. 장점
##### 1) 빠르고 가벼운 가상화 솔루션
#####  - Docker Engine 을 통해서 Guest OS 없이 실행 가능하므로 가상머신보다 빠른 실행속도를 보장
#####  - 하드웨어 가상화를 하지 않기 때문에 메모리 엑세스, 파일 시스템, 네트워크 실행 성능도 뛰어남

##### 2) 개발언어에 종속되지 않음
#####  - 개발언어나 툴에 상관없이 Application 생성 가능
#####  - 생선된 Application은 이동성이 뛰어나고 어디서든 실행이 가능하다.

##### 3) 뛰어난 보안성
#####  - 해킹을 당할경우 각 컨테이너들은 격리되어 있어 원래 서버에 영향을 주지 않는다.

#
#### 3. Window10환경 Docker 설치하기
##### 1) 설치 전 환경설정
##### > Docker를 사용하기 위해서 가상화 기술인 Hyper-V를 활성화 해야한다.
##### > 작업관리자를 통해 확인, 비활성화 상태인 경우 BIOS에서 활성화시켜줘야한다.
##### ![image](https://user-images.githubusercontent.com/74608323/111581547-c9146f00-87fc-11eb-8f43-12c89bbe0441.png)

##### 2) 도커 설치파일 다운로드 및 설치
##### > https://hub.docker.com/editions/community/docker-ce-desktop-windows/ -> Get Docker
##### ![image](https://user-images.githubusercontent.com/74608323/111579630-b187b700-87f9-11eb-8987-7a533aeecd27.png)
##### > 설치 파일 실행
##### ![image](https://user-images.githubusercontent.com/74608323/111581455-9b2f2a80-87fc-11eb-9910-14535ece16b6.png)

##### 3) 설치 완료 되면 재부팅

##### 4) Docker 실행
##### 5-1) 오류메시지 발생시
##### ![image](https://user-images.githubusercontent.com/74608323/111581370-7935a800-87fc-11eb-956b-5673e220798c.png)
##### > 해당 링크에서 관련 파일 설치 재실행

##### 5)회원가입
##### 6)이메일 인증
##### 7)CMD -> docker -v //설치된 도커 버전 확인
##### ![image](https://user-images.githubusercontent.com/74608323/111581825-522ba600-87fd-11eb-8b5a-9e203870e2bb.png)

#
#### 4. GUI 환경 설치(Kitematic)
##### 1) 다운로드 -> 실행 (별도의 설치 불필요)
##### 설치 링크 : https://github.com/docker/kitematic/releases

##### 2) 실행 -> 로그인 (기존에 가입한 Docker ID)
##### ![image](https://user-images.githubusercontent.com/74608323/111582434-278e1d00-87fe-11eb-9b1c-9e8d2ccb3a9c.png)

##### 3) 도커 사용 준비 완료
##### ![image](https://user-images.githubusercontent.com/74608323/111582535-4ee4ea00-87fe-11eb-924f-0dc5afe70441.png)





