# :high_brightness: NS홈쇼핑 BDA
### 프로젝트 개요
* Hadoop 기반 DW/BI 시스템 신규 구축. 인터페이스(CDC, ETL, API 등)와 DW 적재가 주안점
* 프로젝트 분류 : 빅데이터, DW/BI, 정보계
* 기간 : 2019년 09월 ~ 2020년 02월
* 수행역할 : TA, 설계, 개발
> 클러스터 구축부터 Hadoop 및 DW/BI 관련 A to Z
### 프로젝트 환경
* 플랫폼 : Oracle BDA, Cloudera CDH (8 노드)
* OS : Oracle Linux
* 데이터베이스 : Oracle Exadata/EE, Hadoop, Hive, Impala, KUDU
* 주요기술 : Hadoop, Hive, Impala, KUDU, Sqoop, Kafka, Hue, MIT Kerberos, Sentry, Spring Boot, Quartz Scheduler, Multi Thread, Embedded Tomcat
### Hadoop 클러스터 구축
* 플랫폼 : Oracle BDA, Cloudera CDH
* 주요 컴포넌트 : Hadoop, Hive, Impala, KUDU, Kafka, Hue, MIT Kerberos, Sentry
* 클러스터 Capacity Planning 및 클러스터 컴포넌트 세부 설정 
* MIT Kerberos 구축 및 정책 권한 설정. Linux, Windows 기반 (Tableau, WAS 등) Kerberos 연동 설정
### 스케줄링 서버
* Quartz 스케줄러 및 Kafka 메시지 처리
* 사용기술 : Spring Boot, Kafka, Quartz Scheduler, Multi Thread, MyBatis
### 스케줄링 에이전트
* Kafka 메세지 처리 및 JOB 처리
* 사용기술 : Spring Boot, Kafka, Multi Thread
### 인터페이스 어플리케이션 (ETL, API 등)
* 스케줄링 및 JOB 메타 정보를 이용하여 ETL, API 인터페이스 데이터 적재 어플리케이션 구현
* Hive Metastore 정보를 이용하여 Impala, KUDU 테이블 및 데이터 마이그레이션 어플리케이션 구현
* 신규 ETL 인터페이스에 대한 초기적재 어플리케이션 구현
* 사용기술 : Shell, Java, Python, JSON, Hadoop, Hive, Impala. KUDU, JSON Serde
### Rest API Server
* DW/BI 관리자 WEB UI에서 Rest API를 이용하여 스케줄링, JOB, 마이그레이션 등 제어
* 사용기술 : Spring, Quartz Scheduler, Embedded Tomcat, MyBatis, Kafka
### DW
* 기간계/컨텍센터 테이블 500여개 ETL 인터페이스 및 DW 적재
* 사용기술 : HiveQL, Hive, Impala, HDFS, KUDU, Oracle Exadata
### 고객 응대등급 데이터 마트
* 고객 응대등급 팩터에 따른 세그먼트 마트
* 사용기술 : HiveQL, Hive, Impala, HDFS, KUDU

# :high_brightness: 메가박스 마케팅/캠페인 시스템
### 프로젝트 개요
* 마케팅 및 캠페인을 위한 DW/BI 시스템 신규 구축
* 프로젝트 분류 : DW/BI, 캠페인, 정보계
* 기간 : 2019년 03월 ~ 2019년 09월
* 수행역할 : DA, 모델링, 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE/SE
* OS : CentOS
* 주요기술 : ER모델링, 다차원모델링, PL-SQL, SQL*PLUS, SQLLDR, Shell
### 아키텍처 및 공통
* 전사 비즈니스 및 데이터를 분석하여, DW/BI의 개괄적인 데이터 모델 구축
* DW/BI 프로세스 정립, 개발 프로세스 상세 정의 및 표준화
* ETL 솔루션 검증 및 설계 개선
* 사용기술 : ERD, PL-SQL, SQL*PLUS, SQLLDR, Shell
### 캠페인 결과 분석
* 캠페인 결과 분석 관련 마트 (결과분석, 고객군, AB Test, 매출 등)
* 사용기술 : ERD, PL-SQL
### 고객 세그먼트
* 기본 고객 세그먼트 (성별, 연령, 지역 등)
* 세분화 고객 세그먼트 (RFM 및 상품, 관람, 매출 등 관련 고객 세그먼트)
* 사용기술 : ERD, PL-SQL
### 마켓쉐어 데이터 수집
* 마켓쉐어 데이터 인터페이스 및 적재
* 사용기술 : ERD, PL-SQL, SQLLDR

# :high_brightness: SK브로드밴드 UI 5.0 로그 데이터 분석
### 프로젝트 개요
* IPTV 셋톱박스 로그를 활용하여 마케팅 및 인터페이스 개선을 위한 데이터 분석 프로젝트
* 프로젝트 분류 : 빅데이터, DW/BI, 정보계
* 기간 : 2018년 07월 ~ 2019년 01월
* 수행역할 : 모델링, 설계, 개발
> 레거시 마트의 데이터 정합성 15%에서 70%로 향상 (원천의 로그시간 잔존 이슈 해결시 더욱 향상 될것으로 예측)
### 프로젝트 환경
* 플랫폼 : Hortonworks HDP (200 노드)
* 데이터베이스 : Oracle Exadata, Hadoop, Hive, Tez
* OS : CentOS
* 주요기술 : ER모델링, 다차원모델링, Hadoop, Hive, Tez, Oozie, Sqoop, Shell, Crontab
### 로그 데이터 전처리
* 로그 데이터 클렌징 및 변환
* 로그 분류/그룹핑 디멘션 설계
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata
> 로그 전처리 및 디멘션 작업은 기억에 남을 만한 성공작. 로그 정합성이 대폭 향상된 주요인
### 로그 데이터 분석 마트
* 사용자 행동 (메뉴 네비게이션, 선호장르, 컨텐츠 구매 등) 패턴 분석 마트
* 사용자 인터페이스 활용 (배너, UI 메뉴/블록, 시놉시스, 리모컨 등) 분석 마트
* 키즈 컨텐츠 이용 분석 마트
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata
> 250억건 데이터 전처리 및 데이터 마트 적재 소요시간이 30분 미만으로 수행됨
### 로그 연동 AI 음성인식 마트
* AI 음성인식 로그 데이터를 활용하여 기능, 활용의 개선을 위한 분석 마트
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata
### 개인화 추천블록 마트
* 선호장르, 주이용블록 등에 따른 메뉴/블록, 추천블록을 개인화 구성하기 위한 마트
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata
### 인터페이스
* 셋톱박스, AI 음성인식 로그 ETL 인터페이스 및 적재
* 추천블록 데이터 외부(AWS)로 ETL
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata, Shell, Crontab

# :high_brightness: SK브로드밴드 Ocean 빅데이터 아키텍처 개선
### 프로젝트 개요
* 성능 및 기능 향상을 위한 Hortonwork HDP 버전 업그레이드, 클러스터 노드 추가
* 프로젝트 분류 : 빅데이터, DW/BI, 정보계
* 기간 : 2017년 11월 ~ 2018년 05월
* 수행역할 : 설계, 개발, 마이그레이션
### 프로젝트 환경
* 플랫폼 : Hortonworks HDP (200 노드)
* 데이터베이스 : Oracle Exadata, Hadoop, Hive, Tez
* OS : CentOS
* 주요기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Shell, distcp
### DW, 마트 데이터 마이그레이션
* DW/BI 시스템의 2PB 데이터 마이그레이션
* 사용기술 : Hadoop, Shell, distcp
### DW 및 마트 어플리케이션 마이그레이션
* 버전 업그레이드로 인한 Hive, Tez, Sqoop 등을 사용하는 DW, 마트, ETL 어플리케이션 마이그레이션
* DW, Mart, ETL 어플리케이션, 워크플로우 새로운 표준 변경 적용
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Shell
### 모니터링 및 성능/데이터 정합성 개선 
* 모니터링을 통한 슬로우 쿼리 튜닝
* 데이터 전수 검증으로 도출된 AS-IS의 DW 및 마트 데이터 정합성 문제 개선
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Shell
> 수시간 ~ 수십분 걸리는 JOB을 모두 10분이내로 단축

# :high_brightness: SK브로드밴드 MDW 고도화
### 프로젝트 개요
* DW/BI의 신규 구축 및 기존 개선
* 프로젝트 분류 : 빅데이터, DW/BI, 정보계
* 기간 : 2017년 05월 ~ 2017년 11월
* 수행역할 : 모델링, 설계, 개발
### 프로젝트 환경
* 플랫폼 : Hortonworks HDP (100 노드)
* 데이터베이스 : Oracle Exadata, Hadoop, Hive, Tez
* OS : Red Hat
* 주요기술 : ER모델링, 다차원모델링, Hadoop, Hive, Tez, Oozie, Sqoop, Shell
### 고객 세그먼트 상세화
* 세분화 고객 세그먼트 200여개 개발 및 검증
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata
### 기업사업부문 실적 마트
* 기업사업부문 DW/BI 초기 구축을 위한 분석 및 데이터 선별
* 기존 마트에 기업사업 데이터 Append
* 기업사업부문 매출 관련 마트
* 기업사업부문 영업 관련 마트
* 사용기술 : ERD, Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata
> 데이터가 4배 정도 증가하였지만, 수시간 ~ 수십분 걸리는 JOB을 평균 10분이내로 단축
### VOD 캠페인 마트
* 새로운 캠페인 솔루션 도입으로 인한 VOD 캠페인 결과 분석 마트
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata
### 인터페이스 및 DW
* 기업사업부문 관련 ETL 인터페이스 및 DW 적재
* VOD 캠페인 관련 데이터 IN/OUT 인터페이스 및 DW 적재
* 사용기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Oracle Exadata, Shell

# :high_brightness: KEB하나은행 기관 CRM
### 프로젝트 개요
* 기관 영업 관리를 위한 신규 구축
* 프로젝트 분류 : CRM, DW/BI, 정보계
* 기간 : 2016년 12월 ~ 2017년 03월
* 수행역할 : PL, 분석, 모델링, 설계, 개발
> 운영계 시스템 같은데 정보계...
### 프로젝트 환경
* 데이터베이스 : SyBase IQ, Oracle EE
* OS : AIX
* 주요기술 : ER모델링, PL-SQL, T-SQL, ETL, MCI, EAI, Java, Neoworks Framework, xFrame, MyBatis
### Sales Force
* 기관 CRM 전체 모델링 및 설계. 사업정보, 영업기회, 영업정보, 키맨, 입찰정보, 영업일지 등
* 사업정보, 영업기회, 영업일지 등 개발
* 사용기술 : ERD, Java, Neoworks Framework, xFrame, MyBatis
### 기업 CRM 현업
* 기업 CRM과 영업활동 협업
* 사용기술 : ERD, Java, Neoworks Framework, xFrame, MyBatis
### 보고서
* 영업활동 현황 (사업, 입찰, 낙찰 등), 영업기회 관련 보고서
* 영업실적 관련 보고서
* 사용기술 : ERD, PL-SQL, T-SQL
### 인터페이스
* 기관 사업정보, 영업정보, 입찰정보 수집
* 사용기술 : ERD, Java, Neoworks Framework, xFrame, MyBatis

# :high_brightness: SK플래닛 DW Hadoop 기반 이전 구축
### 프로젝트 개요
* 기존 Tera Data에서 Hadoop 기반 DW/BI 시스템으로 마이그레이션
* 프로젝트 분류 : 빅데이터, DW/BI, 정보계
* 기간 : 2016년 07월 ~ 2016년 11월
* 수행역할 : 개발
### 프로젝트 환경
* 플랫폼 : Hortonworks HDP (200 노드)
* 데이터베이스 : Oracle EE, Hadoop, Hive, Tez
* OS : Red Hat
* 주요기술 : Hadoop, Hive, Tez, Oozie, Sqoop, Shell
### OKcashbag 마트
### 11번가 마트
### 인터페이스

# :high_brightness: KEB하나은행 CRM 통합
### 프로젝트 개요
* 외환은행과 하나은행의 CRM 통합 프로젝트
* 프로젝트 분류 : CRM, DW/BI, 정보계
* 기간 : 2015년 12월 ~ 2017년 06월
* 수행역할 : 모델링, 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE, SyBase IQ
* OS : AIX
* 주요기술 : PL-SQL, T-SQL, ETL, MCI, EAI, DW/BI, Java, Neoworks, xFrame, MyBatis
### 영업점 통합
* 영업점 통합 관련 영향도 분석 및 데이터 모델링, UI 변경 설계
* 영업점 통합 관련 300여개 DW 및 마트 변경
* 영업점 통합 관련 정보계 서비스 쿼리 2000여개 변경

# :high_brightness: SKT Wifi Sensing Data / SKT IoT Data Analiytics
### 프로젝트 개요
* IoT 허브 데이터와 Wifi 가맹점 데이터 수집 및 분석
* 프로젝트 분류 : 빅데이터, 데이터수집
* 기간 : 2015년 08월 ~ 2015년 11월
* 수행역할 : 모델링, 설계, 개발
### 프로젝트 환경
* 플랫폼 : Native Hadoop Echo System (10 노드)
* 데이터베이스 : MySQL
* OS : CentOS
* 주요기술 : Hadoop, Kafka, Spark Streaming, Spark SQL, HBase, Hive, Redis, Sqoop, Zepplin, Java, Scala, RegExp, Shell
### Hadoop Echo System 구축
*
### Real-Time Data Collector
* Kafka & Spark Stream 실시간 수집 서버 구축
* Collector 테스트용 시뮬레이터 개발
* HBase, Hive 데이터 적재 및 분석
> 서버 3대로 40만 tps 상회. Consumer에서는 1.여러가지 로그를 분류 2.로그를 정규화된 데이터로 변환하여 HDFS에 적재
### IoT 데이터 분석
* IoT 허브 로그를 분석하여, IoT의 다양한 데이터 분석
* IoT 허브 데이터에서 해당 벤더사의 데이터만 추출/분석 어플리케이션 개발
* 시스템 로그 분석 (like splunk)
### Wifi Sensing 데이터 분석
* Wifi 장비 로그를 분석하여, 가맹점내 고객의 이용 패턴, 방문 패턴 등을 분석하여 가맹점 마케팅에 활용
* Wifi 로그와 기간계 고객, 매출 등의 데이터를 함께 분석하여 가맹점 마케팅에 활용
### Zepplin 시각화
*
### 인터페이스
*

# :high_brightness: 외환은행 카드 영업지원 시스템 (CSMS)
### 프로젝트 개요
* 외환은행, 하나은행 통합 관련 시스템 운영
* 프로젝트 분류 : 계정계
* 기간 : 2014년 05월 ~ 2015년 07월
* 수행역할 : 모델링, 설계, 개발, 운영
### 프로젝트 환경
* 데이터베이스 : Oracle EE
* OS : AIX
* 주요기술 : PL-SQL, ETL, EAI, NRT, Java, Jeus, JSP, HTML, Javascript
### 카드 모집인/영업점 영업지원
*
### 계정계 공통
*

# :high_brightness: SKT Storage & Memory R&D PCI-E SSD Benchmark
### 프로젝트 개요
* 
* 프로젝트 분류 : R&D
* 기간 : 2013년 09월 ~ 2014년 02월
* 수행역할 : 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE, Hadoop, MySQL
* OS : CentOS
* 주요기술 : fio, blktrace, nmon, sysbench, hammerdb, tpcc-mysql, shell
### PCI-E SSD Disk 성능 측정
*
### PCI-E SSD Cache 성능 측정
*
### 실시스템과 동일한 환경에서 성능 측정
*
### 표준 벤치마킹 성능 측정
*

# :high_brightness: NMS(Network Management System), SMS(System Management System) 솔루션
### 프로젝트 개요
* SK, KT에서 운용중인 솔루션 고도화
* 프로젝트 분류 : 솔루션
* 기간 : 2013년 04월 ~ 2013년 09월
* 수행역할 : 모델링, 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE, MySQL
* OS : CentOS
* 주요기술 : PL-SQL, T-SQL, Java, Netty, GBP
### JVM & 데이터베이스 튜닝
*
### 프레임워크 개선
*
### 대용량 데이터 어플리케이션
*

# :high_brightness: 농협 통합 캠페인 시스템 (CMS)
### 프로젝트 개요
* 
* 프로젝트 분류 : CRM, 캠페인, DW/BI, 정보계
* 기간 : 2012년 09월 ~ 2012년 12월
* 수행역할 : 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE
* OS : AIX
* 주요기술 : PL-SQL, T-SQL, Java, Flex, Weblogic
### 캠페인 결과/실적 데이터 마트
*
### 인터페이스
*
### 캠페인 온라인 어플리케이션
* ACS, TM

# :high_brightness: 외환은행 뱅킹 차세대 CRM
### 프로젝트 개요
* 
* 프로젝트 분류 : CRM, DW/BI, 정보계
* 기간 : 2012년 03월 ~ 2012년 09월
* 수행역할 : TA, DA, AA
### 프로젝트 환경
* 데이터베이스 : SyBase IQ, Oracle EE
* OS : AIX
* 주요기술 : PL-SQL, T-SQL, ETL, EAI, NRT, Java, Jeus, Miplatform
### 데이터 아키텍처
*
### 테크니컬 아키텍처
*
### 어플리케이션 아키텍처
* 
### 공통 개발
*
### 개발 지원
*

# :high_brightness: 미쓰이스미토모(SMBC) 뱅킹 계정계 차세대
### 프로젝트 개요
* 
* 프로젝트 분류 : 계정계, DW/BI
* 기간 : 2011년 08월 ~ 2012년 02월
* 수행역할 : 설계, 개발
### 프로젝트 환경
* 데이터베이스 : MS-SQL, Oracle EE
* OS : Windows Server
* 주요기술 : T-SQL, PL-SQL, Java, Spring Framework, xFrame, iBatis
### 수신
* 수신. 예금, 일계(이자, 세금 등), CC, 대인터넷뱅킹 수신 서비스
### 데이터 인터페이스
*

# :high_brightness: 외환은행 카드 CRM
### 프로젝트 개요
* 
* 프로젝트 분류 : CRM, DW/BI, 정보계
* 기간 : 2009년 08월 ~ 2011년 07월
* 수행역할 : 모델링, 설계, 개발, 운영
### 프로젝트 환경
* 데이터베이스 : Oracle EE, SyBase IQ
* OS : AIX
* 주요기술 : PL-SQL, T-SQL, ETL, EAI, NRT, Java, Weblogic, Miplatform
### 분석 CRM
* 
### 인터페이스
*
### 시그니처/플래티늄 카드 부가서비스 발급
*
### 카드운영센터 온라인 어플리케이션
*

# :high_brightness: 동부생명 재무설계 시스템
### 프로젝트 개요
* 
* 프로젝트 분류 : 계정계
* 기간 : 2008년 06월 ~ 2009년 02월
* 수행역할 : 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE
* OS : AIX
* 주요기술 : ROR, Flex, PureMVC
### 재무설계
* 

# :high_brightness: 국민권익위원회 110 정부민원콜센터
### 프로젝트 개요
* 
* 프로젝트 분류 : 고객센터, 정보계
* 기간 : 2007년 12월 ~ 2008년 05월
* 수행역할 : 모델링, 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE
* OS : AIX
* 주요기술 : PL-SQL, Java, MiPlatform
### 캠페인
* 
### 튜닝
* 
### 고객 데이터
* 
###
* 

# :high_brightness: 씨티은행 카드 통합 CRM
### 프로젝트 개요
* 
* 프로젝트 분류 : 고객센터, 정보계
* 기간 : 2007년 08월 ~ 2007년 11월
* 수행역할 : 모델링, 설계, 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE
* OS : AIX
* 주요기술 : PL-SQL, EAI, Java, JSP, HTML, Javascript
### 운영 CRM
* 
### 튜닝
* 

# :high_brightness: 외환은행 BPM (G2G)
### 프로젝트 개요
* 
* 프로젝트 분류 : 계정계
* 기간 : 2007년 03월 ~ 2007년 06월
* 수행역할 : 설계, 개발, 운영
### 프로젝트 환경
* 데이터베이스 : Oracle EE
* OS : AIX
* 주요기술 : PL-SQL, ETL, EAI, NRT, Java, Struts, Jeus, MiPlatform, Filenet, JSP, HTML, Javascript
### 유학생
* 

# :high_brightness: 대우증권 국제 브로커리지
### 프로젝트 개요
* 
* 프로젝트 분류 : 기간계
* 기간 : 2007년 02월 ~ 2007년 03월
* 수행역할 : 개발
### 프로젝트 환경
* 데이터베이스 : Oracle EE
* OS : AIX
* 주요기술 : Java, Struts, Jeus, MiPlatform
### 국제 브로커리지
* 
### 보고서
*

# :high_brightness: 농협 eShop
### 프로젝트 개요
* 
* 프로젝트 분류 : 기간계
* 기간 : 2006년 10월 ~ 2007년 01월
* 수행역할 : 개발
### 프로젝트 환경
* 데이터베이스 : Informix
* OS : AIX
* 주요기술 : Java, Jeus, JSP, HTML, Javascript
### BO
* 
### Front
*

# :high_brightness: 미래에셋 사고이미지
### 프로젝트 개요
* 
* 프로젝트 분류 : 기간계
* 기간 : 2006년 07월 ~ 2006년 09월
* 수행역할 : 개발
### 프로젝트 환경
* 데이터베이스 : MS-SQL, Oracle EE
* OS : Windows NT
* 주요기술 : ASP, Filenet, HTML, Javascript, IIS
### 사고조사 이미지
* 
### 조사지원
*
### 보고서
*

# :high_brightness: 엘림넷
### 프로젝트 개요
* 
* 프로젝트 분류 : 플랫폼
* 기간 : 2005년 02월 ~ 2006년 01월
* 수행역할 : 운영
### 프로젝트 환경
* 데이터베이스 : MySQL, MS-SQL, Oracle EE
* OS : Solais, Fedora
* 주요기술 : MySQL, T-SQL, Java, JSP, HTML, Javascript, Shell, MRTG
### 모니터링 시스템
* 
### 영세 업체 지원??
*

# :high_brightness: 인카르타
### 프로젝트 개요
* 
* 프로젝트 분류 : 플랫폼
* 기간 : 1999년 08월 ~ 2002년 05월
* 수행역할 : 설계, 개발, 운영
> 모델링도 했지만 차마 ...
### 프로젝트 환경
* 데이터베이스 : MS-SQL, MySQL
* OS : Windows NT, Red Hat
* 주요기술 : ASP, Java, JSP, HTML, Javascript
### 샤크몰 쇼핑몰 구축
*
### 인트라넷/웹사이트 구축
* 
### 인트라넷/웹사이트 운영
*
