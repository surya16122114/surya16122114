# Hi, I'm Chinnasurya Prasad! 👋

🎓 Master's in Computer Software Engineering @ **Northeastern University** (GPA: 3.79/4.0)  
🤖 AI Software Engineer @ **Humanitarians AI** · Ex-Software Engineer @ **UnitedHealth Group (Optum)** (2 yrs)  
📍 Boston, MA  
🔗 **Portfolio:** [chinnasuryaprasad-portfolio-website.vercel.app](https://chinnasuryaprasad-portfolio-website.vercel.app/)  
📬 chinnasuryaprasad2001@gmail.com | [LinkedIn](https://www.linkedin.com/in/chinnasurya-prasad-vulavala-119b5816b/)

---

## 🚀 About Me

I'm a backend-focused software engineer who builds the systems behind AI — RAG platforms, LLM context infrastructure, and distributed caches — plus a fair amount of full-stack and one operating system for fun. I like solving hard problems end to end, from resilient backend APIs and consensus protocols to infrastructure on AWS.

- 🤖 Currently an **AI Software Engineer at Humanitarians AI**, building a production RAG + Mixture-of-Experts education platform integrated into Canvas (LTI 1.3)
- 🌱 Deep in **distributed systems, cloud infrastructure, and applied GenAI**
- 💡 Passionate about clean code, system design, and performance optimization
- 🎯 **Actively seeking full-time Software Engineer / AI Engineer roles for 2026**

---

## 🛠️ Tech Stack

**Languages:**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**AI / ML:**  
![RAG](https://img.shields.io/badge/RAG-6E56CF?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-412991?style=flat&logo=openai&logoColor=white)

**Backend & APIs:**  
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244B5A?style=flat&logo=google&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat&logo=postman&logoColor=white)

**Frontend:**  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)

**Cloud & DevOps:**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

**Databases:**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

---

## 📂 Featured Projects

### 🕸️ [PrefixMesh — Distributed LLM Prefix-Cache Mesh](https://github.com/surya16122114/prefixmesh)
> Go • Paxos • gRPC • Kafka • Consistent Hashing • Prometheus

A distributed prefix-cache mesh for LLM inference — shares computed prefix/KV-cache blocks across a fleet so repeated prompt prefixes skip prefill everywhere. Content-addressed blocks on a consistent-hash ring, a **3-replica Paxos control plane**, RF=2 replication, and a Kafka-driven predictive prefetcher. **85.8% cache-hit rate / 87% prefill compute saved** at steady state; kill a node mid-run and the ring self-heals in **~2s with zero errors** — every failure is a cache miss, never a wrong answer.

---

### 🎙️ [MockLoop — Voice-First AI Mock Interviewer](https://github.com/surya16122114/mockloop)
> Python • Pipecat • LiveKit • WebRTC • Deepgram • Cartesia • Gemini • FastAPI • Next.js

A full-duplex voice interviewer that rings you like a real call — yields when you interrupt and waits while you think (Silero VAD + semantic end-of-turn detection). Uploads your resume into a **claims graph** where every claim gets a bar-raiser probe; a whiteboard and Monaco code editor stream into the live conversation as structured text (zero vision tokens); an evidence-anchored rubric scores each transcript with verbatim quotes. Provider-routed across Gemini / Claude / OpenAI behind one config switch.

---

### 🗜️ [ContextPack — Lossless LLM Context Compression](https://github.com/surya16122114/contextpack)
> Python • FastAPI • OpenAI API • MCP • LangChain

An OpenAI-compatible proxy that losslessly compresses LLM context via a **negotiated session codebook** — the model confirms each abbreviation before it's used, so nothing is lost. Reaches **57–60% token savings at 100% accuracy** on the codebook path, with content-aware compressors and a token-budget optimizer. Usable four ways: HTTP proxy, Python library, CLI, or MCP server.

---

### 🗄️ [Distributed Key-Value Store](https://github.com/surya16122114/distributed-kv-store)
> Java • Paxos • gRPC • Redis • Docker

A fault-tolerant distributed key-value store using the **Paxos consensus algorithm** for strong consistency across replicated nodes, with gRPC for low-latency communication and a Redis-backed hot-read layer — optimizing read/write operations by **~30%**.

---

### 🧬 [Custom OS Kernel (SuryaOS)](https://github.com/surya16122114/SuryaOS)
> x86 Assembly • C • C++

An operating-system kernel built from scratch: a custom x86 Assembly bootloader hands off to a C/C++ kernel with a **process scheduler, paging-based memory management, and a kernel heap**, plus interrupt/I/O handling through OOP-based C++ driver abstractions (VGA, keyboard, timer).

---

### ☁️ [Cloud-Native Infrastructure on AWS](https://github.com/chinnasuryaprasad1612/tf-aws-infra)
> AWS • Terraform • VPC • EC2 • S3 • GitHub Actions

Highly available AWS infrastructure provisioned end-to-end with **Terraform** and auto-scaling, deployed through a **GitHub Actions CI/CD pipeline** — reproducible, infrastructure-as-code from network to instances.

---

## 📫 Let's Connect!

[![Portfolio](https://img.shields.io/badge/Portfolio-6E56CF?style=flat&logo=vercel&logoColor=white)](https://chinnasuryaprasad-portfolio-website.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chinnasurya-prasad-vulavala-119b5816b/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:chinnasuryaprasad2001@gmail.com)
