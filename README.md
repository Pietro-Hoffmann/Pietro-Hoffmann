<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=700&size=28&pause=1200&color=22D3EE&center=true&vCenter=true&width=700&height=45&lines=Full+Stack+Developer;Network+Observability+%26+SaaS;From+PostgreSQL+to+the+UI" alt="Full Stack Developer — Network Observability" />

# Pietro Hoffmann

**Full stack developer who speaks network.**

I build production SaaS for ISP network monitoring — multi-tenant platforms where the
hard part isn't the CRUD, it's talking to Cisco, Huawei, Juniper and ZTE gear over SSH
and turning what comes back into something an operator can act on.

</div>

---

## What I work on

At **Bamboo Core** I helped build *Kuantics*, a multi-tenant SaaS for ISP network
monitoring (~29 repositories in production), and was the **lead author of Noc.ai**, its
AI-powered NOC product. A few things I shipped there:

- **An AI agent that runs read-only commands on live network gear** — multi-vendor
  (Cisco, Huawei, Juniper, ZTE, Datacom) over SSH with bastion jump. Credentials are
  never exposed to the model, authorization is per-device, and there's a kill-switch
  that rolls back without a deploy.
- **An autonomous incident diagnosis pipeline** — temporal correlation across Zabbix ×
  Graylog × InfluxDB, then an LLM agent that investigates the device on its own under a
  read-only whitelist and hard command/time ceilings until it reaches root cause.
- **An SRE-grade alerting engine** — incident state machine with sustained-degradation
  detection, 6 triggers per sensor (IPv4/IPv6), parallel DNS alerting, and
  WhatsApp/email notifications with N:N profiles — exactly one notification per episode.
- **Ecosystem-wide SSO** — shared JWT across 5 products, 2FA (TOTP and email) with
  anti-brute-force, refresh token rotation, and admin impersonation with an audit trail.
- **LLDP topology discovery**, validated in the field at 47 nodes and 46 links, 100%
  over SSH — plus per-vendor PON optical signal reads and BGP/interface flap detection
  on InfluxDB v2 (Flux).
- **AI cost controls in production** — token accounting per tenant and per product,
  plan-based limits with automatic blocking, consumption alerts and usage dashboards.

> Most of that work lives in private repositories. What's public here is the trail that
> got me there — coursework, experiments, and the projects I learned on.

---

## Tech

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB_(Flux)-22ADF6?style=flat-square&logo=influxdb&logoColor=white)

**Networks & Ops**

![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![IPv6](https://img.shields.io/badge/IPv6_·_DNS-0F766E?style=flat-square&logo=cloudflare&logoColor=white)

---

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[form-checker-pro](https://github.com/Pietro-Hoffmann/form-checker-pro)** | Real-time exercise form checker — reads body pose from the webcam and flags bad reps | TypeScript · React · MediaPipe |
| **[Dashboard-streamlit](https://github.com/Pietro-Hoffmann/Dashboard-streamlit)** | Multi-page weather analytics dashboard over a real INMET dataset (Porto Alegre) | Python · Streamlit · Pandas |
| **[API_filmes](https://github.com/Pietro-Hoffmann/API_filmes)** | Movie catalog SPA — search, grid and detail modal against a public film API | React · TypeScript · Vite |
| **[task-Manager-Ultimate-Version-Finall](https://github.com/Pietro-Hoffmann/task-Manager-Ultimate-Version-Finall)** | Task manager REST API in clean MVC, documented with Swagger | Node.js · Express · EJS |

---

## Background

- **Technical Diploma in Informatics** — ETEC Monteiro Lobato (2023 – 2026)
- **NIC.br** — IPv6 Fundamentals (2025)
- **X FEBIC Distinction** — Robotics & Computational Intelligence, for *FoodSense*,
  a team-built app helping people with food intolerances eat safely

## Languages I speak

🇧🇷 **Portuguese** — Native  
🇺🇸 **English** — Advanced

---

<div align="center">

<sub>Interested in networks, observability, and systems that have to stay up.</sub>

</div>
