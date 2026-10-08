<div align="center">

# 🛡️ 이지원 | Lee JiWon

### 공격을 이해하고, 탐지하고, 안전하게 만드는 보안 지향 개발자

덕성여자대학교 사이버보안전공

[![Email](https://img.shields.io/badge/Email-jw5194%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:jw5194@naver.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-dlwl224.github.io-222222?style=flat-square&logo=githubpages&logoColor=white)](https://dlwl224.github.io)

</div>

---

## 👩‍💻 About Me

- 🔓 **Offensive** — OWASP Top 10 취약점을 직접 구현하고 Burp Suite로 공격해 보며 **모의해킹 보고서**를 작성했습니다.
- 🔍 **Detection** — URL 특화 언어모델(URLBERT)을 파인튜닝해 **피싱 URL을 탐지**하고, 이를 QR 스캔·챗봇 서비스로 연결했습니다.
- 🔐 **Defensive Dev** — Spring Boot·Flask 백엔드에서 **JWT 인증, 환경변수 기반 비밀값 관리, 입력 검증**을 고민하며 개발합니다.

> "취약점을 찾는 눈으로 코드를 짜고, 개발자의 눈으로 취약점을 설명하는 사람"이 되는 것이 목표입니다.

---

## 🎯 Interests

`Web Penetration Testing` `Secure Coding` `Phishing / Malicious URL Detection` `AI for Security` `Authentication & Authorization`

---

## 📌 Featured Projects

### 🔓 [Vulnerable Web App & Penetration Test](https://github.com/dlwl224/sc_pro)
의도적으로 취약하게 만든 Node.js 웹앱에 직접 모의해킹을 수행하고 결과 보고서를 작성한 프로젝트

- **SQL Injection**(인증 우회) · **Stored XSS** · **IDOR** · **File Upload(Webshell)** 구현 및 공격 시나리오 검증
- Burp Suite 기반 공격 재현 → 원인 분석 → 대응 방안을 담은 **Pentest Report(PDF)** 작성
- `Node.js` `Express` `MySQL` `EJS` `Burp Suite`

### 🔍 [sQanAR — QR 피싱 탐지 서비스](https://github.com/dlwl224/final_sqanar)
QR 코드 속 URL을 분석해 피싱 여부를 판별하고, 챗봇으로 위험 근거를 설명해 주는 서비스

- QR 디코딩·OCR로 URL 추출 → **WHOIS·SSL 등 URL 특징 추출** + **URLBERT 모델**로 피싱 판별
- FAISS 기반 보안 지식 검색(RAG)과 LLM 에이전트로 **사용자 질의응답 챗봇** 구현
- **JWT 인증**, Redis 대화 메모리, AWS S3 모델 저장소 연동
- `Python` `Flask` `PyTorch` `Transformers` `FAISS` `Redis` `AWS S3`

### 🤖 [URLBERT Phishing Detection](https://github.com/dlwl224/urlbert)
URL 전용 사전학습 모델 URLBERT를 피싱 URL 분류 태스크에 파인튜닝

- URL 전용 토크나이저로 전처리 → 분류 헤드 추가 후 파인튜닝
- sQanAR 서비스의 핵심 탐지 모델로 활용
- `Python` `PyTorch` `Transformers`

### 🧳 [DDU-RU — 여행 동행자 매칭 플랫폼](https://github.com/ddu-ru/ddu-ru-backend) · 팀 프로젝트
- Spring Boot 백엔드, Docker 기반 배포, Flyway DB 마이그레이션
- `Java` `Spring Boot` `MySQL` `Docker`

### 💰 [FINDEPENDENCE — 청년 금융자립 AI 상담](https://github.com/FIN-Dependence/fin-backend) · 팀 프로젝트
- 로그인·회원가입 인증 구조, RAG(Chroma) 기반 금융 상담 챗봇
- API 키를 저장소에 올리지 않고 환경변수로 분리해 관리
- `Java 17` `Spring Boot` `React` `Chroma` `LLM`

---

## 🛠️ Tech Stack

**Security**

![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP%20Top%2010-000000?style=flat-square&logo=owasp&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**AI / Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**DevOps / Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🏅 Education & Certifications

<!-- TODO: 실제 이력으로 채우고, 해당 없는 줄은 삭제하세요. -->
| 기간 | 내용 |
| :--- | :--- |
| 2022.03 ~ | 덕성여자대학교 사이버보안전공 |
| YYYY.MM | (자격증) 예: 정보보안기사 / 정보처리기사 / 리눅스마스터 |
| YYYY.MM | (교육) 예: KISA·BoB 등 보안 교육 과정 |
| YYYY.MM | (대회·워게임) 예: CTF 참가, Dreamhack 랭크 |

---

<div align="center">

📫 보안 관련 이야기라면 언제든 편하게 연락 주세요!

</div>
