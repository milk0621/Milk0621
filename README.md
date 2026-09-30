![header](https://capsule-render.vercel.app/api?&type=waving&color=timeAuto&height=180&section=header&text=JiSeon's%20Hub&fontSize=50&animation=fadeIn&fontAlignY=45)

<div align='center'>

💻 디자인에서 출발해, 문제 해결로 확장해나가는 **백엔드 개발자 김지선**입니다.<br />
프로젝트뿐만 아니라 하루하루 공부하고 있는 내용들을 기록하고 있습니다.

<br />

<a href="mailto:wltjs5360@naver.com"><img src="https://img.shields.io/badge/Email-wltjs5360@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://www.notion.so/1ee6731d268a81988510e9b04de46ea1?source=copy_link"><img src="https://img.shields.io/badge/Notion-기록-000000?style=flat-square&logo=notion&logoColor=white" /></a>

</div>

<br />

## 🚀 Main Projects

### [TechConf](https://github.com/milk0621/TechConf) · IT 컨퍼런스 예약 관리 플랫폼
`2026.08 ~ 2026.09` · 멋쟁이사자처럼 백엔드 24기 최종 프로젝트 (4인) · [🔗 서비스](https://techconf.duckdns.org)

- 컨퍼런스 탐색부터 세션 신청·결제·QR 입장·후기까지 한 곳에서 처리하는 **MSA 기반** 플랫폼
- 동시 신청에도 정원을 넘지 않는 좌석 홀드와 대기열 자동 승격, PortOne 결제, Gemini AI 요약
- **담당**: 회원 인증(JWT + Refresh Token HttpOnly 쿠키), 주최자 이메일 인증·국세청 사업자 상태조회, 소셜 로그인, 프론트엔드, Docker·EC2 배포

`Spring Boot` `Spring Cloud Gateway` `Spring Security` `JPA` `MySQL` `React` `Docker` `GitHub Actions` `AWS EC2`

### [Prep2gether](https://github.com/milk0621/prep2gether) · 취업 준비 커뮤니티
`2026.07 ~ 2026.08` · 멋쟁이사자처럼 백엔드 24기 팀 프로젝트 (4인) · [🔗 서비스](http://prep2gether.duckdns.org)

- 취업 정보 공유, 스터디 모집·운영, 전문가 1:1 상담을 하나의 흐름으로 잇는 커뮤니티
- PortOne 빌링키 정기결제 구독, 결제 재조회 검증, 웹훅 멱등 처리, 비관적 락 기반 상담 동시성 제어
- **담당**: 스터디 도메인 전체(모집·가입·멤버 관리·전용 게시판, 비관적 락으로 정원 초과 동시성 해결, `StudyAccessValidator`로 검증 로직 통합), 도메인 간 책임 정리 리팩터링(어드민 → 도메인 서비스 경유), S3 파일 업로드 공통 인프라, PortOne 웹훅 서명 검증, CI/CD 배포

`Spring Boot` `Spring Security` `JPA` `MySQL` `React` `AWS S3` `Docker` `GitHub Actions` `AWS EC2`

### [Barotago](https://github.com/milk0621/barotago) · 지하철 정보 서비스
`2025.10 ~` · 개인 프로젝트

- 역 정보·열차 시간표·실시간 도착정보를 카카오 지도와 함께 보여주는 서비스
- 공공데이터를 Python 스크립트로 수집·정제해 DB에 적재하고, 서울 열린데이터 실시간 도착 API 연동, 급행 열차 구분 로직 구현

`Spring Boot` `MyBatis` `MySQL` `React` `Python` `Kakao Map API`

<br />

## 🌱 Earlier Projects

| 프로젝트 | 소개 | 기술 |
| --- | --- | --- |
| [News Stock](https://github.com/milk0621/project-news-stock) | 금융 뉴스 감성 분석(KorFinBERT)과 LSTM 기반 KOSPI 예측 시각화 | JSP · Python · TensorFlow · WebSocket |
| [Jeonbuk Tour](https://github.com/milk0621/project-jeonbuk-tour) | 리뷰 키워드 기반 관광지 추천과 거리 기반 여행 코스 자동 생성 | Flask · Python · MySQL · Kakao Map |

<br />

## 📚 Tech Stack

<p>
  <b>Backend</b><br />
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/spring%20boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/spring%20security-%236DB33F.svg?style=for-the-badge&logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA%20%2F%20MyBatis-59666C?style=for-the-badge&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white" />
</p>
<p>
  <b>Database</b><br />
  <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" />
</p>
<p>
  <b>Frontend</b><br />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/Thymeleaf-%23005C0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white" />
</p>
<p>
  <b>Infra / DevOps</b><br />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" />
  <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

![footer](https://capsule-render.vercel.app/api?type=waving&color=timeAuto&height=100&section=footer)
