# Hey, I'm Sabir 👋

**Software Engineer currently working in fault-tolerant distributed systems, real-time voice infrastructure, and production-scale data engines.**

**Portfolio: https://sabir.is-a.dev**

> 90% of my enterprise code lives behind private corporate GitLab mirrors. Here is the actual scale, traffic, and complexity I design and manage daily:

## Production Scale & Core Achievements

<details>
<summary><b>High-Throughput Telephony Architecture</b></summary>

* Architected multi-instance real-time telephony services using SIP.js and FreeSWITCH across 9 microservices.
* Implemented concurrency-safe routing using Cassandra Lightweight Transactions (LWTs).

</details>

<details>
<summary><b>Data Migrations</b></summary>

* Executed live, dual-write migrations of 20+ Cassandra tables with over 15 million rows from DataStax to self-hosted infrastructure.
* Built fault-tolerant Node.js automation that successfully bypassed mid-run version incompatibilities without crashing.

</details>

<details>
<summary><b>Distributed Schedulers</b></summary>

* Built a shard-based distributed job scheduler processing over 10,000 daily tasks.
* Enforced epoch fencing for zero split-brain incidents.
* Tuned `gc_grace_seconds` to eliminate tombstone bloat, dropping Cassandra read timeouts to zero.

</details>

<details>
<summary><b>Real-Time Notification Engines</b></summary>

* Engineered a RabbitMQ and WebSocket event pipeline processing over 500,000 daily events.
* Sustained 500 messages per second with sub-50ms latency for live call state webhooks.

</details>

<details>
<summary><b>Data Reliability & Optimization</b></summary>

* Redesigned logging pipelines to append-only logic, achieving 100% call state accuracy and eliminating complex backend reconciliation.
* Cut final status latency by 80%, dropping it from 5 seconds to 1 second.

</details>

<details>
<summary><b>Infrastructure & CI/CD</b></summary>

* Orchestrated a Docker Swarm environment for 19 microservices.
* Built tag-driven automated CI pipelines that enabled 8 or more zero-downtime weekly production releases.

</details>

## 🧪 Personal Projects

📦 **[Angle](https://github.com/anonlegionoke/angle)**
> An AI animation studio that converts natural language prompts into dynamic mathematical animations using Python, Manim, and automated FFmpeg processing pipelines.

📦 **[Taskforge - Distributed Job Scheduler](https://github.com/anonlegionoke/taskforge)**
> A fault-tolerant, horizontally scalable TypeScript engine driven by RabbitMQ and PostgreSQL, featuring a live telemetry and monitoring dashboard.

📦 **[Askverse](https://github.com/anonlegionoke/chat-with-ai-rag)**
> A production-ready multi-mode document Q&A system leveraging LangChain, advanced semantic routing, and vector databases.

📦 **[Crypto Gate](https://github.com/anonlegionoke/crypto-pay-gateway)**
> A crypto payment gateway enabling merchants to accept any SPL token with automatic USDC conversion via Jupiter aggregator on Solana, featuring real-time payment detection and a merchant dashboard.
  
## 🛠️ Core Engineering Toolkit

### Languages
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Backend & Runtimes
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101) ![SIP.js](https://img.shields.io/badge/SIP.js-%23FF5722.svg?style=for-the-badge&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white) ![Framer](https://img.shields.io/badge/Framer-black?style=for-the-badge&logo=framer&logoColor=blue)

### Databases & Message Brokers
![Apache Cassandra](https://img.shields.io/badge/cassandra-%231287B1.svg?style=for-the-badge&logo=apache-cassandra&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) 

### DevOps & Cloud
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

### 🌱 Currently Learning & Exploring
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-FFFFFF?style=for-the-badge&logo=langchain&logoColor=black)

**Applied LLMs • RAG Pipelines • Vector Search**

## 🎯 Current Focus

I thrive in high-ownership environments, startup speed, and early-stage engineering teams building real infrastructure. I am currently open to remote backend or full-stack roles.

[LinkedIn](https://linkedin.com/in/sabirpm) • [Portfolio Website](https://sabir.is-a.dev) • [Email Me](mailto:smrazind@gmail.com)
