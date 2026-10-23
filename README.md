## Hi, I'm Bycorer

Full-stack engineer. Backend-native (Java / Spring Cloud microservices), fluent across the stack — TypeScript frontends, Go services, cloud-native infra, and LLM-powered features.

---

### 🧭 Current project

**[filtrationX](https://github.com/Bycorer/filtrationX)** — an X (Twitter) spam-filter browser extension based on [MXGA](https://github.com/foru17/make-x-great-again) (Chrome MV3 / TypeScript)

I own the full secondary-development chain. A few representative engineering pieces:

- **Two-way keyword sync with a personal GitHub repo** — Contents API incremental merge, conflict strategy, OAuth scope upgrade, and a write-permission auth gate before anything leaves the device
- **Rate-limited bulk action queue** — multi-layer throttling, daily quotas, and failure circuit-breaking to stay under platform risk control; progress is checkpointed per item and survives Service Worker eviction
- **Native X block-list sync** — read-only paginated pulls plus one-click undo, executed entirely in the page context while the background worker only schedules
- **Edge endpoints** — Cloudflare Worker + D1 migrations, reusing the upstream anti-abuse and audit pipeline

### 🛠 Tech stack

**Languages**

![Java](https://img.shields.io/badge/Java_21-437291?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Backend**

![Spring Boot 3](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MyBatis-Plus](https://img.shields.io/badge/MyBatis_Plus-2F74C0?style=flat-square&logo=mybatis&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white)

**Frontend**

![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)

**Data & middleware**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![RocketMQ](https://img.shields.io/badge/RocketMQ-D77310?style=flat-square&logo=apacherocketmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Nacos](https://img.shields.io/badge/Nacos-4285F4?style=flat-square&logo=alibabacloud&logoColor=white)
![Sentinel](https://img.shields.io/badge/Sentinel-4CAF50?style=flat-square&logo=sentinel&logoColor=white)
![Seata](https://img.shields.io/badge/Seata-009688?style=flat-square&logo=seata&logoColor=white)

**Cloud, DevOps & edge**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FCA121?style=flat-square&logo=gitlab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**AI engineering**

![LLM APIs](https://img.shields.io/badge/LLM_APIs-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square&logo=huggingface&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-000000?style=flat-square&logo=openai&logoColor=white)
![Vector DB](https://img.shields.io/badge/Vector_DB-153150?style=flat-square&logo=qdrant&logoColor=white)

### ⚡ What I bring

- Microservice decomposition and governance: registry & config (Nacos), distributed transactions (Seata), inter-service contract design (REST / gRPC)
- High-throughput APIs: cache architecture (penetration / breakdown / avalanche protection), peak shaving (RocketMQ / Kafka), rate limiting and circuit breaking (Sentinel)
- Search & analytics: Elasticsearch index design and query tuning, ClickHouse for OLAP, MySQL indexing and slow-query remediation
- Cloud-native delivery: Docker images, Kubernetes workloads, CI/CD pipelines (GitHub Actions / GitLab CI), edge functions on Cloudflare Workers
- AI-native features: LLM API orchestration, RAG pipelines with vector stores, prompt engineering for production workloads

### 🌱 Exploring

![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-3B82F6?style=flat-square&logo=linux&logoColor=white)

### 📫 Reach me

[X / Twitter](https://x.com/bai3396053528)

---

<img align="left" width="49%" src="https://github-readme-stats.vercel.app/api?username=Bycorer&show_icons=true&hide_border=true&count_private=true" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bycorer&layout=compact&hide_border=true&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=Bycorer&hide_border=true" width="98%" />
