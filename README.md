<!-- 
## 👋 Hi, I’m @quannhq

🌍 **Remote Full-Stack Developer (Vietnam-based)**  
💻 Building modern, scalable web apps with **TypeScript**, **Node.js (NestJS/Express)**, and **React/Next.js**  
🧠 Passionate about **backend architecture**, **database design (PostgreSQL, Prisma)**, and **clean code**  
🚀 Exploring **microservices**, **AWS Cloud**, and **CI/CD pipelines** for production-grade systems  
🌱 Currently completing ** Web Developer** program — hands-on, project-based, and English-driven  
🎯 Goal: Become a world-class remote engineer building global SaaS products

---

### 🛠️ Tech Stack

| Languages | Frontend | Backend | Database (SQL) | Database (NoSQL) | DevOps |
|------------|-----------|----------|----------------|------------------|---------|
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=000) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=fff) | ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=000) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=fff) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=fff) | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=fff) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=fff) ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=fff) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=fff) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=fff) | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=fff) | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=fff) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=fff) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=fff) |

### 🚧 Planned & In-Progress Projects

| Project | Description | Status |
|----------|--------------|---------|
| **Task Manager API** | RESTful API for task management with JWT Auth & PostgreSQL | 🧱 In progress (designing DB schema) |
| **E-Commerce Backend** | Payment, upload, and product management system | 💡 Planned (research phase) |
| **Realtime Chat App** | Socket.io-based chat with Redis pub/sub | 💡 Planned (concept validation) |
| **SaaS Capstone** | Remote-ready backend with microservices and API Gateway | 🚀 Coming soon |

### 📫 Contact Me

- 🌐 Portfolio:  ** — update when ready **
- 💼 LinkedIn:  [linkedin.com/in/quannhq](https://linkedin.com/in/quanngh)  
- 📧 Email: **nguyenhoangquan.contact@gmail.com**  
- 🧑‍💻 GitHub: [github.com/quannhq](https://github.com/quannhq)

---

> “No bugs left unresolved. No code left untested. No learning without building.”  
> — quannhq

-->
# 👋 Hi, I’m @quannhq  
**Backend Engineer (Node.js/TypeScript) — Architecture • Systems • Databases**

I focus on building backend systems that are **predictable**, **scalable**, and **maintainable**.  
Long-term, I’m developing into a **Full-Stack Product Engineer** with strong backend roots.

---

# 🧠 Core Engineering Focus
- Backend architecture (clean, layered, modular monolith → services)
- API design (REST, versioning, auth, rate limiting)
- PostgreSQL schema design, indexing, query plans
- Distributed components: caching, pub/sub, workers
- Production workflows: Docker, CI/CD, cloud
- System Design fundamentals

---

# ⚙️ Technical Skillset

### **Backend Core**
- **Node.js** (NestJS, Express)
- **TypeScript** (strict, clean patterns)
- **PostgreSQL** (indexes, transactions, EXPLAIN)
- **Prisma ORM**
- **Redis** (pub/sub, caching)
- Queues • Background jobs • Logging/metrics

### **Frontend (Fullstack Long-Term Path)**
- React
- Next.js (App Router, SSR/RSC)
- TailwindCSS
- Zustand

### **DevOps & Cloud (Remote-Ready Essentials)**
- Docker • Docker Compose
- GitHub Actions (CI/CD pipelines)
- AWS (EC2, S3, CloudFront)
- Railway / Render (prototyping deployment)

---

# 🏗 System Architecture Diagrams  
*(FAANG style — minimal, technical, focused on flows & components)*

## **1. Task Manager API — Clean Backend Architecture**

```
                  ┌───────────────────────┐
                  │       Client/App       │
                  └────────────┬───────────┘
                               │  REST
                               ▼
                   ┌────────────────────────┐
                   │    API Layer (Node)    │
                   └──────┬────────┬────────┘
                          │        │
                Validation│        │Auth/JWT
                          ▼        ▼
               ┌────────────────────────┐
               │   Application Layer     │
               └──────┬────────┬────────┘
                      │        │
               Services│        │Domain Logic
                      ▼        ▼
        ┌────────────────────────────┐
        │ PostgreSQL (Prisma ORM)    │
        └────────────────────────────┘
                      │
                      ▼
           ┌─────────────────────┐
           │ Redis (Cache/Queue) │
           └─────────────────────┘
```

---

## **2. Realtime Chat App — Pub/Sub Architecture**

```
Client → Socket.io Gateway → Node Server  
                           ↘ Redis Pub/Sub  
```

---

## **3. SaaS Backend — API Gateway + Services**

```
                   Client/Frontend
                          │
                          ▼
                    API Gateway
        ┌───────────────┼────────────────┐
        ▼               ▼                ▼
 Authentication   User Service     Billing Service
        │               │                │
        └───────────────┴────────────────┘
                        ▼
                 PostgreSQL (RLS)
```

---

# 🚀 Backend Projects (Primary Track)

| Project | Description | Status |
|--------|-------------|--------|
| **Task Manager API** | Clean backend: PostgreSQL, Prisma, JWT, RBAC, caching | 🏗 In progress |
| **E-Commerce Backend** | Product catalog, uploads, filters, admin logic | 💡 Research |
| **Realtime Chat** | Socket.io + Redis pub/sub | 💬 Planned |
| **SaaS Backend Capstone** | API gateway, services, rate limiting, logging | 🚀 Coming soon |

---

# 🌐 Fullstack Expansion (Long-Term)
- Multi-tenant SaaS architecture (orgs, roles, teams)
- Next.js RSC + server actions
- Dashboard systems, metrics, audit logs
- Fullstack DX: caching layers, edge rendering

---

# 🎯 Medium-Term Remote Backend Roadmap
- Strengthen Node.js performance patterns
- Master PostgreSQL (indexes, EXPLAIN, optimization)
- Learn distributed backend components properly
- Improve system design (load balancing, queues, caching)
- Build stable CI/CD pipelines for deployments
- Develop remote-ready coding/documentation habits

---

# 🌱 Long-Term Fullstack Engineering Goals
- Deep understanding of Next.js internals (RSC, streaming)
- Build production-grade SaaS UIs (admin dashboards, analytics)
- Strong product mindset: simplicity → iteration → scale
- Architecture thinking from backend → frontend → infra

---

# 🔧 What I'm Improving Right Now
- Rate limiting, caching strategies, pub/sub patterns  
- Transaction boundaries, DB consistency  
- Scalable folder structure for backend services  
- CI/CD automation  
- Next.js server components + caching  

---

# 📫 Contact  
LinkedIn: https://linkedin.com/in/quanngh  
Email: **nguyenhoangquan.contact@gmail.com**  
GitHub: https://github.com/quannhq  
Portfolio: *(coming soon)*

---

> “Backend first. Architecture always. Fullstack eventually.”  
> — **quannhq**


