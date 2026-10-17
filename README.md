# Hi, I'm Prasanna Madiwar 👋

**Backend engineer for AI workloads** · B.Tech AI/ML @ Vishwakarma Institute of Technology, Pune (CGPA 9.33/10)

I build backend services for AI systems: multi-tenant agent APIs, sandboxed code execution, and GPU job orchestration.
I put 350+ automated tests and CI behind my projects and enforce per-user access on every job, thread, and credential route.
I presented GPT-2 training-stability research at **ICST 2026, IIT Patna**.

🎯 **Looking for an SDE internship for Summer 2027.**

[![Portfolio](https://img.shields.io/badge/Portfolio-0f766e?style=flat&logo=vercel&logoColor=white)](https://portfolio-prasanna-seven.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prasanna-madiwar-507462318/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/u/LzLJWzHwdb/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:prasannamadiwar71@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/prasannamadiwar71)

---

## 🚀 Featured Projects

### [NexusLLMFineTuner](https://github.com/PrasannaMadiwar/LLM_FineTuner)
`FastAPI` `Celery` `Redis` `PostgreSQL` `Docker` `GitHub Actions`

- A fine-tuning backend with 36 REST routes, a Celery worker, and a **13-state job state machine**. Per-user JWT checks return 403/404 on every cross-user request.
- A Hugging Face dataset pipeline that previews rows through the Dataset Viewer API without downloading the full dataset. A schema-validated LLM call, cached in PostgreSQL, maps columns to chat format, and 7 validation checks block malformed data.
- A provider-agnostic `GPUProvider` interface with a 7-state lifecycle. A 13-endpoint runtime agent limits GPU pods to 4 approved templates and an allowlist of commands.
- Fine-tuned Qwen2.5-1.5B on 2,000 examples (250 steps, about 6 minutes on a local RTX GPU) and exported a 73.9 MB adapter.
- **329 pytest tests** (73% API coverage, 80% agent coverage) cover every job-state transition using a fake GPU provider. GitHub Actions CI gates merges.

### [NexusAI](https://github.com/PrasannaMadiwar/NexusAI-Central-hub-connecting-tools-and-reasoning) · [Live Demo](https://nexusai-hub.onrender.com)
`FastAPI` `LangGraph` `PostgreSQL` `MongoDB` `Docker` `GitHub Actions`

- A multi-tenant agent backend with 5 FastAPI routers, built on repositories, services, and dependency injection. It orchestrates **4 subagents** (Gmail, Calendar, Meet/Zoom, web search) in LangGraph and checkpoints their state in PostgreSQL.
- Tenants are isolated with JWT auth, PBKDF2-SHA256 password hashing, and an encrypted per-user credential vault on MongoDB Atlas. 7 tenant-isolation tests verify this.
- 23 pytest tests (67% coverage) and a CI coverage gate, plus a `/health` check on PostgreSQL and MongoDB and structured JSON logs with request IDs.

### NexusCode Judge *(in progress)*
`FastAPI` `Docker` `Python` `PostgreSQL` `MongoDB`

- A Python judging pipeline that runs each submission in an isolated Docker container and compares its output with the expected output for each test case. It returns verdicts with error handling, measures runtime, and enforces time and memory limits.

---

## 📄 Research

**"Stabilizing GPT-2 Training via an Additional Post-Normalization Layer"** was presented at ICST 2026, IIT Patna.

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend Services**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=for-the-badge&logo=auth0&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

**Engineering Practices**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0DB7ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**AI Systems**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

**Fundamentals:** OOP · SOLID · Data Structures & Algorithms · DBMS · Operating Systems · Computer Networks

---

## 🧩 Problem Solving

**350+** problems on [LeetCode](https://leetcode.com/u/LzLJWzHwdb/) · **460+** on TakeUForward

[![LeetCode Stats](https://leetcard.jacoblin.cool/LzLJWzHwdb?theme=dark&font=IBM%20Plex%20Mono&ext=heatmap)](https://leetcode.com/u/LzLJWzHwdb/)

---

## 🏆 Achievements & Leadership

- **Research Paper, ICST 2026, IIT Patna:** "Stabilizing GPT-2 Training via an Additional Post-Normalization Layer."
- **President, BIT Student Association:** led 5+ campus activities that engaged 2,000+ students.

---

## 🎓 Education

- **Vishwakarma Institute of Technology, Pune**: B.Tech in AI & ML, CGPA 9.33/10 *(Aug 2025 – Jun 2028, expected)*
- **Ballarpur Institute of Technology**: Diploma in Electronics & Tele-Communication, 94.41% *(Aug 2022 – Jun 2025)*

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=PrasannaMadiwar&theme=transparent&show_icons=true&include_all_commits=true&count_private=false)
![](https://nirzak-streak-stats.vercel.app/?user=PrasannaMadiwar&theme=transparent)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=PrasannaMadiwar&theme=transparent&layout=compact)

[![](https://visitcount.itsvg.in/api?id=PrasannaMadiwar&icon=0&color=0)](https://visitcount.itsvg.in)
