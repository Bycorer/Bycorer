## Hi, I'm Bycorer

Java 后端工程师。日常与 Spring Cloud 微服务、高并发接口和分布式数据一致性打交道，偶尔切到 Vue 写前端。

---

### 🧭 正在做的项目

**[filtrationX](https://github.com/Bycorer/filtrationX)** — 基于 [MXGA](https://github.com/foru17/make-x-great-again) 二开的 X 垃圾号过滤浏览器扩展（Chrome MV3 / TypeScript）

从零负责整条二开链路，几个有代表性的工程点：

- **词库 ↔ GitHub 仓库双向同步**：Contents API 增量合并、冲突策略、OAuth scope 升级与写权限鉴权门禁
- **限速批量动作队列**：多层节流 + 每日配额 + 失败熔断，防平台风控；进度逐条落盘，Service Worker 被回收后可断点续跑
- **X 原生黑名单同步**：只读分页拉取 + 误操作撤销，全部在页面上下文完成，后台只做调度
- **边缘服务端点**：Cloudflare Worker + D1 迁移，复用上游的反滥用与审计链路

### 🛠 技术栈

**后端框架**

![Java](https://img.shields.io/badge/Java-17+-437291?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MyBatis-Plus](https://img.shields.io/badge/MyBatis_Plus-2F74C0?style=flat-square&logo=mybatis&logoColor=white)

**中间件与存储**

![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RocketMQ](https://img.shields.io/badge/RocketMQ-D77310?style=flat-square&logo=apacherocketmq&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Nacos](https://img.shields.io/badge/Nacos-4285F4?style=flat-square&logo=alibabacloud&logoColor=white)
![Sentinel](https://img.shields.io/badge/Sentinel-4CAF50?style=flat-square&logo=sentinel&logoColor=white)
![Seata](https://img.shields.io/badge/Seata-009688?style=flat-square&logo=seata&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**前端与工程化**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FCA121?style=flat-square&logo=gitlab&logoColor=white)

### ⚡ 我在行的事

- 微服务拆分与治理：注册配置中心（Nacos）、分布式事务（Seata）、服务间链路设计
- 高并发接口：缓存体系设计（穿透 / 击穿 / 雪崩防护）、消息削峰（RocketMQ）、限流熔断（Sentinel）
- 检索与数据：Elasticsearch 索引设计与查询优化、MySQL 索引与慢 SQL 治理
- 工程习惯：迁移脚本与审计日志先行、可回滚设计、文档与提交历史保持干净

### 🌱 正在深入

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Netty](https://img.shields.io/badge/Netty-4CAF50?style=flat-square&logo=netty&logoColor=white)
![Vert.x](https://img.shields.io/badge/Vert.x-4B6EAF?style=flat-square&logo=vert.x&logoColor=white)

### 📫 联系我

[X / Twitter](https://x.com/bai3396053528)

---

<img align="left" width="49%" src="https://github-readme-stats.vercel.app/api?username=Bycorer&show_icons=true&hide_border=true&count_private=true" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bycorer&layout=compact&hide_border=true&langs_count=8" />

<img src="https://streak-stats.demolab.com?user=Bycorer&hide_border=true&locale=zh_Hans" width="98%" />