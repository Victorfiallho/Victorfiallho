<div align="center">

<img src="./assets/vf-labs-banner.svg" alt="VF-Labs — Building Intelligent Systems" width="100%" />

<br/>
<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-victorfiallho.github.io-3FAE54?style=for-the-badge&logo=githubpages&logoColor=white&labelColor=0d1116)](https://victorfiallho.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Victor_Fialho-3FAE54?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1116)](https://br.linkedin.com/in/victor-fialho-9140b23b5)
[![LeetCode](https://img.shields.io/badge/LeetCode-VictorFialho-3FAE54?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0d1116)](https://leetcode.com/u/VictorFialho)

</div>

<br/>

```bash
$ whoami

Victor Fialho — 20 · Brasília, Brazil 🇧🇷
AI Engineering @ IESB (one of Brazil's first bachelor's programs in the field)
Founder @ AoTomate Sistemas

I don't just study automation — I build it, ship it,
and debug it in production for real clients.

$ cat languages.txt
PT (native) · EN (fluent) · ES (advanced)

$ cat off_duty.txt
Jiu-Jitsu · philosophy of mind · history of mathematics
```

<br/>

## `>_` What I'm building

### Hera Remoto — Multi-Tenant WhatsApp AI Agent

Flagship AoTomate system: an AI customer service agent built for a remote secretarial company, **live in production**. End-to-end ownership — architecture, deployment, monitoring, and production debugging.

```
┌─ STACK ──────────────────────────────────────────────────┐
│  N8N · Evolution API · Supabase · Groq (Llama 3.3 70B)   │
│  Oracle Cloud (2 VMs)                                    │
└──────────────────────────────────────────────────────────┘
```

- **What it does:** answers inbound WhatsApp messages 24/7 in seconds, routes conversations per tenant, escalates to humans only when needed
- **Engineering highlights:**
  - Diagnosed and fixed a production-breaking change in Meta's `remoteJid` → `@lid` GUID format that silently broke message routing in Evolution API
  - Multi-tenant message routing with hardened Supabase RLS policies
  - Zero-marginal-cost inference pipeline — migrated from Claude API to Groq free tier
- **Code:** private (client production system) · architecture writeup available on request

`STATUS: ● LIVE`

<br/>

### Sels UCOB — Order Management System

Full-stack system built for a real organization (União Centro Oeste Brasileira). Complete order lifecycle — request → warehouse separation → shipment → delivery — with role-based access and photo evidence at each stage.

```
┌─ STACK ──────────────────────────────────────────────────┐
│  Next.js 15 · React 19 · TypeScript · Supabase           │
│  Tailwind CSS 4 · shadcn/ui · Vercel CI/CD               │
└──────────────────────────────────────────────────────────┘
```

- **Features:** multi-role auth (admin/operator), real-time inventory and shipment tracking, report generation, photo uploads
- **Deploy:** [sistema-gestao-pedidos.vercel.app](https://sistema-gestao-pedidos.vercel.app)

`STATUS: ● LIVE`

<br/>

### Portuguese Sentiment Classifier

NLP pipeline for sentiment analysis in Brazilian Portuguese — classical ML from scratch, no pre-trained models. Corpus preprocessing → TF-IDF → Logistic Regression, with focus on PT-BR text normalization, class imbalance, and model interpretability.

```
┌─ STACK ──────────────────────────────────────────────────┐
│  Python · scikit-learn · pandas · NLTK                   │
└──────────────────────────────────────────────────────────┘
```

- **Code:** [github.com/Victorfiallho](https://github.com/Victorfiallho)

<br/>

## `>_` AoTomate Sistemas

The venture under VF-Labs. I build custom AI agents, WhatsApp automation pipelines, and management systems engineered around each client's actual operation — no templates, no bloat. First client live in production; building toward a SaaS product.

→ More at [victorfiallho.github.io](https://victorfiallho.github.io)

<br/>

## `>_` Stack

**AI & Automation**

![N8N](https://img.shields.io/badge/N8N-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Evolution API](https://img.shields.io/badge/Evolution_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=claude&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![Llama 3.3](https://img.shields.io/badge/Llama_3.3-0467DF?style=flat-square&logo=meta&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Backend & Data**

![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Infra**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)

<br/>

## `>_` Stats

<div align="center">

![Victor's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Victorfiallho&show_icons=true&bg_color=0d1116&title_color=3FAE54&text_color=a4aacb&icon_color=65CC73&hide_border=true)

</div>

<br/>

<div align="center">

`DATA · MODELS · SYSTEMS · IDEAS · CODE · IMPACT`

</div>
