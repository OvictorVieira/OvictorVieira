<h1 align="center">Victor Hugo</h1>

<p align="center">
  <strong>Senior Software Engineer</strong><br>
  Node.js · Go · TypeScript · Cloud Native (AWS) · AI-Assisted Development &amp; LLMs<br>
  <sub>Marília, São Paulo — Brazil</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/victor-hugo-vieira/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:victor.h.souza.vieira@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## About

Software Engineer with 10 years of experience building high-scale systems for companies like
**iFood**, **Magalu (Luizalabs)** and, currently, **Sem Parar (Fiserv/Corpay)**.
My focus is backend engineering for **payments** and **logistics** — the flows where correctness,
idempotency and observability are not optional.

I am an early adopter of **LLMs in the development workflow**: I use them to accelerate delivery,
automate testing and cut time-to-market, not as a gimmick but as part of the daily toolchain.

## What I'm doing right now

- **Fintech & Payments** — core banking platform at Sem Parar (Fiserv integration): card issuance,
  duplicate-card flows, spend limits and lock/unlock features with **NestJS + TypeScript**.
- **AI & Automation** — built an incident triage system (Tauri + Rust + Python) that connects **Jira**
  with **AWS logs** to classify tickets and surface root cause automatically, cutting initial
  investigation from **30+ min to under 5 min**.
- **Modernization** — migrating legacy **AWS Lambda** architectures to **Node.js/NestJS**
  microservices for stability and lower latency.

## Engineering impact

| Context | What I did |
| --- | --- |
| iFood | Merchant data platform under a **~65M orders/month** stream (Kotlin, Java, Go, Node.js, Kafka) |
| iFood | Content-moderation feature integrated with **AWS SageMaker**, preventing multimillion-dollar losses |
| Delivery Center | Led migration of order intake from synchronous Node.js to **event-driven Go + Pub/Sub** (1M+ orders) |
| Luizalabs | Logistics from order separation to delivery and reverse logistics; automation dropped recurring incident response from **~30 min to <5 min** |
| Luizalabs | Migration of legacy systems from AWS to proprietary cloud; monitoring with Grafana + alerting |
| Everywhere | Mentoring juniors/mids, documentation culture, incident ownership |

## How I work with AI

- **Agentic coding** — power user of **Claude Code**, Cursor and Codex for implementation,
  refactoring, code explanation and debugging.
- **Custom AI Skills** — I build reusable skills/commands that encode my own engineering standards
  (testing protocol, safe refactor, root-cause debugging, PR review) so the agent follows *my* rules.
- **AI-driven workplans** — architecture and task validation before writing code, so the agent
  executes a reviewed plan instead of improvising.
- **Automation over chat** — LLMs wired into real systems (Jira, AWS logs, CI) to remove toil,
  not just to answer questions.

## Tech stack

**Languages**
<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white">
  <img alt="Ruby" src="https://img.shields.io/badge/Ruby%20on%20Rails-CC0000?style=flat-square&logo=rubyonrails&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
</p>

**Frameworks & Runtime**
<p>
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black">
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=black">
</p>

**Cloud & Infra**
<p>
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white">
</p>

**Messaging & Data**
<p>
  <img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
</p>

## Selected open projects

| Project | What it is | Stack |
| --- | --- | --- |
| [exchange.airdrop.analyzer](https://github.com/OvictorVieira/exchange.airdrop.analyzer) | Local-first desktop app to analyze exchange CSVs and measure farm/airdrop performance (volume, PnL, ROI) — 100% offline | TypeScript |
| [turing-sql-machine](https://github.com/OvictorVieira/turing-sql-machine) | Generates SQL queries from natural language | JavaScript |
| [transact.ease](https://github.com/OvictorVieira/transact.ease) | Transaction management system for card operations and account handling | Go |
| [logistics.api](https://github.com/OvictorVieira/logistics.api) | Logistics API study/reference project | Kotlin |
| [git.history.analyser](https://github.com/OvictorVieira/git.history.analyser) | Repository history analysis tooling | — |

## GitHub metrics

<p align="center">
  <img alt="GitHub metrics" src="./metrics/overview.svg">
</p>
<p align="center">
  <img alt="Most used languages" src="./metrics/languages.svg">
</p>
