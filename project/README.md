# :high_brightness: NS홈쇼핑 BDA
### 프로젝트 개요
* DW/BI 용도의 빅데이터 시스템 신규 구축
* 프로젝트 분류 : 빅데이터, DW/BI, 정보계
* 기간 : 2019년 09월 ~ 2020년 02월
* 수행역할 : TA, 설계, 개발
* 팀구성 : PL 1, DW/BI 1, UI 1
> 특징 : 원맨 DW/BI 프로젝트
### 프로젝트 환경
* 플랫폼 : Oracle BDA, Cloudera CDH
* OS : Oracle Linux
* 주요기술 : Hadoop, Hive, Impala, KUDU, Sqoop, Kafka, Spring Boot, Quartz Scheduler, Multi Thread, Embedded Tomcat
### Hadoop 클러스터 구축
* 플랫폼 : Oracle BDA, Cloudera CDH
* 주요 컴포넌트 : Hive, Impala, KUDU, HDFS, Kafka, Hue, Sentry
* Cluster Planning (CDH의 Role 설정) 및 Impala, KUDU 등 컴포넌트 세부 설정
* MIT Kerberos 및 Sentry, OS 관련 설치 및 설정. Kerberos 외부((Linux, Windows 기반)와 서비스(Impala, Hive) 연동 설정
### 스케줄링 서버
* 스케줄링 서버
* 사용기술 : Spring Boot, Kafka, Quartz Scheduler, Multi Thread, Embedded Tomcat, MyBatis
### 스케줄링 에이전트
* 스케줄링 에이전트
* 사용기술 : Spring Boot, Kafka, Multi Thread
### 인터페이스 어플리케이션 (ETL, API 등)
* 테이블, 컬럼, 스케줄링 JOB 메타 정보를 이용하여 ETL, API 인터페이스를 이용한 데이터 적재 어플리케이션 구현
* Hive Metastore 정보를 이용하여 Impala, KUDU 테이블 및 데이터 마이그레이션 어플리케이션 구현
* 신규 ETL 인터페이스에 대한 초기적재 어플리케이션 구현
* 사용기술 : Shell, Java, Python, JSON, JSON Serde, XML Serde
### Rest API Server
* API를 통한 스케줄링 서버/에이전트 컨트롤
* 사용기술 : Spring, Quartz Scheduler, Embedded Tomcat, Kafka
### DW
* 기간계/컨텍센터 테이블 500여개 ETL 인터페이스 및 DW 적재
* 사용기술 : HiveQL, Hive, Impala, HDFS, KUDU
### 고객 응대등급 데이터 마트
* 고객 응대등급 팩터에 따른 세그먼트 마트
* 사용기술 : HiveQL, Hive, Impala, HDFS, KUDU

# :high_brightness: 메가박스 마케팅/캠페인 시스템
### 프로젝트 개요
* DW/BI 용도의 시스템 신규 구축
* 기간 : 2019년 03월 ~ 2019년 09월
* 수행역할 : DA, 모델링, 설계, 개발
* 팀구성 : PL 1, DW/BI 2, ETL 1, UI 2
### 공통
* 
* 사용기술 : PL-SQL, 
### 캠페인 결과 분석
* 캠페인 결과 분석 관련 마트, AB Test
### 고객 세그먼트
* RFM 및 20여 분류의 상세화 고객 세그먼트
### 마켓쉐어 데이터 수집

# :high_brightness: SK브로드밴드 UI 5.0 로그 데이터 분석
### 프로젝트 개요
* DW/BI 용도의 시스템 신규 구축
* 기간 : 2018년 07월 ~ 2019년 01월
* 수행역할 : 모델링, 설계, 개발
* 팀구성 : PL 1, DW/BI 3, UI 2
> 레거시 마트 데이터 정합성 15%에서 70%로 향상 (원천의 로그시간 이슈 해결시 대폭 향상 될것으로 예측)
> 프로젝트 중간부터 DW/BI 원맨 프로젝트
### 로그 데이터 전처리
* 사용기술 : Hive, Tez, Oozie, Sqoop, Oracle Exadata
### 로그 데이터 분석 마트
### 로그 분석 시각화 마트
### 로그 연동 매출 마트
### 로그 연동 AI 음성 마트
### 개인화 추천블록 마트
### ETL


