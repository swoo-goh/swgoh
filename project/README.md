# NS홈쇼핑 BDA
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
* 사용기술 : Shell, Java, Python, JSON, JSON Serde, XML Serde
* 테이블, 컬럼, 스케줄링 JOB 메타 정보를 이용하여 ETL, API 인터페이스를 이용한 데이터 적재 어플리케이션 구현
* Hive Metastore 정보를 이용하여 Impala, KUDU 테이블 및 데이터 마이그레이션 어플리케이션 구현
* 신규 ETL 인터페이스에 대한 초기적재 어플리케이션 구현
### DW
### Data Mart

# 메가박스 마케팅/캠페인 시스템
### 프로젝트 개요
* DW/BI 용도의 시스템 신규 구축
* 기간 : 2019년 03월 ~ 2019년 09월
* 수행역할 : DA, 모델링, 설계, 개발
* 팀구성 : PL 1, DW/BI 2, ETL 1
### 공통
* 
* 사용기술 : PL-SQL, 
### 캠페인 결과 분석
* 캠페인 결과 분석 관련 마트, AB Test
### 고객 세그먼트
* RFM 및 20여 분류의 상세화 고객 세그먼트
### 마켓쉐어 데이터 수집

# SK브로드밴드 UI 5.0 로그 데이터 분석
### 프로젝트 개요
* DW/BI 용도의 시스템 신규 구축
* 기간 : 2018년 07월 ~ 2019년 01월
* 수행역할 : 모델링, 설계, 개발
* 팀구성 : PL 1, DW/BI 3
> 이전 UI 4.0 프로젝트 분석 데이터 정합성 15%에서 70%로 향상 (원천 로그 시간 이슈로 70%이며, 이슈 제거시 대폭 향상 될것으로 예측)
> 프로젝트 중간부터 원맨 프로젝트
### 로그 데이터 전처리
* 사용기술 : Hive, Tez, Oozie, Sqoop, Oracle Exadata
### 로그 데이터 분석 마트
### 로그 분석 시각화 마트
### 로그 연동 매출 마트
### 로그 연동 AI 음성 마트
### 개인화 추천블록 마트
### ETL

2017년 11월 ~ 2018년 5월 / SK브로드밴드 Ocean 빅데이터 아키텍처 개선
사용기술 : Hadoop, Ambari, Hive, Tez, Oozie, Sqoop, Oracle ExaData, Shell, DW/BI
수행역할 : 마이그레이션, 개발
수행내용
- Hadoop 에코 시스템 버전 업그레이드에 의한 데이터 마이그레이션
- Hadoop 에코 시스템 버전 업그레이드로 인한 이슈해결 및 어플리케이션 마이그레이션
- Ambari 설정 최적화

2017년 05월 ~ 2017년 11월 / SK브로드밴드 MDW 고도화
사용기술 : Hadoop, Ambari, Hive, Tez, Oozie, Sqoop, Oracle ExaData, Shell, DW/BI
수행역할 : 분석, 모델링, 설계, 개발
수행내용
- 고객 세그먼트 상세화
- 기업사업부문 실적 마트
- VOD 캠페인 마트
- CDC, ETL 인터페이스 및 DW 구축

2016년 12월 ~ 2017년 03월 / KEB하나은행 기관 CRM
사용기술 : AIX, Oracle EE, SyBase IQ, PL-SQL, T-SQL, ETL, EAI, NRT, Java, Neoworks, xFrame
수행역할 : PL, 분석, 모델링, 설계, 개발
수행내용
- 기관 CRM 전체 모델링 및 설계. 사업정보, 영업기회, 영업정보, 키맨, 입찰정보, 영업일지 등
- 유연한 영업활동 프로세스에 초점을 맞춘 모델링 및 설계
- 사업정보, 영업기회, 영업일지 등 개발

2016년 07월 ~ 2016년 11월 / SK플래닛 DW Hadoop 기반 이전 재구축
사용기술 : Red Hat, Hadoop, Hive, Tez, Oozie, Sqoop, Shell, MySQL, CDC, ETL, DW/BI
수행역할 : 개발
수행업무
- OkCashbag 마케팅 DW 및 마트

2015년 12월 ~ 2016년 06월 / KEB하나은행 CRM
사용기술 : AIX, Oracle, SyBase IQ, PL-SQL, T-SQL, ETL, EAI, NRT, DW/BI, Java, Neoworks, xFrame, MCI
수행역할 : 개발
수행업무
- 하나/외환은행 영업점 통합 관련 DW, 마트, 온라인 어플리케이션 개발

2015년 09월 ~ 2015년 11월 / SKT IoT Data Analiytics
사용기술 : CentOS, Hadoop, Spark(Stream, SQL), Kafka, Hive, HBase, Zepplin, Zookeeper, Java Daemon, MariaDB
수행역할 : 분석, 모델링, 설계, 개발
수행업무
- IoT 클라우드 실시간 로그 및 서버 로그 데이터 수집/적재, 분석 전체 개발

2015년 08월 ~ 2015년 10월 / SKT Wifi Sensing Data
사용기술 : CentOS, Hadoop, Spark(Stream, SQL), Kafka, Hive, Java Daemon, MariaDB
수행역할 : 분석, 모델링, 설계, 개발
수행업무
- SKT Wifi AP 로그 실시간 데이터 수집, 적재/분석 전체 개발

2014년 05월 ~ 2015년 07월 / 외환은행 CSMS(Card Sales Management System)
사용기술 : AIX, Oracle, SyBase IQ, PL-SQL, T-SQL, ETL, EAI, NRT, DW, mart, Java, Java Daemon, Jeus, JSP, HTML, Javascript
수행역할 : 분석, 설계, 개발
수행업무
- 카드영업지원시스템 (모집인, 영업점)
- 하나/외환카드 통합 관련 계정계 공통. 통합 인사/영업점

2013년 09월 ~ 2014년 01월 / SKT Storage & Memory R&D PCI-E SSD Benchmark
사용기술 : CentOS, Oracle, MySQL, fio, blktrace, nmon, sysbench, hammerdb, tpcc-mysql, shell
수행업무
- PCI-E SSD를 Disk, Cache로 활용한 OLTP, Database, Hadoop 시스템의 성능 측정

2013년 04월 ~ 2013년 09월 / 모비젠 NMS(Network Management System), SMS(System Management System)
사용기술 : CentOS, Oracle, MySQL, PL-SQL, T-SQL, Java Deamon, Netty, GBP
수행역할 : 분석, 설계, 개발
수행업무
- NMS & SMS 서버 어플리케이션 및 DB 튜닝, 프레임워크 개선 등 고도화

2012년 09월 ~ 2012년 12월 / 농협 CMS(Campaign Management System)
사용기술 : AIX, Oracle, PL-SQL, ETL, DM, Flex, Weblogic
수행역할 : 개발
수행업무
- 캠페인 ACS 및 TM 관련 마트 및 온라인 어플리케이션 개발

2012년 03월 ~ 2012년 09월 / 외환은행 뱅킹 차세대 CRM(Customer Relationship Management)
사용기술 : AIX, Oracle, SyBase IQ, PL-SQL, T-SQL, ETL, EAI, NRT, Java, Jeus, Miplatform, DW/BI
수행역할 : DA, AA
수행업무
- DW/BI 및 OLTP 아키텍처 전반, 프레임워크 구축, 공통 DW/OLTP DB, 배치/온라인 어플리케이션

2011년 08월 ~ 2012년 02월 / 미쓰이스미토모(SMBC) 뱅킹 계정계 차세대
사용기술 : Windows Server, MS-SQL, Oracle, T-SQL, PL-SQL, Java, Spring, xFrame
수행역할 : 설계, 개발
수행업무
- 수신. 예금, 일계(이자, 세금 등), CC, 대인터넷뱅킹 수신 서비스

2009년 08월 ~ 2011년 07월 / 외환은행 카드 CRM(Customer Relationship Management)
사용기술 : AIX, Oracle, SyBase IQ, PL-SQL, T-SQL, ETL, EAI, NRT, Java Daemon, Weblogic, Miplatform, DW/BI
수행역할 : 운영
수행업무
- 고객센터, 캠페인, TM, 부가서비스/PP카드 발급 관련 DW/DM 및 온라인 어플리케이션

2008년 06월 ~ 2009년 02월 / 동부생명 재무설계 시스템
사용기술 : AIX, Oracle, ROR, Flex, PureMVC
수행역할 : 설계, 개발
수행업무
- 종합재무 지표, 계획, 설계 및 시뮬레이션

2007년 12월 ~ 2008년 05월 / 국민권익위원회 110 정부민원콜센터
사용기술 : AIX, Oracle, PL-SQL, Java, MiPlatform
수행역할 : 분석, 설계, 개발
수행업무
- DB 및 어플리케이션 튜닝, 공통 DB 및 어플리케이션, 캠페인

2007년 08월 ~ 2007년 11월 / 씨티은행 카드 통합 CRM(Customer Relationship Management)
사용기술 : AIX, Oracle, PL-SQL, EAI, Java, JSP, HTML, Javascript
수행역할 : 설계, 개발
수행업무
- 공통 어플리케이션, 운영/지원 CRM 관련 배치, 온라인 어플리케이션 및 통계

2007년 03월 ~ 2007년 06월 / 외환은행 G2G
사용기술 : AIX, Oracle, PL-SQL, ETL, EAI, NRT, Java, Struts, Jeus, MiPlatform, Filenet, JSP, HTML, Javascript
수행역할 : 개발
수행업무
- 외환 유학생 관련 배치/온라인/BPM

2007년 02월 ~ 2007년 03월 / 대우증권 국제 브로커리지
사용기술 : AIX, Oracle, Java, Struts, Jeus, MiPlatform
수행역할 : 개발
수행업무
- 국제 브로커리지 매도, 매수 신청서 및 집계, 보고서

2006년 10월 ~ 2007년 01월 / 농협 eShop
사용기술 : AIX, Informix, Java, Jeus, JSP, HTML, Javascript
수행역할 : 개발
수행업무
- 공통 어플리케이션, BO & Front 전반, 상품 카테고리 및 리스트, 상세, 주문, 결제, 장바구니, 쿠폰 등

2006년 07월 ~ 2006년 09월 / 미래에셋 사고이미지
사용기술 : Windows NT, Oracle, MS-SQL, ASP, Filenet, HTML, Javascript, IIS
수행역할 : 개발
수행업무
- 사고조사 스캔 이미지 관리 및 조사지원 어플리케이션, 통계

2005년 02월 ~ 2006년 01월 / (주)엘림넷 운영팀
사용기술 : Fedora, MySQL, Transactional SQL, Java, JSP, HTML, Javascript, Shell, MRTG
수행역할 : 운영
수행업무
- 서버/네트워크 모니터링 데이터 수집 및 적재

1999년 08월 ~ 2002년 05월 / 인카르타 개발팀
사용기술 : Windows NT, MS-SQL, ASP, HTML, Javascript, IIS, AD DS, EMWAC
Red Hat, MySQL, Java, JSP, Tomcat, Resin
수행역할 : 분석, 설계, 개발, 운영
수행업무
- 웹사이트, 인트라넷, 쇼핑몰 구축 및 운영

1998년 01월 ~ 1999년 03월 / 한덕엔지니어링 통신실
수행업무
- 통신