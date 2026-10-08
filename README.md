<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Security%20Portfolio&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Policy%20%C3%97%20Code%20%C3%97%20Automation&descAlignY=58&descSize=18&animation=fadeIn" alt="header" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2C5364&center=true&vCenter=true&width=600&lines=%EB%B3%B4%EC%95%88%EC%9D%84+%EA%B8%B0%EC%88%A0%EB%A1%9C+%ED%95%B4%EA%B2%B0%ED%95%A9%EB%8B%88%EB%8B%A4+%F0%9F%9B%A1%EF%B8%8F;Web+Pentest+%7C+Secure+Coding;URL-BERT+Phishing+Detection+99.72%25" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://mynote6336.tistory.com"><img src="https://img.shields.io/badge/Tech%20Blog-Tistory-000000?style=for-the-badge&logo=tistory&logoColor=white" /></a>
</p>

---

## 🙋 About Me

**공격을 이해하고, 위협을 탐지하고, 반복되는 위험을 구조로 해결합니다.**

- 🔓 취약한 웹 서버를 직접 구축·공격하고 **시큐어 코딩으로 조치**해 본 경험
- 🤖 URL-BERT를 직접 구현해 큐싱(QR 피싱) URL을 **정확도 99.72%** 로 탐지
- 🏆 SQanaR 프로젝트로 과학기술대학 학술제 **최우수상**
- 🔍 관심 분야: **정보보호 관리체계(ISMS-P)** · 웹 취약점 진단 · AI 기반 위협 탐지 · 보안 자동화

```mermaid
flowchart LR
    A["🔓 공격 이해<br/>Web Pentest · Secure Coding"] --> B["🤖 위협 탐지<br/>URL-BERT · Feature Engineering"]
    B --> C["🏢 관리체계<br/>Policy · Compliance · ISMS-P"]
    C --> D["⚙️ 자동화<br/>Security Workflow"]
    D -. 반복 위험을 구조로 해결 .-> A
```

---

## 🛠️ Tech Stack

<div align="center">

**🔐 Security**<br/>
<img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
<img src="https://img.shields.io/badge/OWASP%20ZAP-000000?style=for-the-badge&logo=owasp&logoColor=white" />
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />

**💻 Backend**<br/>
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />

**🤖 AI**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />

**☁️ Infra & DB**<br/>
<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />

</div>

---

## 📌 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔍 [SQanaR](https://github.com/dlwl224/final_sqanar)
**URL-BERT 기반 큐싱(QR 피싱) 탐지 앱**<br/>
`2025.03 ~ 2025.11` · 팀 · AI 모델·백엔드

- URL-BERT 직접 구현, URL+Header 10만 건 파인튜닝
- **Accuracy / F1 99.72%** (XGBoost 95.99%, BERT 94.03%)
- WHOIS·TLD·Subdomain 등 30+ Feature 파이프라인
- 블랙리스트에 없는 **제로데이 URL** 탐지
- LangChain + FAISS 보안 지식 챗봇
- 🏆 과학기술대학 학술제 **최우수상**

`PyTorch` `Flask` `LangChain` `FAISS` `Redis`

</td>
<td width="50%" valign="top">

### 🔓 [Web Pentest & Secure Coding](https://github.com/dlwl224/sc_pro)
**취약한 웹앱 구축 → 모의해킹 → 조치**<br/>
`2025.11` · 개인 · 기여도 100%

| 취약점 | 조치 |
| :--- | :--- |
| SQL Injection | Prepared Statement |
| Stored XSS | HTML Entity Encoding |
| IDOR | 세션 기반 소유권 검증 |
| File Upload | 화이트리스트 · 파일명 난수화 |

- AWS EC2 배포, Security Group 접근 제한

`Node.js` `MySQL` `Burp Suite` `AWS EC2`

</td>
</tr>
</table>

<details>
<summary><b>🗺️ SQanaR 시스템 구성도 보기</b></summary>
<br/>

```mermaid
flowchart LR
    U["📱 QR 스캔<br/>React Native"] --> API["Flask REST API"]
    API --> F["Feature 추출<br/>WHOIS · TLD · Subdomain 등 30+"]
    API --> M["URL-BERT<br/>Fine-tuned"]
    F --> M
    M --> DB[("MySQL")]
    API --> BOT["LangChain 챗봇"]
    BOT --> V[("FAISS<br/>보안 지식")]
    BOT --> R[("Redis<br/>대화 컨텍스트")]
    BOT --> G["Gemini API"]
```

</details>

### 🌲 [구독숲](https://github.com/SubscriptionForest) — 인증 보안 구현
`2025.07 ~ 2025.08` · 팀 · Full-stack
- Spring Security + **JWT** 인증, 로그아웃 시 **토큰 블랙리스트** 처리로 탈취 토큰 재사용 차단

`Spring Boot` `Spring Security` `JWT`

---

## 📜 Certifications

| 자격증 | 취득 |
| :--- | :--- |
| ✅ 정보처리기사 | 2025.09 |
| ✅ 리눅스마스터 2급 | 2025.07 |
| ✅ SQLD | 2025.12 |

---

## 📚 Security Activities

- 🛡️ **보안동아리 '백도어'** — 제로트러스트 아키텍처 · 디지털 포렌식 스터디 및 세미나 발표
- 🕸️ **웹해킹 실습** — OWASP Top 10 중심 취약점 분석, DVWA 필터링 우회 실습

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=dlwl224&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dlwl224&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=120&section=footer" alt="footer" />
</p>
