# Richard Wollyce

**Software Engineer & Architect | AI Memory & Sovereign Systems**

I build high-performance, local-first software and deterministic memory infrastructure for autonomous systems. My work focuses on eliminating hallucinations in AI systems by replacing opaque vector embeddings with auditable, zero-latency retrieval, and leveraging that foundation to build intelligent, sovereign educational tools.

---

## 🧠 AI Memory & AI Tutor

My primary architectural focus is the intersection of **deterministic memory retrieval** and **active pedagogical AI systems**:

### [Ulpia](https://github.com/richard-wollyce/ulpia) — Local-First AI Memory Infrastructure *(Public Open-Source)*
**Rust | Apache 2.0 | [ulpia.io](https://ulpia.io)**

An open-source, local-first memory and retrieval layer for AI agent fleets.
- **Zero embeddings at query time:** Exact SQLite FTS5 (BM25) fused with Reciprocal Rank Fusion (RRF) behind an explicit confidence verdict gate (`Hit`, `Guess`, `Nothing`).
- **Verifiable abstention:** Declines out-of-scope queries (97% abstention on LongMemEval-S; 0.68 ms p50 warm latency).
- **Safe agent tooling:** MCP server with strict read-only tools and zero write-surface accessible to models.
- **Sovereign & lightweight:** ~17,000 lines of idiomatic Rust, single runtime dependency, 200+ unit tests, 36 Architecture Decision Records.

### Wollyce AI Tutor — Sovereign Socratic Learning System *(Private • Open-Source Release Coming Soon)*
**Built on Ulpia & Rust**

A personal preceptor and learning engine designed to actively educate users on their own ingested material.
- **Active Recall & Socratic Inquiry:** Rather than generating passive answers, it interrogates, challenges, and guides the student using pedagogical frameworks (Feynman Technique, Pólya, and Socratic Dialectic).
- **100% Local Inference:** Engineered to run local sovereign models (DeepSeek R1 via `llama.cpp` / `llama-server`) with integrated thinking-trace parsing, zero cloud reliance, and intelligent idle power management.
- **Deterministic Knowledge:** Ulpia serves as the underlying memory backbone, ensuring the tutor grounds all questions exclusively in the user's authentic notes and books.

---

## 🛠️ Focus Areas

- **AI Memory & Retrieval:** Deterministic RAG, hybrid keyword-rank fusion, confidence evaluation harnesses, MCP protocol.
- **Sovereign & Local AI:** Offline execution, `llama.cpp` integration, DeepSeek R1 reasoning extraction, battery/resource lifecycle management.
- **Systems Architecture:** Clear component boundaries, type-level invariants in Rust, resilient multi-agent orchestration.
- **Modern Full-Stack Interfaces:** Responsive, ultra-clean web & mobile interfaces focused on clarity and ergonomic interaction.

---

## 💻 Core Technologies

- **Languages:** Rust, TypeScript, JavaScript, SQL, Bash.
- **AI & Systems:** Deterministic RAG, Local LLMs, `llama-server`, SQLite FTS5, BM25, RRF, MCP, Evaluation Harnesses.
- **Backend & Data:** Rust, Node.js, PostgreSQL, SQLite, Drizzle ORM, REST, WebSockets, SSE.
- **Frontend & Mobile:** React, Next.js, Tauri v2, Tailwind CSS, Modern Web Standards.
- **DevOps & Tooling:** Docker, Linux, Git, GitHub Actions, CI/CD, Benchmarking.

---

## 🌐 Languages

- Portuguese (Native)
- English (Fluent / C1)
- Spanish (Fluent)

---

## 📬 Connect

Based in Franca, Brazil. Open to engineering leadership, systems architecture, and specialized AI infrastructure roles.

[Portfolio](https://richardwollyce.com) · [CV](https://richardwollyce.com/richard-wollyce-cv.pdf) · [LinkedIn](https://linkedin.com/in/richardwollyce-/) · [GitHub](https://github.com/richard-wollyce) · [Email](mailto:mail@richardwollyce.com)
