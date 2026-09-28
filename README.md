<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=CC0033&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Hassan;I+build+AtlasRU+for+Rutgers+students;full-stack+%2B+applied+AI;looking+for+SWE+%2F+AI+internships" alt="Hi, I'm Hassan" />

CS @ Rutgers · Prev. AI Fellow @ NJ Innovation Authority · HackRU R&D · IBM Z Student Ambassador

<p><a href="https://atlasru.com"><img src="https://img.shields.io/badge/AtlasRU-live-CC0033?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>&nbsp;<a href="https://hassan-portfolio-mhassanibrahim123-3130s-projects.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>&nbsp;<a href="https://www.linkedin.com/in/hassan1brahim"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;<a href="mailto:m.hassan.ibrahim.123@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a></p>

</div>

---

## AtlasRU

<a href="https://atlasru.com"><img src="assets/atlasru-courses.webp" alt="AtlasRU course search with open seats, SIRS and RateMyProfessor ratings, and prereq status" /></a>

Planning a Rutgers semester means bouncing between WebReg, Degree Navigator, SIRS and RateMyProfessors. [AtlasRU](https://atlasru.com) puts them in one place: live seat counts, ratings, prereqs, degree audits, a schedule generator, and an AI advisor that looks up your audit and the catalog before it answers.

<div align="center">

| **300+** | **2,000+** | **1,800+** |
|:--:|:--:|:--:|
| students | course monitors | advisor chats |

</div>

<details>
<summary><b>How it's built</b></summary>
<br>

```mermaid
flowchart LR
    U([Student]) --> FE[Next.js + React<br/>Vercel]
    FE --> API[NestJS + Prisma<br/>Railway]
    API --> DB[(PostgreSQL<br/>+ pgvector)]
    API --> LLM{{AI advisor<br/>tool calling}}
    LLM -->|audit, catalog,<br/>schedule tools| API
    P[Python + Node<br/>pipelines] --> DB
    SRC[WebReg · Degree Navigator<br/>SIRS · RateMyProfessors] --> P
```

Things I spent way too long on:

- getting the audits to agree with Degree Navigator, down to the weird edge cases
- stopping the advisor from recommending courses you can't take yet. Prompting didn't fix it, so the check lives in code now
- turning bugs real students hit into replay tests so they stay fixed

The code is private for now. Happy to walk through it.

</details>

---

## On GitHub

| | | |
|:--|:--|:--|
| [**eufy-controller-bridge**](https://github.com/hassan1brahim/eufy-controller-bridge) | drive a robot vacuum with a PS5 controller | Python · MQTT |
| [**HackRU**](https://github.com/HackRU/frontendv2/pulls?q=is%3Apr+author%3Ahassan1brahim+is%3Amerged) | Rebuilt the Fall 2026 landing page for 600+ hackers (yes, including the mushroom cursor), then went into the backend and [fixed bugs](https://github.com/HackRU/HackRU-Backend/pulls?q=is%3Apr+author%3Ahassan1brahim+is%3Amerged) | Next.js · AWS Lambda |
| [**Job Ops**](https://github.com/hassan1brahim/codex-job-ops-template) | my internship search pipeline | Python · LaTeX |
| [**ticket-classification-gh-action**](https://github.com/newjersey/ticket-classification-gh-action) | ticket classifier I built at NJIA | Python · ML |

Experience, more projects and my resume are on my **[portfolio](https://hassan-portfolio-mhassanibrahim123-3130s-projects.vercel.app)**.

---

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,python,java,c,cpp,postgres,react,nextjs,nestjs,nodejs,tailwind,pytorch,sklearn,flask,django,aws,githubactions,linux&perline=9" alt="Stack" />
</p>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hassan1brahim/hassan1brahim/output/snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/hassan1brahim/hassan1brahim/output/snake.svg" alt="Contribution snake" />
</picture>

</div>
