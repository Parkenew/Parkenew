
## 🧑‍💻 About Me
- **Introduce**
  - 안녕하세요! 소프트웨어 엔지니어 박건우입니다.
  - 대기업에서 Elastic Stack 기반으로 로그 모니터링 시스템을 구축하고 운영한 경험이 있습니다.

- **Profile**
  - 서경대학교 컴퓨터공학과 졸업
  - 로이드케이 Elasticsearch Engineer 재직 ( 25.02 ~ 현재 )

## 🚀 Career
>### LLOYDK - Elasticsearch Engineer ( 25.02 ~ 현재 )
> - **LG U+ 로그 모니터링 프로젝트**
> 	- Elastic Stack 기반 데이터 파이프라인 구축 및 운영
>     - Elasticsearch 3-노드 클러스터 구축
> 		- 로그 수집·정제 파이프라인 운영(일 30억+ 로그 이벤트 처리)
> 		- 로그 파티셔닝 로직 개발 및 S3 적재
> 		- 로그 파싱 로직 리팩토링 및 성능 최적화
>       - ES 조회 기반 매핑 로직을 Logstash translate(in-memory dictionary)로 치환하여 조회 I/O 및 파이프라인 지연 감소
>       - 병목 구간 분석 후 batch size, worker, ES shard 수 튜닝하여 처리량 및 인덱싱 지연 개선(5000EPS → 40000EPS, indexing latency 14ms→1ms)
> 	- 모니터링/알림 체계 구축
> 		- 운영 모니터링 목적의 대시보드 설계·구현(팀별 수집 현황, 일별 수집 용량 추이, 예외 케이스 발생 현황 시각화)
> 		- Email 연동 Alert 로직 개발로 이상 징후 자동 탐지 및 즉시 대응 체계 구축
> 		
> - **벡터검색 시연 웹페이지 제작 프로젝트**
>   - 시연 데이터 파이프라인 구성
>     - 시연 데이터 선정 및 전처리
>     - 임베딩 모델 성능 비교 분석 후 multilingual-e5-large 선정
>     - 임베딩 데이터 Elasticsearch Bulk 인덱싱 
> 	- 웹 서비스 개발(풀스택)
> 		- React 기반 프론트엔드 개발
>		  - Spring Boot 기반 백엔드 개발
>       - 검색/임베딩/인덱싱 API 구현
> 	
> - **기술 스택**
> 	- Elastic Stack(ELK), SpringBoot, React.js


## 📖 Study Experience
- 주식회사 구름 클라우드 네이티브 개발자 과정 수료 (640시간)
- 서경대학교 산학협력 SW 아카데미 클라우드/백엔드 과정 수료 (720시간)
- AWS 주관 생성형 AI 활용 애플리케이션 개발 캠프 (24시간)
## 🪪 Certificate
- Elastic Certified Engineer
- AWS Certified Security Specialty
- AWS Certified Cloud Practitioner
- 정보처리기사
- 리눅스마스터2급
## 🗂️ Toy Project
**IoT 모니터링** [GitHub](https://github.com/Parkenew/IoTmonitoring)
> 간략소개: 서초구 실내공기질 데이터 실시간 모니터링
> - 프로젝트 기간: 2025.03.06 ~ 2025.03.30
> - 상세 내용: 
> 	- 데이터 파이프라인 구축
> 		- 서초구 실내공기질 데이터셋을 실시간으로 발생하도록 구현
> 		- FileBeat를 사용하여 실시간 데이터 Kafka로 전달
> 		- Logstash를 사용하여 Kafka의 데이터를 스트리밍 처리하여 데이터 적재
>   - 모니터링 대시보드 구축
>   	- Kibana 대시보드 제작
> - 기술 스택
> 	- Elastic Stack, Apache Kafka

## 🗂️ Team Project
**온보딩티켓**
[GitHub](https://github.com/SKUWooU) - 학부 프로젝트 경진대회 은상 수상🥈
> 간략소개: 공연 티켓팅 웹서비스
> - 프로젝트 기간: 2024.04.19 ~ 2024.06.20
> - 담당 파트: 백엔드 개발 및 인프라 구축
> - 상세 내용:
> 	- 벡엔드 개발
>     - 로그인(Oauth2,JWT)API 개발
>     - 공연 좌석 예매 API 개발
> 		- Spring Batch를 활용한 배치성 데이터 업데이트 시스템 구현
> 	- 인프라 구축
> 		- 백엔드 서버 이중화 배포
> 		- 리버스 프록시를 통한 로드 밸런싱 설정
> 		- 도메인 발급 및 SSL 인증서 발급
> 		- DNS 등록
> - 기술 스택
> 	- SpringBoot, JPA, MariaDB, Nginx, Docker
> 		
**Book Network** [GitHub](https://github.com/goorm-k8s-3rd)
> 간략소개: 책 리뷰 커뮤니티 웹서비스
> - 프로젝트 기간: 2023.03.13 ~ 2023.04.12
> - 담당 파트: 인프라 구축
> - 상세 내용: 
> 	- 인프라 구축
> 		- AWS EKS 환경 설정
> 		- helm을 이용한 grafana/prometheus 컨테이너 배포
> - 기술 스택
> 	- Kubernetes, Grafana, Prometheus 



