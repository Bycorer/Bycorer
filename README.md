## Hi, I'm Bycorer

Java backend engineer. I spend most of my time on Spring Cloud microservices, high-throughput APIs, and distributed data consistency — and I switch to Vue when a frontend needs shipping.

---

### 🧭 Current project

**[filtrationX](https://github.com/Bycorer/filtrationX)** — an X (Twitter) spam-filter browser extension based on [MXGA](https://github.com/foru17/make-x-great-again) (Chrome MV3 / TypeScript)

I own the full secondary-development chain. A few representative engineering pieces:

- **Two-way keyword sync with a personal GitHub repo** — Contents API incremental merge, conflict strategy, OAuth scope upgrade, and a write-permission auth gate before anything leaves the device
- **Rate-limited bulk action queue** — multi-layer throttling, daily quotas, and failure circuit-breaking to stay under platform risk control; progress is checkpointed per item and survives Service Worker eviction
- **Native X block-list sync** — read-only paginated pulls plus one-click undo, executed entirely in the page context while the background worker only schedules
- **Edge endpoints** — Cloudflare Worker + D1 migrations, reusing the upstream anti-abuse and audit pipeline

### 🛠 Tech stack

**Backend**

![Java](https://img.shields.io/badge/Java-17+-437291?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MyBatis-Plus](https://img.shields.io/badge/MyBatis_Plus-2F74C0?style=flat-square&logo=mybatis&logoColor=white)

**Middleware & storage**

![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RocketMQ](https://img.shields.io/badge/RocketMQ-D77310?style=flat-square&logo=apacherocketmq&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Nacos](https://img.shields.io/badge/Nacos-4285F4?style=flat-square&logo=alibabacloud&logoColor=white)
![Sentinel](https://img.shields.io/badge/Sentinel-4CAF50?style=flat-square&logo=sentinel&logoColor=white)
![Seata](https://img.shields.io/badge/Seata-009688?style=flat-square&logo=seata&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Frontend & tooling**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FCA121?style=flat-square&logo=gitlab&logoColor=white)

### ⚡ What I'm good at

- Microservice decomposition and governance: service registry & config (Nacos), distributed transactions (Seata), inter-service contract design
- High-throughput APIs: cache architecture (penetration / breakdown / avalanche protection), peak shaving with RocketMQ, rate limiting and circuit breaking with Sentinel
- Search & data: Elasticsearch index design and query tuning, MySQL indexing and slow-query remediation
- Engineering habits: migrations and audit logs before features, reversible designs, clean commit history

### 🌱 Currently learning

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Netty](https://img.shields.io/badge/Netty-4CAF50?style=flat-square&logo=netty&logoColor=white)
![Vert.x](https://img.shields.io/badge/Vert.x-4B6EAF?style=flat-square&logo=vert.x&logoColor=white)

### 📫 Reach me

[X / Twitter](https://x.com/bai3396053528)

---

<img align="left" width="49%" src="https://github-readme-stats.vercel.app/api?username=Bycorer&show_icons=true&hide_border=true&count_private=true" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bycorer&layout=compact&hide_border=true&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=Bycorer&hide_border=true" width="98%" />