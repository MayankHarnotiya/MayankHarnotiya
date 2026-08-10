<div align="center">

# Mayank Harnotiya

### Backend Software Engineer — Java · Spring Boot · Microservices · Kafka · AWS

🟢 **Open to Work** — Immediate Joiner · Open to relocation across India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayank-harnotiya/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mayankharnotiya25@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/MayankHarnotiya/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MayankHarnotiya)

</div>

---

## About Me

Backend engineer with ~1 year building production **Java 17 / Spring Boot** microservices and REST APIs — across a **US fintech client (EZCORP, via VRIZE)** and a **Government of India platform (C-DAC)**. I care about the parts of backend engineering that don't show up in a demo: idempotency under concurrent load, transactional integrity, and treating every external input — including LLM output — as untrusted until proven otherwise.

- 🔭 Currently deepening Kafka internals (consumer groups, exactly-once semantics) and distributed-systems patterns
- 🌱 Learning Kubernetes and Spring AI internals
- 🤝 Looking to connect with teams hiring for **SDE-1 / Backend Engineer** roles
- 💬 Ask me about idempotency design, optimistic locking, REST API design, Spring Security (JWT/RBAC), or safely handling LLM output in production backends
- ⚡ In fintech, a backend bug isn't a bug report — it's a financial incident. That's the mindset I build with.

---

## Featured Projects

### 🔗 PayLite — Event-Driven Fintech Wallet
Spring Boot · Java 17 · Kafka · Redis · MySQL · AWS
[Live Demo](https://paylite-web.vercel.app) · [GitHub](https://github.com/MayankHarnotiya/payLite)

An event-driven payment wallet built to prevent double-spending on concurrent P2P transfers using **four independent layers of defense** — Redis idempotency keys (`SET NX`, 24h TTL), a unique ledger constraint, `@Version` optimistic locking, and a DB-level balance check. Completed transfers publish Kafka events to a separate notification service, after commit, fire-and-forget. Deployed on AWS (Elastic Beanstalk, RDS) via multi-stage Docker, with 78% test coverage (JUnit 5, Mockito, Jacoco).

### 🔗 QuerySense — LLM-Powered Text-to-SQL Analytics API
Spring Boot · Spring AI · PostgreSQL · Redis
[Live Demo](https://query-sense-frontend.vercel.app) · [GitHub](https://github.com/MayankHarnotiya/querySense)

A natural-language-to-SQL API where users query uploaded CSVs in plain English via an LLM (Groq Llama-3.3-70B), integrated through Spring AI. The core engineering problem: treating model output as **untrusted input**. I built a deterministic SQL-safety pipeline using JSQLParser — enforcing single-statement, SELECT-only, schema-validated SQL executed through a read-only PostgreSQL role — three independent layers blocking SQL injection, stacked queries, and hallucinated tables.

---

## Experience

**Associate Software Engineer** — VRIZE India Pvt. Ltd. (Client: EZCORP Inc., US Fintech)
Built REST endpoints across an 8-service Spring Boot platform for loan issuance and repayment; made repayment processing atomic with `@Transactional`; eliminated N+1 queries with JOIN FETCH and EXPLAIN-verified indexing.

**Software Engineer Intern** — C-DAC (Govt. of India)
Built REST APIs and JWT-secured, role-based dashboards for CyberShakti, a national cybersecurity training platform.

---

## Tech Stack

**Languages:** ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-323330?style=flat-square&logo=javascript&logoColor=F7DF1E) ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Backend:** ![Spring](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring&logoColor=white) ![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Kafka](https://img.shields.io/badge/-Apache%20Kafka-000000?style=flat-square&logo=apachekafka&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Data:** ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)

**Cloud & DevOps:** ![AWS](https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-0DB7ED?style=flat-square&logo=docker&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Frontend:** ![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TailwindCSS](https://img.shields.io/badge/-Tailwind-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)

**Tools:** ![Git](https://img.shields.io/badge/-Git-F05033?style=flat-square&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) ![Jira](https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

---

## GitHub Stats

<div align="center">

![](https://github-readme-stats.shion.dev/api?username=MayankHarnotiya&theme=default&hide_border=true&include_all_commits=false&count_private=false)
![](https://github-readme-stats.shion.dev/api/top-langs/?username=MayankHarnotiya&theme=default&hide_border=true&layout=compact)

</div>

---

## Achievements

- 🧩 **500+ DSA problems** solved across LeetCode & GeeksforGeeks
- 📜 The Complete Java Masterclass (VRIZE) — [Verify](https://drive.google.com/file/d/1PqRp62JaNVPJYRs5gYzamMAAbS8bYd4q/view?usp=sharing)

<div align="center">

📫 **Reach out:** [mayankharnotiya25@gmail.com](mailto:mayankharnotiya25@gmail.com) · +91 8700566274

</div>
