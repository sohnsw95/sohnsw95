<p align="center">
  <a href="https://sukwoo-portfolio.vercel.app/"><img src="assets/header.svg" width="100%" alt="손석우 — 사용자의 문제를 이해하고, 구현부터 운영까지 연결합니다." /></a>
</p>

<p align="center">
  <a href="https://sukwoo-portfolio.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-바로가기-B7F267?style=for-the-badge&amp;labelColor=172319" alt="포트폴리오 바로가기" /></a>
  <a href="mailto:sohnsw95@naver.com"><img src="https://img.shields.io/badge/EMAIL-sohnsw95%40naver.com-343D46?style=for-the-badge&amp;labelColor=172319" alt="이메일 sohnsw95@naver.com" /></a>
</p>

<p align="center"><a href="https://sukwoo-portfolio.vercel.app/">sukwoo-portfolio.vercel.app</a></p>

## 소개

안녕하세요. **사용자 요구를 백엔드 기능으로 만들고, 배포·운영까지 연결하는 개발자 손석우입니다.**

대학정보공시 시스템 운영에서 사용자 요청과 데이터 품질을 다뤘고, 직접 기능을 구현하는 개발자로 경험을 넓혔습니다.<br/>
사용자 도메인 API, AI 작업의 비동기 연동, 여러 서비스의 배포 환경을 만들어 왔습니다.

<br/>

## Projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/sohnsw95/Theseus"><img src="assets/theseus.png" height="200" alt="Theseus AI 도구 목록 서비스 화면" /></a>
<h3><a href="https://github.com/sohnsw95/Theseus">01 · Theseus</a></h3>
<b>AI Agent 플랫폼</b>
<p>자연어로 AI 도구를 생성하고,<br/>원격 서버와 연동해 반복 업무를 자동화하는 서비스.</p>
<p><b>팀장 · 인프라 · 백엔드</b><br/>Kafka 요청·Redis 상태 저장, 배포 환경 구성,<br/>Remote Workspace EC2 연결</p>
<p><code>Spring Boot</code> <code>Kafka</code> <code>Docker</code></p>
<p><a href="https://github.com/sohnsw95/Theseus#readme">README</a> · <a href="https://github.com/sohnsw95/Theseus/blob/main/docs/screens.md">화면 포트폴리오</a></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/sohnsw95/SSAFY-Stock"><img src="assets/stock.png" height="200" alt="싸피증권 실시간 시세 및 모의투자 화면" /></a>
<h3><a href="https://github.com/sohnsw95/SSAFY-Stock">02 · SSAFY-Stock</a></h3>
<b>실시간 모의투자 서비스</b>
<p>실시간 시세와 주문·체결,<br/>투자 커뮤니티를 제공하는 주식 모의투자 서비스.</p>
<p><b>팀장 · 인프라 · 백엔드</b><br/>회원·관심종목·Gateway, CI/CD<br/>후속 연동: 커뮤니티·주주 배지·좋아요·SQL</p>
<p><code>Spring Boot</code> <code>Redis</code> <code>Jenkins</code></p>
<p><a href="https://github.com/sohnsw95/SSAFY-Stock#readme">README</a> · <a href="https://github.com/sohnsw95/SSAFY-Stock/blob/main/docs/screens.md">화면 포트폴리오</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p align="center"><a href="https://github.com/sohnsw95/One-step"><img src="assets/onestep.png" height="225" alt="One-step 일일 루틴 Figma 디자인 화면" /></a></p>
<h3><a href="https://github.com/sohnsw95/One-step">03 · One-step</a></h3>
<b>일상 회복 지원 서비스</b>
<p>고립·은둔 청년의 일상 회복을 돕는<br/>행동 유도 기반 Android 서비스.</p>
<p><b>백엔드</b><br/>사용자·펫 상태·편지 API,<br/>수신 이력을 반영한 편지 매칭</p>
<p><code>Java</code> <code>Spring Boot</code> <code>JPA</code></p>
<p><a href="https://github.com/sohnsw95/One-step#readme">README</a> · <a href="https://github.com/sohnsw95/One-step/blob/main/docs/screens.md">화면 포트폴리오</a></p>
</td>
<td width="50%" valign="top">
<a href="https://sukwoo-portfolio.vercel.app/"><img src="assets/portfolio.svg" width="100%" alt="공개 포트폴리오 — 화면과 구조, 문제를 해결한 과정까지" /></a>
<h3>프로젝트를 더 자세히</h3>
<p>서비스 화면과 시스템 구조,<br/>담당 업무와 문제 해결 과정을 담았습니다.</p>
<p>AI 기능을 실제 서비스에 연결하고,<br/>서버와 운영 환경을 구성한 경험을 소개합니다.</p>
<p><a href="https://sukwoo-portfolio.vercel.app/"><b>포트폴리오 방문하기 ↗</b></a></p>
</td>
</tr>
</table>

<br/>

## 구현에서 다룬 주제

| 주제 | 경험과 판단 |
|---|---|
| **사용자 행동을 도메인 규칙으로** | One-step의 편지 수신 이력, 싸피증권의 관심종목·작성자 권한·주주 배지를 API와 조회 조건으로 구현했습니다. [One-step](https://github.com/sohnsw95/One-step/blob/main/docs/engineering.md) · [싸피증권](https://github.com/sohnsw95/SSAFY-Stock/blob/main/docs/engineering.md) |
| **AI 요청을 실행 가능한 서비스로** | Theseus의 Kafka 요청 발행·소비와 Redis 상태 저장을 연결하고 DB 정리·백그라운드 실행 단위를 점검했습니다. [Theseus](https://github.com/sohnsw95/Theseus/blob/main/docs/engineering.md) |
| **팀의 구현을 배포로 연결하기** | Compose 실행 영역과 Jenkins 배포 조건을 나누고, 팀장으로 일정·API·파트 간 연동을 조율했습니다. |

<br/>

## 🚀 Experience

### 🏢 한국대학교육협의회

**대학정보공시 시스템 운영·유지보수 | 2020.12 ~ 2023.06**

- 대학정보공시 통합 시스템 및 [대학알리미](https://www.academyinfo.go.kr/index.do) 운영
- 사용자 요청 접수·분류 및 요구사항 조율
- 공시 데이터 검증 및 품질 점검
- 사용자 매뉴얼·연수자료 제작 및 교육

### 🎓 SSAFY 14기

**2025.07 ~ 2026.06 · Backend · Infrastructure · Team Leadership**

- Python 기반 알고리즘 학습 및 문제 해결
- 프로젝트 3회 중 2회 팀장으로 일정 관리와 협업 조율

<br/>

## 팀 수상

| 프로젝트 | 수상 |
|---|---|
| Theseus | 자율 프로젝트 우수상<br/>프로젝트 전시발표회 발표부문 우수상 |
| SSAFY-Stock | 특화 프로젝트 우수상 |
| One-step | 공통 프로젝트 우수상 |

<br/>

## 🛠 Tech & Tools

실제 개발·연동·운영에 사용한 도구입니다. 프로젝트 전체 기술과 개인 구현 범위는 각 README에 구분했습니다.

#### Language & Backend

<table>
<tr><td align="center" width="88"><img src="assets/tech/java.svg" width="44" height="44" alt="Java"/><br/><sub>Java</sub></td><td align="center" width="88"><img src="assets/tech/python.svg" width="44" height="44" alt="Python"/><br/><sub>Python</sub></td><td align="center" width="88"><img src="assets/tech/spring.svg" width="44" height="44" alt="Spring Boot"/><br/><sub>Spring Boot</sub></td><td align="center" width="88"><img src="assets/tech/fastapi.svg" width="44" height="44" alt="FastAPI"/><br/><sub>FastAPI</sub></td></tr>
</table>

#### Data & Messaging

<table>
<tr><td align="center" width="88"><img src="assets/tech/mysql.svg" width="44" height="44" alt="MySQL"/><br/><sub>MySQL</sub></td><td align="center" width="88"><img src="assets/tech/postgres.svg" width="44" height="44" alt="PostgreSQL"/><br/><sub>PostgreSQL</sub></td><td align="center" width="88"><img src="assets/tech/kafka.svg" width="44" height="44" alt="Kafka"/><br/><sub>Kafka</sub></td><td align="center" width="88"><img src="assets/tech/redis.svg" width="44" height="44" alt="Redis"/><br/><sub>Redis</sub></td></tr>
</table>

#### Infrastructure

<table>
<tr><td align="center" width="88"><img src="assets/tech/docker.svg" width="44" height="44" alt="Docker"/><br/><sub>Docker</sub></td><td align="center" width="88"><img src="assets/tech/jenkins.svg" width="44" height="44" alt="Jenkins"/><br/><sub>Jenkins</sub></td><td align="center" width="88"><img src="assets/tech/nginx.svg" width="44" height="44" alt="Nginx"/><br/><sub>Nginx</sub></td><td align="center" width="88"><img src="assets/tech/aws.svg" width="44" height="44" alt="AWS"/><br/><sub>AWS</sub></td></tr>
<tr><td align="center" width="88"><img src="assets/tech/linux.svg" width="44" height="44" alt="Linux"/><br/><sub>Linux</sub></td></tr>
</table>

#### Development & Collaboration

<table>
<tr><td align="center" width="88"><img src="assets/tech/git.svg" width="44" height="44" alt="Git"/><br/><sub>Git</sub></td><td align="center" width="88"><img src="assets/tech/github.svg" width="44" height="44" alt="GitHub"/><br/><sub>GitHub</sub></td><td align="center" width="88"><img src="assets/tech/gitlab.svg" width="44" height="44" alt="GitLab"/><br/><sub>GitLab</sub></td><td align="center" width="88"><img src="assets/tech/swagger.svg" width="44" height="44" alt="Swagger"/><br/><sub>Swagger</sub></td></tr>
<tr><td align="center" width="88"><img src="assets/tech/jira.svg" width="44" height="44" alt="Jira"/><br/><sub>Jira</sub></td><td align="center" width="88"><img src="assets/tech/notion.svg" width="44" height="44" alt="Notion"/><br/><sub>Notion</sub></td><td align="center" width="88"><img src="assets/tech/mattermost.svg" width="44" height="44" alt="Mattermost"/><br/><sub>Mattermost</sub></td></tr>
</table>

<br/>

## Contact

[Portfolio](https://sukwoo-portfolio.vercel.app/) · [GitHub](https://github.com/sohnsw95) · [sohnsw95@naver.com](mailto:sohnsw95@naver.com)
