<div align="center">
  <img src="./vf-labs-banner.svg" alt="VF-Labs — Building Intelligent Systems" width="100%" />
</div>

<br />

## `>_ whoami`

**Victor Fialho** · Anápolis, Brazil 🇧🇷
AI Engineering @ UniEVANGÉLICA
Founder @ AoTomate Sistemas · Automation Analyst @ DataCrazy CRM

I build AI agents, automation pipelines, and full-stack systems for real operations. My work spans architecture, implementation, deployment, monitoring, and production debugging — from multi-tenant WhatsApp agents to retrieval systems with evaluation suites.

```text
languages   PT (native) · EN (fluent) · ES (advanced)
off-duty    Jiu-Jitsu · philosophy of mind · history of mathematics
```

---

## `>_ Featured projects`

### SIMPA — Academic Monitoring & Risk Prediction Platform

![Status](https://img.shields.io/badge/status-in%20progress-F5A623?style=flat-square) · Integrator project · AI Engineering @ UniEVANGÉLICA

Records grades and attendance, computes statistical indicators, and classifies each student's academic risk with an explanation of why — all exposed through a secure REST API.

**Stack:** FastAPI · React + Vite + TypeScript · PostgreSQL · RabbitMQ · nginx · Docker Compose · pytest

- Service-oriented architecture: `auth`, `academico` and `analitico` services, each with its own database, behind an nginx gateway
- Event-driven risk recalculation: grade and attendance changes publish to RabbitMQ and a worker updates the risk history
- JWT RS256 authentication, regression-based prediction, recommendations, and PDF/Excel reports
- Requirements traceability (SRS, ERD, decision log) linking every feature to its requirement

**Source:** [github.com/Victorfiallho/simpa](https://github.com/Victorfiallho/simpa)

### Racha — Split the Restaurant Bill at the Table

![Status](https://img.shields.io/badge/status-design%20phase-8A8F98?style=flat-square) · Product concept · System design first

Customers tap an NFC tag or scan a QR code on the table, mark what they ordered (or split evenly), and pay their share via Pix. The table closes itself once everything is paid.

**Stack (planned):** OpenAPI · JSON Schema · Architecture Decision Records

- Ingestion layer that normalizes bills from an open API, POS connectors, a print-capture agent, or a manual panel into one canonical format
- Full requirements, use cases with acceptance criteria, domain model with state machines, and ADRs
- Contracts defined up front: OpenAPI for ingestion and JSON Schema for the canonical bill and events
- Includes a 3D-printed table piece spec combining QR code and NFC

**Source:** [github.com/Victorfiallho/Racha](https://github.com/Victorfiallho/Racha)

### RAG Agent — Retrieval-Augmented Q&A with Evaluation

![Status](https://img.shields.io/badge/status-in%20progress-F5A623?style=flat-square) · Production-shaped retrieval system

A document Q&A pipeline covering ingestion, embeddings, retrieval, grounded generation, and systematic evaluation. The evaluation harness measures both retrieval quality and answer faithfulness.

**Stack:** Python · LangChain · pgvector / Supabase · Claude API · Custom evaluation harness

- End-to-end ingestion and semantic retrieval pipeline
- Grounded responses backed by retrieved context
- Retrieval and faithfulness metrics designed for repeatable evaluation
- Built around production concerns rather than a tutorial-only implementation

**Source:** Private during active development · Technical write-up available on request

### Orçador — Pricing & Scope Engine

![Status](https://img.shields.io/badge/status-in%20progress-F5A623?style=flat-square) · Internal product for AoTomate Sistemas

Turns a client brief into structured pricing and scope output using service-tier rules and LLM-generated JSON. It is also my learning-by-building vehicle for understanding every layer of a full-stack product.

**Stack:** JavaScript · React / Next.js · Supabase / SQL · Claude API · Vercel

- Converts unstructured client requirements into predictable JSON output
- Applies service-tier and pricing rules to generate proposals consistently
- Covers HTTP fundamentals, data modeling, backend integration, frontend development, and deployment

**Source:** Private during active development · Technical write-up available on request

---

## `>_ Current focus`

```text
[NOW ]  RAG systems       embeddings · retrieval · evaluation · faithfulness
[NOW ]  Agentic AI        orchestration · tool use · reliable workflows
[NOW ]  Full-stack        JavaScript · SQL · React/Next.js · deployment
[NOW ]  AI Engineering    calculus · linear algebra · computer science
[NEXT]  Cloud             AWS AI Practitioner certification track
```

---

## `>_ Tech stack`

**AI & Automation**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Llama](https://img.shields.io/badge/Llama%203.3-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Evolution API](https://img.shields.io/badge/Evolution%20API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)

**Application Development**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)

**Data & Infrastructure**

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)

---

## `>_ GitHub activity`

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Victorfiallho&show_icons=true&theme=dark&hide_border=true&title_color=3FAE54&icon_color=3FAE54" alt="Victor's GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Victorfiallho&layout=compact&theme=dark&hide_border=true&title_color=3FAE54" alt="Victor's most used languages" height="165" />
</div>

---

## `>_ Let's build something useful`

I'm open to AI engineering opportunities, technical collaborations, and conversations about applied AI, automation, and production systems.

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-3FAE54?style=for-the-badge&logo=googlechrome&logoColor=white)](https://victorfiallho.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-fialho-9140b23b5/)

<sub>DATA · MODELS · SYSTEMS · IDEAS · CODE</sub>

</div>
