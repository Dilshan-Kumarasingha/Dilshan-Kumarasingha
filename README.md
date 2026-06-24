<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0B0F,50:1a1a2e,100:C8A96E&height=200&section=header&text=Dilshan%20Kumarasingha&fontSize=40&fontColor=C8A96E&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%E2%80%94%20C%23%20.NET%20%7C%20React%20%7C%20QA%20Automation&descSize=16&descAlignY=58&descColor=9090A0" />

</div>

<br/>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=DM+Mono&size=18&duration=3000&pause=800&color=C8A96E&center=true&vCenter=true&width=750&lines=Full-Stack+Developer+%E2%80%94+C%23+.NET+%26+React;Building+Real-Time+Systems+%26+Business-Rule+Engines;REST+APIs+%7C+JWT+Auth+%7C+PostgreSQL+%7C+SignalR;BSc+(Hons)+IT+%E2%80%94+SLIIT+%282025%29;Open+to+Software+Engineer+Roles" />
</div>

<br/>

<div align="center">

[![Open to Work](https://img.shields.io/badge/%E2%97%8F%20Open%20to%20Work-C8A96E?style=flat-square&labelColor=0B0B0F&color=C8A96E&logoColor=white)](https://www.linkedin.com/in/dilshan-kumarasingha/)&nbsp;&nbsp;
[![SLIIT](https://img.shields.io/badge/BSc%20IT-SLIIT%20%272025-6366F1?style=flat-square&labelColor=0B0B0F)](https://www.sliit.lk)&nbsp;&nbsp;
[![Location](https://img.shields.io/badge/Colombo%2C%20Sri%20Lanka-%F0%9F%87%B1%F0%9F%87%B0-9090A0?style=flat-square&labelColor=0B0B0F)](https://github.com/Dilshan-Kumarasingha)&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-C8A96E?style=flat-square&labelColor=0B0B0F&logo=linkedin)](https://www.linkedin.com/in/dilshan-kumarasingha/)

</div>

---

<br/>

## 〔 About Me 〕

```yaml
# dilshan.kumarasingha.yaml

name:         Dilshan Kumarasingha
title:        Software Engineer (Full-Stack)
location:     Colombo, Sri Lanka 🇱🇰
education:    BSc (Hons) Information Technology — SLIIT (2021–2025)

experience:
  - role:     Software Developer Intern
    at:       Bank of Ceylon
    period:   2023 – 2024
    focus:    Web & mobile app dev, SQL Server/MySQL, UAT, SDLC

  - role:     IT Support & System Operations / Lab Demonstrator
    at:       Lyceum International Schools
    period:   2026 – Present
    focus:    IMS deployment, IT ops, network/system admin

primary_stack:
  backend:    C# · ASP.NET Core Web API · Entity Framework Core
  frontend:   React · TypeScript · Vite
  database:   PostgreSQL
  realtime:   SignalR
  auth:       JWT Bearer · PBKDF2 password hashing
  jobs:       Hangfire (recurring background processing)
  testing:    NUnit · RestSharp · Dapper

secondary_stack:
  backend:    Java · Spring Boot · Spring Security
  frontend:   JavaScript · React
  testing:    Selenium · TestNG · RestAssured

status:       Open to full-time Software Engineer roles ✓
```

<br/>

> **Primary focus:** building production-grade systems on **C# / .NET** — REST APIs, JWT auth, real-time features with SignalR, and time-based background processing with Hangfire — backed by **PostgreSQL** and a **React + TypeScript** frontend. Every project below ships with its own professional QA automation suite.

<br/>

---

## 〔 Tech Stack 〕

**Primary — C# / .NET**

<p>
  <img src="https://skillicons.dev/icons?i=cs,dotnet,react,ts,postgres&theme=dark" />
</p>

**Secondary**

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,js&theme=dark" />
</p>

**Testing & DevOps**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,postman,vscode,visualstudio,idea&theme=dark" />
</p>

<details>
<summary><b>Full stack breakdown</b></summary>

<br/>

| Layer | Technologies |
|---|---|
| **Backend (primary)** | C# · ASP.NET Core Web API (.NET) · Entity Framework Core |
| **Backend (secondary)** | Java · Spring Boot · Spring Security |
| **Frontend** | React · TypeScript · Vite · JavaScript · Tailwind CSS |
| **Database** | PostgreSQL |
| **Real-time & Jobs** | SignalR · Hangfire |
| **Auth** | JWT Bearer tokens · PBKDF2 password hashing |
| **QA & Testing** | NUnit · RestSharp · Dapper · Selenium WebDriver · TestNG · RestAssured · Allure Reports |
| **DevOps** | Docker · GitHub Actions · CI/CD · Git |
| **Tools** | Visual Studio · IntelliJ IDEA · VS Code · Postman |

</details>

<br/>

---

## 〔 Featured Projects 〕

### 🔄 Flowspace — Async Standup & Decision Platform
`ASP.NET Core (.NET)` `React + TypeScript` `PostgreSQL` `SignalR` `JWT` `NUnit`

An async team-standup and decision-logging platform for software teams — solves two real problems: meetings that waste time, and decisions that get lost in chat history.

- **Live async standups** — SignalR-powered real-time feed, blockers flagged instantly, one-post-per-day rule enforced server-side
- **Decision log with a real state machine** — Draft → Open → Decided → Superseded, forward-only transitions, team voting, threaded comments
- **Role-based workspaces** — Lead/Member permission boundaries enforced at the service layer, time-limited invite codes
- **Full QA automation suite** — RestSharp API tests, Selenium UI tests (Page Object Model), Dapper-based DB validation, Allure reporting in CI

[![View on GitHub](https://img.shields.io/badge/View%20on%20GitHub-C8A96E?style=flat-square&logo=github&logoColor=white&labelColor=0B0B0F)](https://github.com/Dilshan-Kumarasingha/flowspace)

<br/>

### 🎫 HelpDeskHQ — IT & Facilities Helpdesk with SLA Automation Engine
`ASP.NET Core (.NET)` `React + TypeScript + Vite` `PostgreSQL` `Hangfire` `NUnit`

An internal helpdesk system where the core feature isn't CRUD — it's a **rules engine that acts on data over time without a human touching it**, the same category of problem found in Jira Service Management or Zendesk.

- **SLA escalation engine** — configurable response/resolution targets per category × priority; a recurring Hangfire job scans open tickets, flags at-risk tickets, and auto-escalates breached ones to a Team Lead
- **Enforced ticket state machine** — every status transition validated server-side; no skipping straight from New to Closed
- **JWT auth with PBKDF2 hashing**, role-based access across Employee / Agent / Team Lead / Admin
- **QA highlight** — tests seed backdated tickets via direct SQL (Dapper) and invoke the escalation job's logic directly, validating time-dependent background business logic — a meaningfully different testing skill than standard request/response API testing

[![View on GitHub](https://img.shields.io/badge/View%20on%20GitHub-C8A96E?style=flat-square&logo=github&logoColor=white&labelColor=0B0B0F)](https://github.com/Dilshan-Kumarasingha/helpdeskhq)

<br/>

### 🛒 ShopQA — E-Commerce + QA Automation *(secondary stack: Java / Spring Boot)*
`React` `Spring Boot` `PostgreSQL` `Selenium` `TestNG` `RestAssured` `GitHub Actions` `Allure`

A full-stack e-commerce app paired with a professional QA automation framework — built to demonstrate the same testing discipline applied to a Java/Spring Boot backend instead of .NET.

- Full customer flow — register, browse, cart, checkout, order history; admin product management
- JWT-secured Spring Boot REST API with Spring Security
- UI testing via Selenium + Page Object Model, API testing via RestAssured, DB validation via JDBC
- Allure reporting integrated into a GitHub Actions CI pipeline

[![View on GitHub](https://img.shields.io/badge/View%20on%20GitHub-6366F1?style=flat-square&logo=github&logoColor=white&labelColor=0B0B0F)](https://github.com/Dilshan-Kumarasingha/shopqa-ecommerce)

<br/>

---

## 〔 Experience 〕

<details open>
<summary><b>🖥️ &nbsp; IT Support & System Operations — Lyceum International Schools &nbsp; <code>2026 – Present</code></b></summary>
<br/>

> Managing IT infrastructure and system operations across school labs — while also developing the tools used internally.

- Deployed and configured the Institute Management System (IMS) across the full lab network
- Hardware, software, and network troubleshooting to ensure uninterrupted operations
- Proactive system monitoring for uptime and stability across multiple workstations

<br/>
</details>

<details open>
<summary><b>💼 &nbsp; Software Developer Intern — Bank of Ceylon &nbsp; <code>2023 – 2024</code></b></summary>
<br/>

> Contributed to real-world software development inside a regulated enterprise banking environment.

- Web and mobile application development (backend APIs, SQL Server/MySQL integration)
- Participated in full SDLC phases: development → testing → UAT → deployment
- Collaborated with senior developers and QA teams on security-compliant features
- End-to-end system testing and defect tracking

<br/>
</details>

<br/>

---

## 〔 Certifications 〕

<div align="center">

| Certification | Issuer | Year |
|---|---|---|
| ☁️ AWS Amazon Q Developer Fundamentals | Amazon Web Services | 2025 |
| 🐳 LFS144: Introduction to Istio | Linux Foundation | 2026 |
| 🐍 Python Essentials 1 | Cisco | 2026 |
| 🔬 API Fundamentals Student Expert | Postman | 2025 |
| 💻 Foundational C# with Microsoft | freeCodeCamp × Microsoft | 2025 |
| 🤖 Career Essentials in Generative AI | Microsoft | 2024 |
| 💼 Career Essentials in Software Development | Microsoft | 2024 |
| 🔐 Introduction to Cybersecurity | Cisco | 2024 |

</div>

<br/>

---

## 〔 GitHub Stats 〕

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Dilshan-Kumarasingha&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&border_radius=12&title_color=C8A96E&icon_color=6366F1&text_color=9090A0&bg_color=0B0B0F" />
&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dilshan-Kumarasingha&layout=compact&theme=tokyonight&hide_border=true&border_radius=12&title_color=C8A96E&text_color=9090A0&bg_color=0B0B0F" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Dilshan-Kumarasingha&theme=tokyonight&hide_border=true&border_radius=12&ring=C8A96E&fire=6366F1&currStreakLabel=C8A96E&background=0B0B0F&sideLabels=9090A0&dates=5A5550" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Dilshan-Kumarasingha&bg_color=0B0B0F&color=C8A96E&line=6366F1&point=F472B6&area=true&hide_border=true&radius=8" />

</div>

<br/>

---

## 〔 Let's Connect 〕

<div align="center">

I'm actively looking for **Software Engineer**, **Backend (.NET)**, and **Full-Stack** roles in Sri Lanka or remotely.<br/>
If you have an opportunity or just want to connect — reach out anytime.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-6366F1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dilshan-kumarasingha/)&nbsp;&nbsp;
[![Email](https://img.shields.io/badge/Email-F472B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dilshan.jkumarasingha@gmail.com)&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-9090A0?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Dilshan-Kumarasingha)

</div>

<br/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C8A96E,50:6366F1,100:0B0B0F&height=130&section=footer&animation=fadeIn" />

</div>
