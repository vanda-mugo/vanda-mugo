<h1 align="center">Hi, I'm John Mugo (Vanda) 👋</h1>

<p align="center">
  <em>Full-Stack Developer &amp; Systems Architect - building scalable, production-grade distributed systems</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/john-mugo-699466112/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://vanda-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:johnmugo006@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 🚀 About Me

I architect and build production-grade systems with a focus on **scalability**, **reliability**, and **clean design**. My work spans the full spectrum — from event-driven microservices backends and advanced REST APIs to robotics software and responsive frontends.

- 🏗️ Specialized in **microservices architecture**, **event-driven systems**, and **distributed computing**
- ⚙️ Experienced in designing **scalable ERP-class backends** with NestJS, TypeORM, PostgreSQL, and Docker
- 🤖 Proficient in **robotics software** using ROS2, autonomous navigation, and C++/Python control systems
- 📐 Advocate for **Domain-Driven Design**, clean code principles, and rigorous testing

---

## 🏆 Featured Projects

### 🔷 OptimizeERP — Multi-Tenant ERP Backend
> **A comprehensive, production-grade multi-tenant ERP system** built with NestJS, designed to scale to 10,000 tenants with complete data isolation and secure authentication.

**Architecture:** Modular Monolith → Master DB (Auth & Tenancy) + Tenant DB (Business Logic) with row-level isolation

- **Multi-tenant architecture** with two-database logical separation: Master DB for authentication/authorization, Tenant DB for business data
- **Comprehensive RBAC** with granular permissions (`{module}.{resource}.{action}`), role hierarchy, and tenant-scoped access control
- **6 core modules**: Authentication & Authorization, Inventory Management, Sales, Purchases, Accounting, and Reports & Analytics
- **Production-ready infrastructure**: Docker containerized with Nginx reverse proxy, staging/production configs, and monitoring setup
- **Advanced filtering engine** with 13+ operators, nested AND/OR logic groups, and field-level security via custom decorators

**Stack:** `NestJS` `TypeScript` `TypeORM` `PostgreSQL` `Redis` `Docker` `Nginx`

🔗 [View Repository →](https://github.com/vanda-mugo/optimiseERP)

---

### 🔷 OptimizeERP — Mobile Application
> **A React Native Expo mobile client** for the OptimizeERP multi-tenant ERP system, following Clean Architecture with strict TypeScript.

**Architecture:** Clean Architecture — Presentation → Business Logic → Data layers

- **React Native + Expo** with strict TypeScript (no `any`, no `@ts-ignore`) targeting iOS 15+ and Android API 26+
- **Zustand + Immer** for client state, **TanStack Query v5** for server state, and **React Hook Form + Zod** for validated forms
- **Secure multi-tenant auth**: JWT tokens in `expo-secure-store`, automatic refresh on 401, tenant-scoped API requests via `x-tenant-id` header
- **Material Design 3** UI with React Native Paper, custom design system (colors, typography, spacing tokens)
- **Permission-based rendering** with RBAC wildcard support and role-based conditional UI

**Stack:** `React Native` `Expo` `TypeScript` `Zustand` `TanStack Query` `React Navigation v6` `Zod`

🔗 [View Repository →](https://github.com/vanda-mugo/optimizeERP-mobile)

---

### 🔷 NestJS Advanced Filter Backend
> **A type-safe, composable filtering engine** for NestJS + TypeORM applications — the data query layer powering the ERP platform.

- **13 filter operators**: `eq`, `neq`, `gt`, `lt`, `gte`, `lte`, `in`, `between`, `contains`, `starts_with`, `ends_with`, `is_null`, `is_not_null`
- **Nested AND/OR logic groups** for arbitrarily complex queries via a single POST body or GET query string
- **Field-level security** with custom `@Filterable` decorators to prevent unauthorized field access
- Built-in **pagination, sorting**, and full TypeScript generics support
- **69 automated tests** covering unit, integration, and edge-case scenarios
- Fully containerised with **Docker Compose** (app + PostgreSQL); production and development environments separated via `.env` namespacing

**Stack:** `NestJS` `TypeScript` `TypeORM` `PostgreSQL` `Docker` `Jest`

🔗 [View Repository →](https://github.com/vanda-mugo/FilterBackendNestJsProject)

---

### 🔷 TypeScript RDBMS
> **A lightweight relational database engine** implemented from scratch in TypeScript, with SQL support, persistent storage, and dual CLI/web interfaces.

**Stack:** `TypeScript` `SQL` `Node.js`

🔗 [View Repository →](https://github.com/vanda-mugo/RDBMS)

---

### 🔷 ROS2 Robot Navigation Package
> **Autonomous robot navigation system** built on ROS2 Humble with Python and C++ — covering path planning, obstacle avoidance, and sensor integration.

**Stack:** `ROS2` `Python` `C++` `Navigation2`

🔗 [View Repository →](https://github.com/vanda-mugo/Robot_Navigation_pkg)

---

## 🛠️ Tech Stack

### Backend & APIs
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Robotics
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <a href="https://github.com/vanda-mugo">
    <img src="https://github-readme-stats.vercel.app/api?username=vanda-mugo&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  </a>
  <a href="https://github.com/vanda-mugo">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vanda-mugo&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top Languages" height="165"/>
  </a>
</p>

---

## 🎯 Current Focus

| Area | Details |
|---|---|
| 🔥 **ERP Systems** | Expanding microservices with Kafka event streaming and CQRS patterns |
| ☁️ **Cloud-Native** | Kubernetes orchestration, service mesh, and cloud deployment strategies |
| 🤖 **Robotics** | Advanced ROS2 navigation, multi-robot coordination, and sensor fusion |
| 📚 **Learning** | Advanced Kafka stream processing, distributed tracing, and observability |

---

## 📬 Let's Connect

I'm open to collaboration on ambitious backend systems, open-source tooling, or robotics projects.

- 💼 [LinkedIn](https://www.linkedin.com/in/john-mugo-699466112/)
- 🌐 [Portfolio](https://vanda-portfolio.vercel.app/)
- 📧 [johnmugo006@gmail.com](mailto:johnmugo006@gmail.com)

---

<p align="center">
  <em>"First, solve the problem. Then, write the code." — John Johnson</em>
</p>
