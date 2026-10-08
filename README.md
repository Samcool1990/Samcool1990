<h1 align="center">Hi 👋, I'm Suman Pathak</h1>

<h3 align="center">Technical Architect | Senior Python Backend Engineer | GenAI & LLMOps</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=700&color=3776AB&center=true&vCenter=true&width=800&lines=Python+%7C+FastAPI+%7C+SQL+%7C+AWS;GenAI+%7C+LLMOps+%7C+Observability;Building+Scalable+Production+Systems;Cloud-Native+Backend+Engineering;14%2B+Years+of+Software+Engineering" alt="Typing Animation"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/14%2B%20Years-Software%20Engineering-1f6feb?style=for-the-badge" alt="Experience"/>
  <img src="https://img.shields.io/badge/Python-8%2B%20Years-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/FastAPI-6%2B%20Years-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/LLMOps-Production-6B4FBB?style=for-the-badge" alt="LLMOps"/>
</p>

---

## 👨‍💻 `whoami`

<p align="center">
  <img src="./whoami.svg" alt="Terminal: Suman Pathak, Technical Architect and Senior Python Backend Engineer, 13+ years, Python FastAPI SQL AWS GenAI LLMOps Observability" width="860"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OPEN%20TO-Senior%20Python%20Backend-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Open to Senior Python Backend"/>
  <img src="https://img.shields.io/badge/OPEN%20TO-Technical%20Architect-6B4FBB?style=for-the-badge" alt="Open to Technical Architect"/>
  <img src="https://img.shields.io/badge/OPEN%20TO-GenAI%20%2F%20LLMOps-009688?style=for-the-badge" alt="Open to GenAI and LLMOps"/>
</p>

### 🛠️ What I love building

- 🐍 Production-grade **Python & FastAPI** backends
- 🧠 **GenAI / LLMOps** platforms and developer tooling
- ☁️ Cloud-native architectures on **AWS**
- 🔭 **OpenTelemetry**-based observability
- ⚡ Event-driven and asynchronous systems
- 🗄️ High-volume **SQL and data platforms**
- 🔐 Secure REST APIs and authentication workflows
- 🧩 Clean architecture, OOP, SOLID and engineering standards

---

<h2 align="center">⚡ Tech Stack & Currently Learning</h2>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./Skills_Animation_Dark.gif">
    <source media="(prefers-color-scheme: light)" srcset="./Skills_Animation_White.gif">
    <img alt="Skills animation" src="./Skills_Animation_White.gif">
  </picture>
</p>

**🌱 Currently learning**

- Deepening my knowledge in Machine Learning and AI
- Exploring advanced React.js patterns and state management
- Improving my cloud skills across AWS and Azure

---

## 🏗️ Architecture I Work With

```mermaid
flowchart LR
    APP["🤖 AI / LLM apps"] --> SDK["Python SDK<br/>decorators + OpenTelemetry"]
    SDK --> API["⚡ FastAPI<br/>REST API"]
    API -.-> REDIS[("Redis cache")]
    API -.-> SQL[("SQL / Snowflake")]
    API --> SNS{{"SNS<br/>fan-out"}}
    SNS --> SQS["SQS queues"]
    SQS --> WK["☸️ EKS workers<br/>KEDA queue-depth scaling"]
    WK --> S3["S3"]
    WK --> NR["New Relic"]
    WK --> LF["Langfuse"]
    WK -. status .-> DDB[("DynamoDB<br/>processing status")]
    WK -. failed traces .-> FS3["S3<br/>failed-trace store"]
    FS3 -. batch recovery .-> SQS

    style API fill:#009688,color:#fff,stroke:#00695c
    style SNS fill:#FF4F8B,color:#fff,stroke:#c2185b
    style WK fill:#326CE5,color:#fff,stroke:#1a4cb5
    style SDK fill:#3776AB,color:#fff,stroke:#1f4f7a
```

> **Tracing · Evaluation · Reliability · Redaction · Retryability · Observability · Scalability**

---

## 🏆 Key Achievements

<details open>
<summary><b>🔭 Enterprise LLMOps Observability</b></summary>
<br/>

Contributed to an enterprise observability platform for AI/LLM applications:

- LLM call tracing through Python SDK decorators
- LLM evaluation capture — score, label and rationale
- REST API observability
- Transaction and span tracking
- OpenTelemetry instrumentation
- Website crawling observability
- Redaction and privacy-aware telemetry
- Non-blocking and idempotent exports
- Multi-destination telemetry delivery

</details>

<details>
<summary><b>📈 Designed for Production Scale</b></summary>
<br/>

Helped evolve the architecture from direct queue processing to a **fan-out architecture using SNS + queues**, enabling reliable distribution to multiple downstream destinations.

| Today | Designed for |
|---|---|
| **15–20** production applications | Significantly higher future volume |
| **10K+** transactions / day | |

</details>

<details>
<summary><b>🔄 Reliability & Failure Recovery</b></summary>
<br/>

- DynamoDB-based processing status
- Destination-specific retry handling
- Failed-trace persistence in S3
- Batch recovery jobs
- Data restoration workflows
- Monitoring and validation

🎯 Engineering objective: **zero data loss**

</details>

<details>
<summary><b>☁️ Cloud-Native AWS Architecture</b></summary>
<br/>

Hands-on work across **EKS · KEDA · SNS · SQS · Lambda · DynamoDB · S3**, with a focus on:

- Asynchronous processing
- Horizontal scaling
- Queue-depth-based scaling
- Retries and fault tolerance
- Distributed workloads

</details>

<details>
<summary><b>👨‍🏫 Engineering & Mentoring</b></summary>
<br/>

- Mentored **5 interns/developers**
- Contributed to coding and design standards
- Worked on production code-quality improvements
- Addressed SonarQube issues and technical debt
- Promoted maintainable Python and clean architecture

</details>

---

## 🛠️ Tech Stack

### 🐍 Languages & Backend

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/REST%20APIs-02569B?style=for-the-badge"/>
</p>

### ☁️ Cloud & AWS

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon%20SQS-FF4F8B?style=for-the-badge&logo=amazonsqs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon%20SNS-FF4F8B?style=for-the-badge&logo=amazonsns&logoColor=white"/>
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon%20EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white"/>
</p>

### 🧠 GenAI / LLMOps / Observability

<p>
  <img src="https://img.shields.io/badge/GenAI-412991?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LLMOps-6B4FBB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white"/>
  <img src="https://img.shields.io/badge/Langfuse-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/New%20Relic-1CE783?style=for-the-badge&logo=newrelic&logoColor=black"/>
</p>

### 🗄️ Data & Messaging

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
</p>

### ⚙️ DevOps & Engineering

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/KEDA-326CE5?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bamboo-0052CC?style=for-the-badge&logo=bamboo&logoColor=white"/>
</p>

---

## 📊 Experience Meter

<sub>1 block = 1 year</sub>

```text
Python          ████████░░░░░  8+ yrs
SQL/PostgreSQL  ████████░░░░░  8+ yrs
FastAPI         ██████░░░░░░░  6+ yrs
Snowflake       ██████░░░░░░░  6+ yrs
AWS             ████░░░░░░░░░  4+ yrs
Docker          ████░░░░░░░░░  4+ yrs
GenAI / LLM     ██░░░░░░░░░░░  2+ yrs
LLMOps          ██░░░░░░░░░░░  2+ yrs
Kubernetes/EKS  ██░░░░░░░░░░░  2+ yrs
Kafka           ██░░░░░░░░░░░  2+ yrs
Redis           ██░░░░░░░░░░░  2+ yrs
OpenTelemetry   ██░░░░░░░░░░░  2+ yrs
```

---

## 💡 Engineering Principles

| | Principle |
|:-:|---|
| 📏 | **Measure before optimizing.** |
| 💥 | **Design for failure, not just the happy path.** |
| 🔭 | **Keep APIs simple and systems observable.** |
| 🧼 | **Prefer clean architecture over clever code.** |
| 📈 | **Scale based on real workload and measurements.** |

---

## 💼 Career Journey

```mermaid
flowchart LR
    A["🏢 TCS<br/>2013 – 2022"] --> B["🏦 LTIMindtree<br/>2022 – 2023"]
    B --> C["🧪 SmartIMS<br/>2023 – 2025"]
    C --> D["🚀 Hexaware<br/>2025 – now"]

    style D fill:#1f6feb,color:#fff,stroke:#0d419d
```

<details open>
<summary><b>🔹 Hexaware Technologies</b> · Senior Developer · Jan 2025 – Present</summary>
<br/>

Enterprise LLMOps / AI Observability platform.

**Focus:** Python · FastAPI · AWS · OpenTelemetry · LLMOps · EKS · KEDA · SQS/SNS · DynamoDB · S3 · New Relic · Langfuse · Snowflake

</details>

<details>
<summary><b>🔹 SmartIMS</b> · Oct 2023 – Jan 2025</summary>
<br/>

Life Sciences / CTMS backend engineering.

**Focus:** Python · Backend Development · Kafka · Event-Driven Architecture · Data Consistency · Retry Handling

</details>

<details>
<summary><b>🔹 LTIMindtree</b> · Oct 2022 – Oct 2023</summary>
<br/>

Banking backend microservices.

**Focus:** Python · FastAPI · AWS Lambda · REST APIs · Authentication · Microservices

</details>

<details>
<summary><b>🔹 Tata Consultancy Services</b> · Mar 2013 – Oct 2022</summary>
<br/>

Software engineering, production support and Python backend development.

**Focus:** Python · Backend Engineering · Production Systems · SQL · Application Support

</details>

---

## 📌 What I'm Looking For

I'm most interested in roles where **Backend Engineering + Cloud + AI + Observability** come together:

- **Senior Python Backend Engineering**
- **Technical Architecture**
- **GenAI Engineering**
- **LLMOps / AI Platform Engineering**
- **Cloud-Native Backend Systems**
- **Distributed Systems**
- **Observability Platforms**
- **High-Scale API & Data Platforms**

---

## 📈 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Samcool1990&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="420" alt="GitHub Stats"/>
  <img src="https://streak-stats.demolab.com/?user=Samcool1990&theme=tokyonight&hide_border=true" width="420" alt="GitHub Streak"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Samcool1990&layout=compact&theme=tokyonight&hide_border=true" width="420" alt="Top Languages"/>
</p>

---


---

## 🤝 Let's Connect

<p align="center">
  <a href="https://github.com/Samcool1990">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/sumanpathak-ai-work/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

<p align="center">
  <b>Python • FastAPI • SQL • AWS • GenAI • LLMOps • Observability</b>
</p>

---

<h3 align="center">🚀 Building reliable backend systems for the AI era.</h3>

<p align="center">
  Thanks for visiting my profile!
</p>
