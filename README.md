<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6E56CF,100:A855F7&height=220&section=header&text=Pasindi%20Alawatta&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Engineer%20%7C%20AI%20Engineer%20%7C%20Full-Stack%20Developer&descAlignY=58&descSize=20" width="100%"/>

<img src="https://komarev.com/ghpvc/?username=pasindi15&label=Profile%20Views&color=6e56cf&style=for-the-badge" alt="profile views"/>
<img src="https://img.shields.io/badge/Focus-Enterprise%20Data%20%26%20AI%20Systems-6e56cf?style=for-the-badge" alt="focus"/>
<img src="https://img.shields.io/badge/Flagship%20Projects-4-a855f7?style=for-the-badge" alt="flagship"/>
<img src="https://img.shields.io/badge/Status-Actively%20Building-success?style=for-the-badge" alt="status"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=A855F7&center=true&vCenter=true&width=800&lines=Building+Enterprise+Data+Lakehouses+%F0%9F%8F%A6;Banking-Grade+PII+Tokenization+%26+Privacy+Engineering+%F0%9F%94%90;Medallion+Architectures+%7C+Bronze+%E2%86%92+Silver+%E2%86%92+Gold;RAG+%2B+LangGraph+Multi-Agent+AI+Copilots+%F0%9F%A4%96;Full-Stack+Platforms+%7C+MERN+%7C+Next.js+%7C+React+Native;Data+Engineer+Intern+%40+Bank+of+Ceylon+(BOC)" alt="Typing SVG"/>

</div>

<br/>

<div align="center">

### 📌 Jump to a project
[AtlasDLH-Bank](#-1--atlasdlh-bank--enterprise-banking-data-lakehouse) ·
[AtlasFlow](#-2--atlasflow--cloud-native-aiml-data-platform) ·
[BRAINO](#-3--braino--enterprise-ai-business-operations-manager) ·
[BoBo](#-4--bobo--international-retail-platform) ·
[Tech Stack](#%EF%B8%8F-tech-stack) ·
[GitHub Stats](#-github-stats)

</div>

---

## 🚀 About Me

> Enterprise-grade **data engineering**, **AI systems**, and **full-stack platforms** — built with production discipline, not just prototypes.

- 💼 **Currently:** Data Engineer Intern @ **Bank of Ceylon (BOC)** — Head Office, contributing to an enterprise-scale Data Lakehouse implementation
- 🏗️ **Signature work:** Two independent, production-shaped **banking data lakehouses** (Docker-native and cloud-native), a **100%-complete enterprise AI operations platform**, and a **cross-border retail commerce platform**
- 🧠 **Core competencies:**
  - **Data Engineering** — Kafka/Debezium CDC, Spark, Delta Lake, dbt, Airflow, Trino, medallion (Bronze→Silver→Gold) architecture
  - **AI/ML Systems** — RAG pipelines, LangGraph multi-agent orchestration, MLflow model registries, PyTorch, LLM copilots (Ollama/Groq)
  - **Security & Compliance** — PII tokenization, Fernet encryption, JWT RBAC, audited detokenization workflows (banking AML-grade)
  - **Full-Stack Delivery** — Next.js, React Native/Expo, Node/Express, FastAPI, Prisma/PostgreSQL, Kubernetes
- 📊 **13+ completed projects** spanning data platforms, AI systems, mobile apps, and BI/data warehousing
- 📫 **Reach me:** pasindialawatta@gmail.com

<br/>

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

</div>

---

<div align="center">

## 🏆 Flagship Projects

<i>Four enterprise-scale systems — architected, built, and shipped end-to-end.</i>

</div>

<br/>

## 🏦 1 — AtlasDLH-Bank — Enterprise Banking Data Lakehouse

<div align="center">

![Status](https://img.shields.io/badge/Status-11%2F11%20Phases%20Complete-success?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-Spark%20%7C%20Kafka%20%7C%20Delta%20Lake%20%7C%20Trino-6e56cf?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-100%25%20Free%20%26%20Open%20Source-blue?style=for-the-badge)

</div>

A fully containerized **banking data lakehouse** that ingests core-banking data, moves it through a **Bronze → Silver → Gold** medallion pipeline, and serves executive dashboards, ML fraud/churn scores, natural-language analytics, and a JWT-audited compliance API — while keeping **PII completely out of the analytics and ML path**.

<table>
<tr>
<td width="50%" valign="top">

**🔩 Platform (11 Phases — all ✅)**
- Docker-native stack: Kafka + Debezium CDC, Spark, MinIO (Delta Lake), Airflow, Trino + Hive Metastore
- **PII Classification Gate** — splits every record into encrypted PII (on-prem PostgreSQL vault) + tokenized analytics data *before* any lakehouse write
- 6 Silver tables + 8 Gold tables (KPIs, `customer_360`, fraud/churn ML features) — all `customer_token` only, zero raw PII
- Great Expectations data-quality gates + OpenMetadata governance

</td>
<td width="50%" valign="top">

**🤖 Intelligence & Compliance**
- 4 Superset BI dashboards (Executive, Fraud, Branch, Customer)
- 3 MLflow-tracked models: fraud detection, churn, credit risk — daily batch scoring
- **Atlas Banking Copilot** — RAG (ChromaDB) + Ollama → NL question → Trino SQL → plain-English answer
- **Detokenization & Compliance API** — JWT RBAC, audit-logged AML identity resolution
- **Atlas Command Center** — unified executive portal (17 dashboards, Portfolio, Report Center, Identity Resolution, ML Trainer)

</td>
</tr>
</table>

<details>
<summary><b>🔍 Architecture snapshot</b> (click to expand)</summary>

```
Source DBs (PostgreSQL + MySQL)
        │  PII Classification Gate (Phase 3)
        ├── on-prem vault (token_vault + pii_store, encrypted)
        └── atlas-bronze (tokens only) → Silver → Gold
                                              │
                ┌────────────┬────────────────┼───────────────┬─────────────┐
                ▼            ▼                ▼               ▼             ▼
             Trino      Superset BI       MLflow        AI Copilot   Command Center
                                                                            │
                                                          Identity Resolution UI
                                                          → Detokenization API (audited)
```

</details>

**Tech:** ![Spark](https://img.shields.io/badge/-Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Delta Lake](https://img.shields.io/badge/-Delta%20Lake-00ADD8?style=flat-square) ![Trino](https://img.shields.io/badge/-Trino-DD00A1?style=flat-square) ![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Superset](https://img.shields.io/badge/-Superset-20A6C9?style=flat-square) ![MinIO](https://img.shields.io/badge/-MinIO-C72E49?style=flat-square) ![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square)

---

## ☁️ 2 — AtlasFlow — Cloud-Native AI/ML Data Platform

<div align="center">

![Status](https://img.shields.io/badge/Status-5%2F5%20Steps%20Complete-success?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-dbt%20%7C%20PyTorch%20%7C%20Kubernetes%20%7C%20LangGraph-6e56cf?style=for-the-badge)
![Type](https://img.shields.io/badge/Cost-%240%20Design-blue?style=for-the-badge)

</div>

The same banking domain as AtlasDLH-Bank, **rebuilt the way a modern cloud-native data team ships it** — IaC, CI/CD, containerized model serving, and specialized AI agents — taking Gold CSVs all the way to a Kubernetes-served fraud API and a multi-agent copilot.

<table>
<tr>
<td width="50%" valign="top">

**🔧 Pipeline & Ops**
- **dbt + DuckDB + BigQuery** (via Terraform) — staging → intermediate → marts (`mrt_fraud_features`, `mrt_churn_features`, `mrt_executive_summary`)
- **GitHub Actions** CI/CD (dbt build+test on every PR, lint, prod deploy) + **Airflow** scheduled re-materialization
- **PyTorch** fraud & churn models tracked in **MLflow**, with an optional Llama QLoRA fine-tune notebook

</td>
<td width="50%" valign="top">

**🚀 Serving & Copilot**
- **Kubernetes** (minikube) FastAPI fraud-scoring service with HPA autoscaling + Prometheus/Grafana
- **LangGraph** multi-agent copilot — intent router → SQL agent (DuckDB) / RAG agent (ChromaDB policies) → compliance-gated response
- **AtlasFlow Portal** (Streamlit, 5 dashboards) — Executive, Fraud Risk Desk, Churn Watch, Banking Copilot, Platform Control

</td>
</tr>
</table>

<details>
<summary><b>🔍 End-to-end flow</b> (click to expand)</summary>

```
Gold CSVs → dbt marts (DuckDB + BigQuery)
        ├── GitHub Actions / Airflow → keeps marts fresh & tested
        ├── PyTorch training → fraud_model.pt / churn_model.pt → MLflow
        │        └── FastAPI → Docker → Kubernetes (HPA + Grafana) → /predict
        └── LangGraph agents (SQL + RAG + Compliance) → Streamlit Portal (:8501)
```

</details>

**Tech:** ![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat-square) ![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square) ![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## 🧠 3 — BRAINO — Enterprise AI Business Operations Manager

<div align="center">

<a href="https://braino-xi.vercel.app" target="_blank"><img src="https://img.shields.io/badge/🌐_Live_Demo-braino--xi.vercel.app-a855f7?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo"/></a>
<img src="https://img.shields.io/badge/Progress-30%2F30%20Parts%20%E2%80%94%20100%25-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Lines-34%2C500%2B-orange?style=for-the-badge"/>

</div>

A **commercial-grade AI system**, fully deployed in production (Railway + Vercel), combining document intelligence, conversational AI, financial intelligence, compliance monitoring, proactive health monitoring, and interactive problem-solving — 30/30 parts shipped across 7 phases in 8 weeks.

<table>
<tr>
<td width="50%" valign="top">

**🤖 AI Core**
- RAG pipeline — Groq (Llama 3.3 70B) + ChromaDB, <200ms streaming, <100ms hybrid search
- Citation-accurate document Q&A, 10-message conversational memory
- Braino AI advisor — proactive suggestions, weakness detection (7 categories), recommendation engine

</td>
<td width="50%" valign="top">

**💰 Business Intelligence**
- Financial intelligence — budgets, 90-day cash-flow forecasting, anomaly detection
- Compliance rules engine, real-time alerts, contract-expiry tracking
- Multi-tenant RLS, JWT auth, Stripe billing, SendGrid notifications, PDF/CSV reporting

</td>
</tr>
</table>

<details>
<summary><b>📊 Metrics</b> (click to expand)</summary>

```
Lines of Code: 34,500+   |  API Endpoints: 120+   |  DB Tables: 30+
Search: <100ms  |  RAG Response: <200ms  |  Citation Accuracy: 98%
Anomaly Detection: 85%+  |  Uptime: 99.9%  |  Test Suites: 31/31 passing
```

</details>

**Tech:** ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js%2014-000000?style=flat-square&logo=next.js&logoColor=white) ![Groq](https://img.shields.io/badge/-Groq%20Llama%203.3-000000?style=flat-square) ![ChromaDB](https://img.shields.io/badge/-ChromaDB-FF6B6B?style=flat-square) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Railway](https://img.shields.io/badge/-Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## 🛍️ 4 — BoBo — International Retail Platform

<div align="center">

![Status](https://img.shields.io/badge/Phase%201%20%26%202-Complete-success?style=for-the-badge)
![Status2](https://img.shields.io/badge/Phase%205-Complete-success?style=for-the-badge)
![Status3](https://img.shields.io/badge/Phase%203%2C4%2C6-In%20Progress-yellow?style=for-the-badge)
<a href="https://github.com/pasindi15/BoBo-Retail-APP" target="_blank"><img src="https://img.shields.io/badge/Repo-BoBo--Retail--APP-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

A cross-border retail platform letting customers in **Sri Lanka** buy authentic imported products from **Australia, Japan, USA, and Canada** — shipped as a **mobile app** (Expo/React Native), a **web storefront** (Next.js), and a fully-tested **REST API** in a pnpm monorepo.

<table>
<tr>
<td width="50%" valign="top">

**🔩 Backend (38 routes — production-ready)**
- Express + TypeScript + Prisma/PostgreSQL, Clerk JWT auth, RBAC (Customer/Admin/Supplier/Delivery)
- Full order lifecycle state machine (Pending → Delivered/Cancelled/Refunded) with stock-safe transactions
- Socket.io live order & shipment tracking; Cloudinary image pipeline; Zod-validated everything

</td>
<td width="50%" valign="top">

**💳 Commerce & Logistics**
- PayPal + PayHere (Visa/MC, Bank) + Cash-on-Delivery, live USD→LKR FX with 1-hour cache
- Shipment tracking with carrier events & ETA; DHL/FedEx logistics integration
- Nodemailer transactional emails (order confirmation, shipment, welcome)

</td>
</tr>
</table>

<details>
<summary><b>📦 Monorepo layout</b> (click to expand)</summary>

```
BoBo/
├── apps/
│   ├── api/     — Express + Prisma + Socket.io   (✅ Phase 2)
│   ├── web/     — Next.js 14 storefront           (Phase 4, 75%)
│   └── mobile/  — Expo Router + NativeWind         (Phase 3, in progress)
└── packages/    — @bobo/types, @bobo/config, @bobo/ui (shared)
```

</details>

**Tech:** ![Next.js](https://img.shields.io/badge/-Next.js%2014-000000?style=flat-square&logo=next.js&logoColor=white) ![Expo](https://img.shields.io/badge/-Expo-000020?style=flat-square&logo=expo&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) ![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Clerk](https://img.shields.io/badge/-Clerk-6C47FF?style=flat-square) ![Socket.io](https://img.shields.io/badge/-Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white) ![PayPal](https://img.shields.io/badge/-PayPal-00457C?style=flat-square&logo=paypal&logoColor=white) ![pnpm](https://img.shields.io/badge/-pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)

---

<details>
<summary><h2 style="display:inline">💼 Other Notable Projects (click to expand)</h2></summary>

<br/>

| Project | Description | Stack |
|---|---|---|
| 🏥 **NYHospitalDW & BI Solution** | Star-schema data warehouse + SSAS OLAP cube + 4 Power BI reports on hospital admission data | SQL Server · SSAS · Power BI |
| 💰 **Financial Tracker** | Laravel API + Tabulator grids, budget-vs-actual tracking, Excel/PDF export | Laravel · MySQL · ApexCharts |
| 🩺 **Doctor-Patient Comprehension Analysis** | Statistical + predictive analytics (regression, KNN) on healthcare survey data | R · ggplot2 |
| 🌊 **SafeZone DMS** | Disaster management system — shelters, victim tracking, donations, live mapping | MERN · Mapbox |
| ✈️ **Travellers Platform** | Full travel booking system — flights, hotels, visas, Stripe/PayPal payments | Flask · React · PostgreSQL |
| 🛫 **SkyWay** | Native Android flight-booking app, fragment architecture, Material Design | Kotlin |
| 🌴 **TripMate** | Travel planner UI/UX prototype | Figma |
| 🏔️ **Sky Mountain** | Java MVC property management system | Java · JSP · MySQL |
| 🏃 **Wellness Tracker** | Habit/mood/hydration Android app — scored 10/10 on lab exam | Kotlin |
| 📚 **EduFlex** | Online teacher-training platform (group project) | PHP · MySQL |

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

**Data Engineering**
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=for-the-badge)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge)

**Backend & Cloud**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

**Frontend & Mobile**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=pasindi15&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=A855F7&text_color=c9d1d9" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com?user=pasindi15&theme=radical&hide_border=true&background=0D1117&ring=A855F7&fire=A855F7&currStreakLabel=A855F7" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pasindi15&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=c9d1d9" height="165"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=pasindi15&theme=react-dark&hide_border=true&bg_color=0D1117&color=A855F7&line=A855F7&point=ffffff" width="90%"/>

</div>

---

## 📫 Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-pasindialawatta%40gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pasindialawatta@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pasindi-alawatta)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pasindi15)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:A855F7,100:6E56CF&height=120&section=footer" width="100%"/>

<div align="center"><b>⭐ Building enterprise-grade systems, one pipeline at a time ⭐</b></div>
