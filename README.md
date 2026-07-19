<div align="center">
  <h1>
    Hey, I'm Wolffy
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28" />
  </h1>
  <h3>后端开发者 · 分布式系统爱好者 · AI 编程实践者</h3>

  <p>
    <a href="https://codewolffy.github.io/"><img src="https://img.shields.io/badge/博客-狼码纪-FF6B35?style=for-the-badge&logo=hexo&logoColor=white" /></a>
    <a href="https://github.com/CodeWolffy"><img src="https://img.shields.io/badge/GitHub-CodeWolffy-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  </p>
</div>

---

### 👨‍💻 About Me

- 🎓 软件工程专业，2026 年毕业
- ✍️ 在 **https://codewolffy.github.io/** 写技术博客，记录工程踩坑与深度思考
- 🤖 AI 编程重度用户，相信 AI 是开发者的外挂而非替代

---

### 🛠️ Tech Stack

**Backend & Middleware**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![MyBatis Plus](https://img.shields.io/badge/MyBatis%20Plus-FF6B35?style=flat&logo=mybatis&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat&logo=hibernate&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![RocketMQ](https://img.shields.io/badge/RocketMQ-D77310?style=flat&logo=apache&logoColor=white)
![Sa-Token](https://img.shields.io/badge/Sa--Token-0088FF?style=flat&logo=auth0&logoColor=white)


**Frontend**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)
![Element Plus](https://img.shields.io/badge/Element_Plus-409EFF?style=flat&logo=element&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-FF5D01?style=flat&logo=astro&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vben Admin](https://img.shields.io/badge/Vben%20Admin-646CFF?style=flat&logo=vite&logoColor=white)

**DevOps & Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

### 📌 Featured Projects

#### [CodeWolffy/papercheck](https://github.com/CodeWolffy/papercheck) — 自建库论文查重系统

前后端分离的自建库论文查重平台，适用于高校毕业论文校内互检场景。

- 🧠 **9 种检测算法**：连续文本匹配、指纹索引、同义词归一化、语义向量检测等
- 🔐 **完善权限体系**：JWT 鉴权、角色管理、日配额限制、登录失败限流
- 📊 **可视化报告**：左右对照原文与库内来源，红色高亮重复片段，支持 PDF 导出
- 🤖 **AI 降重指南**：提供自查清单与一键复制的 AI 降重提示词
- 🏗️ **技术栈**：Python / FastAPI + Vue 3 / Element Plus + MySQL + sentence-transformers

#### [CodeWolffy/enterprise-auth-platform](https://github.com/CodeWolffy/enterprise-auth-platform) — 企业级管理后台基座

用于快速孵化企业管理后台的通用底座，内置认证、RBAC、多租户、组织架构、系统管理、日志、通知、文件、工作流、代码生成等横向能力。

- 🔐 **认证与安全**：账号密码登录、滑块验证码、登录风控、会话管理与强制下线
- 🏢 **组织与权限**：RBAC + 菜单权限 + 按钮权限码，多租户隔离与租户套餐
- 🛠️ **效率工具**：代码生成、轻量审批流、文件存储（MinIO/S3/本地）、站内通知 SSE
- 📐 **工程规范**：四层架构（interfaces/application/domain/infrastructure）+ ArchUnit 模块边界守护
- 🏗️ **技术栈**：Java 17 / Spring Boot 3.5 + Sa-Token / MyBatis-Plus / Redis / Redisson + Vue 3 / Vben Admin v5

#### [CodeWolffy/str-reservation](https://github.com/CodeWolffy/str-reservation) — 学习空间预约管理系统

基于 Spring Boot + Vue 3 的现代化学习空间预约管理平台，专为高校、图书馆、自习室等场景设计。

- 🪑 **可视化座位布局**：自定义行列布局、拖拽式操作、实时座位状态
- ⏰ **完整预约生命周期**：待审批 → 待签到 → 已签到 → 已完成/缺席/违规，自动签退与缺席检测
- 🐇 **RabbitMQ 延迟队列**：预约到期自动签退、超时未签到自动标记缺席
- 🔔 **实时消息通知**：WebSocket 推送预约状态变更、签到提醒、违约警告
- 📊 **数据可视化**：ECharts 展示空间使用率、热门时段、预约趋势
- 🏗️ **技术栈**：Java 17 / Spring Boot 2.7 + MyBatis-Plus / Druid / JWT / RabbitMQ / WebSocket + Vue 3 / Pinia / Element Plus

#### [CodeWolffy/codewolffy.github.io](https://github.com/CodeWolffy/codewolffy.github.io) — 狼码纪技术博客

基于 Astro + React + Tailwind CSS 构建的现代个人技术博客。

- ⚡ Astro 静态生成，暗色模式无闪烁
- 🔍 集成 Pagefind 全文搜索，支持中文分词
- 💬 Giscus 评论系统、RSS 订阅、音乐播放器
- 🎨 玻璃拟态视觉设计与响应式布局

---

### 📝 Recent Blog Posts

<!-- BLOG-POST-LIST:START -->
- [本地消息表、事务消息与 Outbox 工程实现](https://codewolffy.github.io/blog/45-database-message-eventual-consistency/)
- [跨分片分页与分布式 ID 方案](https://codewolffy.github.io/blog/44-sharding-pagination-sorting-id/)
- [动态刷新中的半新半旧、集群版本漂移](https://codewolffy.github.io/blog/spring-config-dynamic-refresh-consistency/)
- [调度与执行分离、租约、fencing token](https://codewolffy.github.io/blog/78-horizontally-scalable-scheduled-job-system/)
- [JOIN FETCH、EntityGraph、DTO 投影](https://codewolffy.github.io/blog/43-hibernate-n-plus-one/)
<!-- BLOG-POST-LIST:END -->

→ [更多文章](https://codewolffy.github.io/archives/)

---

### 📊 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=CodeWolffy&show_icons=true&theme=vue&hide_title=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CodeWolffy&layout=compact&theme=vue&hide_title=true" />
</div>

---

### 🌐 Find Me

[![Blog](https://img.shields.io/badge/🐺%20狼码纪-FF6B35?style=flat-square&logo=hexo&logoColor=white)](https://codewolffy.github.io/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/CodeWolffy)
[![Bilibili](https://img.shields.io/badge/Bilibili-00A1D6?style=flat-square&logo=bilibili&logoColor=white)](https://b23.tv/CWW8udk)
[![Juejin](https://img.shields.io/badge/掘金-007FFF?style=flat-square&logo=juejin&logoColor=white)](https://juejin.cn/user/407261374331431)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/codewolffy)
[![Douyin](https://img.shields.io/badge/抖音-000000?style=flat-square&logo=tiktok&logoColor=white)](https://v.douyin.com/npIXkasyEdE)

---

<div align="center">
  <sub>
    <i>代码会过期，但思考不会。&ensp;—&ensp;</i>
    <a href="https://codewolffy.github.io/">狼码纪</a>
  </sub>
</div>



<!--
**CodeWolffy/CodeWolffy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
