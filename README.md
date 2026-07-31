<div align="center">

<img src="./assets/vf-labs-banner.svg" alt="VF-Labs — Building Intelligent Systems" width="100%" />

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-3FAE54?style=for-the-badge&logo=githubpages&logoColor=white)](https://victorfiallho.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-3FAE54?style=for-the-badge&logo=linkedin&logoColor=white)](https://br.linkedin.com/in/victor-fialho-9140b23b5)
[![LeetCode](https://img.shields.io/badge/LeetCode-3FAE54?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/VictorFialho)

</div>

## `>_` whoami

```
Victor Fialho — 20 · Anápolis, Brazil 🇧🇷
AI Engineering @ UniEVANGÉLICA
Founder @ AoTomate Sistemas · Automation Analyst @ DataCrazy CRM

I don't just study automation — I build it, ship it,
and debug it in production for real clients.

languages : PT (native) · EN (fluent) · ES (advanced)
off_duty  : Jiu-Jitsu · philosophy of mind · history of mathematics
```

## `>_` What I'm building right now

### RAG Agent — Retrieval-Augmented Q&A with Eval Suite

Current focus: a production-shaped RAG agent — not a tutorial. Document ingestion → embeddings → retrieval → grounded generation, with a proper evaluation harness measuring retrieval quality and answer faithfulness. Built to be the real thing employers look for, not a toy.

**Stack:** Python · LangChain · pgvector (Supabase) · Claude API · custom eval harness (retrieval + faithfulness metrics)

- **Why it matters:** RAG + eval is the exact stack that shows up in every AI engineering role — the difference between "used an LLM" and "engineered a retrieval system"
- **Code:** private while in active development · writeup available on request

`STATUS: ● IN PROGRESS`

### Orçador — AoTomate Pricing & Scope Engine

The pricing and scope-automation system behind AoTomate — built from the ground up as I learn the full stack end to end. Takes a client brief, applies the service-tier logic, and produces structured pricing/scope output. My learning-by-building vehicle: every layer written to be understood, not copied.

**Stack:** JavaScript · Supabase (SQL) · Claude API (JSON output) · React / Next.js · deployment

- **What I learned:** HTTP fundamentals, backend + SQL data modeling, structured JSON output from LLMs, React frontend, and shipping to deploy — each concept introduced only when the project demanded it
- **Code:** [github.com/Victorfiallho/orcador](https://github.com/Victorfiallho/orcador)

`STATUS: ● IN PROGRESS`

### Hera Remoto — Multi-Tenant WhatsApp AI Agent

Flagship AoTomate system: an AI customer service agent built for a remote secretarial company, **live in production**. End-to-end ownership — architecture, deployment, monitoring, and production debugging.

**Stack:** N8N · Evolution API · Supabase · Groq (Llama 3.3 70B) · Oracle Cloud (2 VMs)

- **What it does:** answers inbound WhatsApp messages 24/7 in seconds, routes conversations per tenant, escalates to humans only when needed
- **Engineering highlights:**
  - Diagnosed and fixed a production-breaking change in Meta's `remoteJid` → `@lid` GUID format that silently broke message routing in Evolution API
  - Multi-tenant message routing with hardened Supabase RLS policies
  - Zero-marginal-cost inference pipeline — migrated from Claude API to Groq free tier
- **Code:** private (client production system) · architecture writeup available on request

`STATUS: ● LIVE`

### Sels UCOB — Order Management System

Full-stack system built for a real organization (União Centro Oeste Brasileira). Complete order lifecycle — request → warehouse separation → shipment → delivery — with role-based access and photo evidence at each stage.

**Stack:** Next.js 15 · React 19 · TypeScript · Supabase · Tailwind CSS 4 · shadcn/ui · Vercel CI/CD

- **Features:** multi-role auth (admin/operator), real-time inventory and shipment tracking, report generation, photo uploads
- **Scale:** 65+ commits, multi-module architecture, production-ready
- **Deploy:** [sistema-gestao-pedidos.vercel.app](https://sistema-gestao-pedidos.vercel.app)

`STATUS: ● LIVE`

## `>_` AoTomate Sistemas

The venture under VF-Labs. I build custom AI agents, WhatsApp automation pipelines, and management systems engineered around each client's actual operation — no templates, no bloat. First client live in production; building toward a SaaS product.

→ More at [victorfiallho.github.io](https://victorfiallho.github.io)

## `>_` Sharpening now

```
[NOW ]  RAG & retrieval systems — embeddings, eval harnesses, faithfulness
[NOW ]  Agentic AI — multi-agent orchestration beyond visual builders
[NOW ]  Full-stack from scratch — JS → SQL → React/Next → deploy
[NOW ]  AI Engineering degree — math foundations (calculus, linear algebra)
[NEXT]  Cloud certification track — AWS AI Practitioner
```

## `>_` Stack

**AI & Automation**

![N8N](https://img.shields.io/badge/N8N-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Evolution API](https://img.shields.io/badge/Evolution_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=claude&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Backend & Data**

![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Infra**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)

## `>_` Stats

<div align="center">

![Victor's GitHub stats](https://github-readme-stats.vercel.app/api?username=Victorfiallho&show_icons=true&theme=dark&hide_border=true&title_color=3FAE54&icon_color=3FAE54)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Victorfiallho&layout=compact&theme=dark&hide_border=true&title_color=3FAE54)

</div>

<div align="center">

`DATA · MODELS · SYSTEMS · IDEAS · CODE`

</div>
