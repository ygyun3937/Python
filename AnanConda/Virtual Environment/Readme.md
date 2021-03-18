###### 출처: https://teddylee777.github.io/python/anaconda-%EA%B0%80%EC%83%81%ED%99%98%EA%B2%BD%EC%84%A4%EC%A0%95-%ED%8C%81-%EA%B0%95%EC%A2%8C

#
### 가상환경이란?
##### - 가상의 개발 환경
##### - 필요한 이유
          1) python 버전 관리
          2) Package 충돌 방지

#
#### 2. 설치
##### 1) Anaconda를 활용한 가상환경 설치
#####   ■ 명령어
#####     - 설치된 패키지 목록 보기
            conda list
#####     - 단일 패키지 설치
            conda install pandas
#####     - 2개 이상 패키지 설치
#####       ex) pandas, numpy, tensorflow 설치
            conda install pandas numpy tensorflow
#####     - 단일 패키지 업데이트
            conda update pandas
#####     - 설치된 패키지 모두 업데이트
            conda update --all           
#####     - 패키지 제거
            conda remove pandas
#####     - 설치된 패키지 검색
            conda search '*pandas*'            
#####     - 가상환경 생성
            conda create -n my_python_env
#####     - 가상환경 생성하면서 패키지 설치 
            conda create -n my_python_env pandas tensorflow            
#####     - python 설치
            conda create -n my_python_env python=3.4
#####     - 가상환경 시작/종료
            activate my_python_env      //시작
            deactivate                  //종료
            
