<div align="center">

# Hi, I'm Saurabh Sonawane 👋

### Enterprise Java Backend Developer | Scalable Systems | Business Workflow Automation

I engineer reliable backend platforms that modernize enterprise applications, scale with demand,
and turn repetitive business processes into secure, observable, automated workflows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saurabhsds13)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-00EA64?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/profile/saurabhsds13)
[![Email](https://img.shields.io/badge/Email-Let's_Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saurabhsds13@gmail.com)

</div>

---

## 👨‍💻 About Me

I'm a backend-focused software engineer specializing in **enterprise Java**, **Spring Boot**, and **distributed systems**. I build high-throughput APIs, event-driven services, and automation solutions designed for maintainability, resilience, and secure operation in production.

My work spans application modernization, database upgrades, asynchronous processing, CI/CD automation, observability, performance engineering, and production-grade AI-assisted workflows. I care about systems that are easy to operate—not just easy to demo—and services that do not wake anyone up at 3 AM.

- 🏗️ Build scalable, maintainable services using clean architecture and proven design patterns
- ⚡ Design event-driven and asynchronous flows with Kafka and message queues
- 🔄 Automate manual business processes and software delivery workflows
- 🔐 Treat security, validation, and sensitive-data protection as design requirements
- 📊 Use logging, health checks, tests, and load analysis to improve production reliability

---

## 🎯 Engineering Focus

| Enterprise Backend Engineering | Scalability & Reliability | Business Process Automation |
|:---|:---|:---|
| Java and Spring Boot services, REST APIs, application modernization, and clean architecture | Distributed services, event streaming, caching, load testing, observability, and resilient delivery | Automated business workflows, CI/CD pipelines, asynchronous processing, and AI-assisted operations |

---

## 🧰 Technology Stack

### Backend & Architecture

![Java](https://img.shields.io/badge/Java_8–21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-005571?style=flat-square&logo=fastapi&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapiinitiative&logoColor=white)

`Microservices` · `Clean Architecture` · `SOLID` · `Design Patterns` · `API Security`

### Data, Caching & Messaging

![MongoDB](https://img.shields.io/badge/MongoDB_8.x-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

`Event Streaming` · `Partition Strategies` · `Exactly-Once Semantics` · `Caching` · `Session Management` · `Rate Limiting`

### DevOps, Quality & Observability

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Elastic Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)
![Apache JMeter](https://img.shields.io/badge/Apache_JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

`Pipeline as Code` · `Multi-Environment Delivery` · `Rollback Strategies` · `Structured Logging` · `Health Checks` · `Unit & Integration Testing`

### AI & Frontend

![Amazon Q](https://img.shields.io/badge/Amazon_Q-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

`AI Agents` · `Production Prompt Engineering` · `Backend-Heavy Full-Stack Delivery`

---

## &#128640; Featured Projects

### Quick-Commerce Order & Inventory Platform

A production-style commerce ecosystem spanning a customer storefront and an enterprise order-management platform, connected through bidirectional Kafka event flows.

```text
QuickBasket Storefront
        │  ORDER_PLACED · oms.orders.inbound
        ▼
    Apache Kafka
        │
        ▼
Enterprise OMS ── Order · Inventory · Payment · Shipping · Analytics
        │  ORDER_STATUS · oms.orders.status
        ▼
    Apache Kafka
        │
        ▼
QuickBasket ── Audit History · User Notification · Live SSE Update
```

- **[QuickBasket E-Commerce System](https://github.com/Saurabhsds13/QuickBasket-Ecommerce-System)** — Java 17, Spring Boot 3.2, React 19, MySQL, Redis, JWT security, Razorpay payments, Kafka, and server-sent events. Implements catalog, cart, checkout, orders, returns, notifications, and administration across a seeded catalog of 170+ products and 20 categories.
- **[Enterprise Order Management System](https://github.com/Saurabhsds13/IBM-OMS-SYSTEM)** — Java 17 and Spring Boot 3.5 modular monolith covering order lifecycle, inventory reservation, payment, shipping, analytics, JWT/RBAC, Flyway migrations, and a Kafka-backed transactional outbox.
- Publishes committed orders to `oms.orders.inbound` and returns lifecycle updates through `oms.orders.status`, with messages keyed by order number to preserve per-order partition ordering.
- Designs for **at-least-once delivery** through idempotent order intake, producer idempotence, auditable status history, and explicit failure-handling trade-offs.

[View Storefront Repository](https://github.com/Saurabhsds13/QuickBasket-Ecommerce-System) · [View OMS Repository](https://github.com/Saurabhsds13/IBM-OMS-SYSTEM) · [Kafka Integration Contract](https://github.com/Saurabhsds13/QuickBasket-Ecommerce-System/blob/main/docs/oms-integration.md)

### AI Customer Support Assistant

A human-in-the-loop support workflow that combines enterprise Java engineering with grounded generative AI.

- **[AI Customer Support Assistant](https://github.com/Saurabhsds13/ai-customer-support-assistant)** — Java 21, Spring Boot 3.3, Spring AI, PostgreSQL, Docker Compose, Spring Security, and JWT/RBAC.
- Implements ticket analysis, priority classification, provider-agnostic LLM integration, controlled tool calling, and agent approval or rejection of generated responses.
- Builds a RAG pipeline with document chunking, vector search, grounding, source citations, and a guard that avoids calling the model when relevant context is unavailable.
- Adds production-style controls through AI audit logs, Prometheus metrics, health indicators, retry and circuit-breaker policies, structured logging, and unit/integration testing with JUnit, Mockito, and Testcontainers.

[View Repository](https://github.com/Saurabhsds13/ai-customer-support-assistant)

<sub>These are independent portfolio systems designed to demonstrate architecture and engineering practices; they are not representations of vendor-owned production platforms.</sub>

---

## &#128200; Selected Engineering Impact

<table>
<tr>
<td align="center"><strong>Java 8 → 21</strong><br/>Enterprise application modernization</td>
<td align="center"><strong>Zero Downtime</strong><br/>Production migration rollout</td>
<td align="center"><strong>MongoDB 8.x</strong><br/>Major database version migration</td>
<td align="center"><strong>Automated Delivery</strong><br/>Build, test, deploy, and rollback</td>
</tr>
</table>

- **Modernized enterprise Java applications from Java 8 to Java 21**, addressing deprecated APIs, module-system considerations, library compatibility, and regression coverage while maintaining a zero-downtime rollout.
- **Delivered a MongoDB 8.x migration**, adapting schema validation and aggregation pipelines while revisiting index strategy for compatibility and performance.
- **Engineered Jenkins CI/CD pipelines** that automate builds, tests, multi-environment deployments, and rollback procedures for safer, repeatable releases.
- **Improved distributed-service operability** through centralized structured logging, ELK-based analysis and alerting, and health-check endpoints.
- **Protected production data** with layered authentication and authorization, input validation, API security controls, and masking that keeps PII and tokens out of plain-text logs.
- **Validated API capacity with JMeter**, exposing bottlenecks, connection-pool constraints, and memory issues before they reached users.
- **Built Kafka-based processing flows** using deliberate partitioning and delivery-semantics strategies for dependable asynchronous workloads.
- **Automated repetitive business and team workflows**, reducing manual handoffs and creating more consistent, auditable execution paths.
- **Developed Amazon Q AI agents** with production-oriented prompt practices focused on consistent and reliable workflow outputs.

<!--
Replace or supplement the impact statements above with verified business metrics when available, for example:
- Reduced processing time from [X] to [Y]
- Increased sustained throughput to [N] requests/events per second
- Reduced deployment time or failure rate by [N%]
- Saved [N] engineering or operations hours per month through automation
Do not publish estimates that cannot be supported in an interview.
-->

---

## 🧭 How I Engineer

- **Automate deliberately:** if a repeatable process is being performed manually, I look for a reliable way to automate it.
- **Design for change:** clear boundaries, SOLID principles, and readable code keep enterprise systems adaptable.
- **Build quality in:** unit, integration, regression, and load testing are part of delivery—not post-release activities.
- **Secure by default:** authorization, validation, API protection, and safe logging begin at design time.
- **Operate what I build:** observability, health checks, failure handling, and rollback paths are core features.

---

<div align="center">

<table width="92%">
<tr>
<td align="center">

<h2 align="center">📊 GitHub Overview</h2>

<a href="https://github.com/Saurabhsds13">
  <img width="84%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Saurabhsds13&theme=github" alt="Saurabh's GitHub profile summary" />
</a>

<br /><br />

<a href="https://github.com/Saurabhsds13?tab=repositories">
  <img width="40%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Saurabhsds13&theme=github" alt="Saurabh's repositories by language" />
</a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/Saurabhsds13">
  <img width="40%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Saurabhsds13&theme=github" alt="Saurabh's GitHub statistics" />
</a>

<br /><br />

<sub>Statistics reflect public GitHub activity and do not represent overall professional experience.</sub>

<br />

</td>
</tr>
</table>

</div>

---

## 🤝 Let's Connect

I'm always interested in discussing **enterprise Java**, **backend architecture**, **distributed systems**, **application modernization**, and **business workflow automation**.

- 💼 [LinkedIn](https://www.linkedin.com/in/saurabhsds13)
- 🧩 [HackerRank](https://www.hackerrank.com/profile/saurabhsds13)
- 📧 [saurabhsds13@gmail.com](mailto:saurabhsds13@gmail.com)

<div align="center">

**Build for scale. Automate with purpose. Operate with confidence.**

</div>
