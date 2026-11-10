<div align="center">
  <img src="./assets/vf-labs-banner.svg" alt="VF-Labs — Building Intelligent Systems" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=1100&color=3FAE54&center=true&vCenter=true&width=750&height=45&lines=%3E+Booting+VF-Labs...;%3E+Building+AI+agents+for+real+operations.;%3E+Retrieval.+Evaluation.+Faithfulness.;%3E+Find+the+problem.+Build+the+fix.+Ship+it." alt="Typing animation"/>

<br>

<img src="https://img.shields.io/badge/FOCUS-AI%20ENGINEERING%20%26%20AUTOMATION-3FAE54?style=for-the-badge&labelColor=0D1117" alt="Focus"/>
<img src="https://img.shields.io/badge/NOW-RAG%20%2B%20AGENTS-F5A623?style=for-the-badge&labelColor=0D1117" alt="Now"/>
<img src="https://img.shields.io/badge/STATUS-BUILDING-3FAE54?style=for-the-badge&labelColor=0D1117" alt="Status"/>

<br><br>

<a href="https://github.com/Victorfiallho?tab=followers">
  <img src="https://img.shields.io/github/followers/Victorfiallho?style=flat-square&logo=github&label=Followers&labelColor=0D1117&color=3FAE54" alt="Followers"/>
</a>
<img src="https://komarev.com/ghpvc/?username=Victorfiallho&label=Profile+Views&color=3FAE54&style=flat-square" alt="Profile views"/>
<a href="https://github.com/Victorfiallho?tab=repositories">
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FVictorfiallho&query=%24.public_repos&label=Repositories&style=flat-square&logo=github&logoColor=white&labelColor=0D1117&color=3FAE54" alt="Public repositories"/>
</a>

</div>

---

## `01`  `>_ whoami`

```python
class VictorFialho:
    location = "Anápolis, Brazil 🇧🇷"
    roles = [
        "AI Engineering @ UniEVANGÉLICA",
        "Founder @ AoTomate Sistemas",
        "Automation Analyst @ DataCrazy CRM",
    ]
    languages = {"PT": "native", "EN": "fluent", "ES": "advanced"}
    off_duty  = ["Jiu-Jitsu", "philosophy of mind", "history of mathematics"]
```

I build AI agents, automation pipelines, and full-stack systems for real operations. My work spans architecture, implementation, deployment, monitoring, and production debugging — from multi-tenant WhatsApp agents to retrieval systems with evaluation suites.

---

## `02`  `>_ Featured projects`

<table>
<tr>
<td width="50%" valign="top">

### 🎓 SIMPA
**Academic Monitoring & Risk Prediction Platform**

![Status](https://img.shields.io/badge/status-in%20progress-F5A623?style=flat-square&labelColor=0D1117) ![Type](https://img.shields.io/badge/integrator%20project-0D1117?style=flat-square)

Records grades and attendance, computes statistical indicators, and classifies each student's academic risk with an explanation of why — all exposed through a secure REST API.

- Services `auth`, `academico` and `analitico`, each with its own DB, behind an nginx gateway
- Event-driven risk recalculation via RabbitMQ worker
- JWT RS256, regression-based prediction, PDF/Excel reports
- Requirements traceability (SRS, ERD, decision log)

![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=009688)
![React](https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-0D1117?style=flat-square&logo=rabbitmq&logoColor=FF6600)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED)

**[→ Source](https://github.com/Victorfiallho/simpa)**

</td>
<td width="50%" valign="top">

### 🍽️ Racha
**Split the Restaurant Bill at the Table**

![Status](https://img.shields.io/badge/status-design%20phase-8A8F98?style=flat-square&labelColor=0D1117) ![Type](https://img.shields.io/badge/system%20design%20first-0D1117?style=flat-square)

Customers tap an NFC tag or scan a QR code on the table, mark what they ordered (or split evenly), and pay their share via Pix. The table closes itself once everything is paid.

- Ingestion layer normalizing bills from API, POS connectors, print capture or manual panel
- Requirements, use cases, domain model with state machines, and ADRs
- Contracts up front: OpenAPI + JSON Schema
- 3D-printed table piece combining QR code and NFC

![OpenAPI](https://img.shields.io/badge/OpenAPI-0D1117?style=flat-square&logo=openapiinitiative&logoColor=6BA539)
![JSON Schema](https://img.shields.io/badge/JSON%20Schema-0D1117?style=flat-square&logo=json&logoColor=white)
![ADRs](https://img.shields.io/badge/ADRs-0D1117?style=flat-square)

**[→ Source](https://github.com/Victorfiallho/Racha)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔎 RAG Agent
**Retrieval-Augmented Q&A with Evaluation**

![Status](https://img.shields.io/badge/status-in%20progress-F5A623?style=flat-square&labelColor=0D1117) ![Type](https://img.shields.io/badge/production--shaped-0D1117?style=flat-square)

A document Q&A pipeline covering ingestion, embeddings, retrieval, grounded generation, and systematic evaluation of retrieval quality and answer faithfulness.

- End-to-end ingestion and semantic retrieval
- Grounded responses backed by retrieved context
- Repeatable retrieval & faithfulness metrics

![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3776AB)
![LangChain](https://img.shields.io/badge/LangChain-0D1117?style=flat-square&logo=langchain&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![Claude](https://img.shields.io/badge/Claude%20API-0D1117?style=flat-square&logo=anthropic&logoColor=D97757)

🔒 *Private during active development · write-up on request*

</td>
<td width="50%" valign="top">

### 💰 Orçador
**Pricing & Scope Engine**

![Status](https://img.shields.io/badge/status-in%20progress-F5A623?style=flat-square&labelColor=0D1117) ![Type](https://img.shields.io/badge/AoTomate%20internal-0D1117?style=flat-square)

Turns a client brief into structured pricing and scope output using service-tier rules and LLM-generated JSON — and my learning-by-building vehicle for every layer of a full-stack product.

- Unstructured requirements → predictable JSON
- Consistent proposals from service-tier and pricing rules
- HTTP, data modeling, backend, frontend and deployment

![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-0D1117?style=flat-square&logo=supabase&logoColor=3FCF8E)
![Claude](https://img.shields.io/badge/Claude%20API-0D1117?style=flat-square&logo=anthropic&logoColor=D97757)
![Vercel](https://img.shields.io/badge/Vercel-0D1117?style=flat-square&logo=vercel&logoColor=white)

🔒 *Private during active development · write-up on request*

</td>
</tr>
</table>

<div align="center">

**Also on GitHub:** [LeetCode Solutions](https://github.com/Victorfiallho/LeetCode-Solutions) — Python & SQL, organized by topic · [Portfolio](https://github.com/Victorfiallho/victorfiallho.github.io) — projects & interactive demos

<a href="https://github.com/Victorfiallho?tab=repositories">
  <img src="https://img.shields.io/badge/EXPLORE_ALL_PROJECTS-3FAE54?style=for-the-badge&logo=github&logoColor=white" alt="Explore all projects"/>
</a>

</div>

---

## `03`  `>_ Current focus`

```bash
victor@vf-labs:~$ ./roadmap --active

[NOW ]  RAG systems       embeddings · retrieval · evaluation · faithfulness
[NOW ]  Agentic AI        orchestration · tool use · reliable workflows
[NOW ]  Full-stack        JavaScript · SQL · React/Next.js · deployment
[NOW ]  AI Engineering    calculus · linear algebra · computer science
[NOW ]  Security          offensive security · Linux · web app pentesting
[NEXT]  Cloud             AWS AI Practitioner certification track
[NEXT]  Pentest           SYCP — Solyd Certified Pentester

victor@vf-labs:~$
```

---

## `04`  `>_ Certifications & security`

<div align="center">

<img src="https://img.shields.io/badge/SOLYD-Linux%20%26%20Shell%20Script%20for%20Pentesters-3FAE54?style=for-the-badge&labelColor=0D1117" alt="Solyd Linux"/>
<img src="https://img.shields.io/badge/SOLYD-Python%20OOP%20%26%20Automation-3FAE54?style=for-the-badge&labelColor=0D1117" alt="Solyd Python"/>
<img src="https://img.shields.io/badge/SYCP-in%20progress-F5A623?style=for-the-badge&labelColor=0D1117" alt="SYCP"/>

</div>

```bash
victor@vf-labs:~$ cat certs.txt

[✔] Dominando o Linux e Shell Script para Pentesters   Solyd Offensive Security   16h     Aug 2026
[✔] Python Orientado a Objetos e Automação             Solyd Offensive Security   46h40   Sep 2026
[ ] SYCP — Solyd Certified Pentester                   Solyd Offensive Security   next

victor@vf-labs:~$ ls ~/labs
owasp-juice-shop/   # SQLi · XSS · hash cracking (hashcat) · recon (nmap)
tailscale-lab/      # private VPN lab for security practice
```

---

## `05`  `>_ Tech stack`

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=py,js,ts,java,bash&theme=dark" alt="Languages"/>

**Application Development**

<img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,fastapi&theme=dark" alt="Application development"/>

**Data & Infrastructure**

<img src="https://skillicons.dev/icons?i=supabase,postgres,rabbitmq,docker,nginx,vercel,linux,git&theme=dark" alt="Data and infrastructure"/>

**AI & Automation**

<img src="https://img.shields.io/badge/n8n-0D1117?style=for-the-badge&logo=n8n&logoColor=EA4B71" alt="n8n"/>
<img src="https://img.shields.io/badge/Claude%20API-0D1117?style=for-the-badge&logo=anthropic&logoColor=D97757" alt="Claude API"/>
<img src="https://img.shields.io/badge/LangChain-0D1117?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/Groq-0D1117?style=for-the-badge&logoColor=F55036" alt="Groq"/>
<img src="https://img.shields.io/badge/Llama%203.3-0D1117?style=for-the-badge&logo=meta&logoColor=0467DF" alt="Llama 3.3"/>
<img src="https://img.shields.io/badge/Evolution%20API-0D1117?style=for-the-badge&logo=whatsapp&logoColor=25D366" alt="Evolution API"/>
<img src="https://img.shields.io/badge/pgvector-0D1117?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="pgvector"/>
<img src="https://img.shields.io/badge/Oracle%20Cloud-0D1117?style=for-the-badge&logo=oracle&logoColor=F80000" alt="Oracle Cloud"/>

**Security**

<img src="https://img.shields.io/badge/Nmap-0D1117?style=for-the-badge&logoColor=white" alt="Nmap"/>
<img src="https://img.shields.io/badge/Hashcat-0D1117?style=for-the-badge&logoColor=white" alt="Hashcat"/>
<img src="https://img.shields.io/badge/OWASP-0D1117?style=for-the-badge&logo=owasp&logoColor=white" alt="OWASP"/>
<img src="https://img.shields.io/badge/Tailscale-0D1117?style=for-the-badge&logo=tailscale&logoColor=white" alt="Tailscale"/>

</div>

---

## `06`  `>_ GitHub activity`

<div align="center">

<img src="https://github-readme-stats-fast.vercel.app/api?username=Victorfiallho&show_icons=true&theme=github_dark&hide_border=true&bg_color=00000000&title_color=3FAE54&icon_color=3FAE54" height="165" alt="GitHub stats"/>
<img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Victorfiallho&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000&title_color=3FAE54" height="165" alt="Most used languages"/>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Victorfiallho/Victorfiallho/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Victorfiallho/Victorfiallho/output/snake.svg"/>
  <img src="https://raw.githubusercontent.com/Victorfiallho/Victorfiallho/output/snake.svg" width="100%" alt="Contribution snake"/>
</picture>

</div>

---

## `07`  `>_ Let's build something useful`

I'm open to AI engineering opportunities, technical collaborations, and conversations about applied AI, automation, and production systems.

<div align="center">

<a href="https://victorfiallho.github.io">
  <img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=googlechrome&logoColor=3FAE54" alt="Portfolio"/>
</a>
<a href="https://www.linkedin.com/in/victor-fialho-9140b23b5/">
  <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"/>
</a>
<a href="https://github.com/Victorfiallho">
  <img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<br><br>

<sub>DATA · MODELS · SYSTEMS · IDEAS · CODE</sub>

</div>
