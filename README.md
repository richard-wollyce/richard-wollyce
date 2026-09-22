# Richard Wollyce

**Tech Lead & Full-Stack Software Engineer | AI Systems**

I build the infrastructure other software depends on. My main project is [Ulpia](https://github.com/richard-wollyce/ulpia), an open-source local-first memory and retrieval layer for AI agents written in Rust — RAG with no model in the retrieval path, with its evaluation harness published alongside it. The rest of my work is commerce: infoproducts, payment flows, and the attribution systems that report what each launch actually earned.

## Focus Areas

- **AI retrieval & evaluation:** deterministic, offline RAG for agents; abstention as a real verdict; benchmark harness published with the product.
- **Platform architecture & leadership:** clear system boundaries, end-to-end delivery accountability.
- **Commerce & conversion:** Mercado Pago, Pix checkout, idempotent webhooks, entitlements, attribution, server-side tracking, revenue reconciliation.
- **Web & mobile:** responsive apps, PWAs, native mobile.
- **Production reliability:** testing, CI/CD, monitoring, incident response.

## Selected Work

### [Ulpia](https://github.com/richard-wollyce/ulpia) — Local-First AI Memory Infrastructure
**Rust | Apache 2.0 | [ulpia.io](https://ulpia.io)**

Memory and retrieval layer for AI agent fleets: keyword index (SQLite FTS5) fused with Reciprocal Rank Fusion behind a confidence gate, no embedding model at query time.

- 28/30 out-of-scope questions declined on a blind adversarial set; 97% abstention on LongMemEval-S; 0.68 ms p50 warm latency.
- MCP server with four read-only tools; no write tool a model can reach.
- Privacy from git: untracked files are never served.
- ~17,000 lines of Rust, one runtime dependency, 200+ tests, 36 architecture decision records.

### Casa Seth — Infoproducts, Commerce & Conversion
Engineering lead for a house that ships digital products: Mercado Pago/Pix checkout, UTM attribution, server-side event tracking, deduplication, and revenue reconciliation.

**[BiblinhaPlay](https://biblinhaplay.com)** — cross-platform subscription (~500 users) with video, music, games, gamification, and BiblinhaCraft, a custom Three.js voxel experience.

### [RoadToCyberSec.com](https://roadtocybersec.com) — Cybersecurity Learning Hub
Structured learning path covering threat analysis, MFA, networking, incident response, and digital forensics.

## Experience

- **Ulpia — Creator & Maintainer** *(Aug 2026 – Present)*: local-first AI memory layer in Rust with benchmark harness, MCP server, and full decision record.
- **Casa Seth — Tech Lead & Software Engineer** *(Apr 2026 – Present)*: architecture and delivery across payments, attribution, and BiblinhaPlay.
- **MG Laser — Software Engineer** *(Nov 2025 – Apr 2026)*: ERP for inventory and sales; improved data quality, performance, and access control.
- **Freelance — Independent Software Engineer** *(2018 – Present)*: full-stack apps, integrations, and operational tools from discovery through live support.
- **Earlier:** IT Support at São Joaquim Hospital *(2017–2018)* and Technical Instructor at Escola Remington *(2015–2016)*.

## Core Technologies

- **Languages:** TypeScript, JavaScript, Rust, SQL; Python, Bash.
- **AI & retrieval:** RAG, LLM evaluation, deterministic retrieval, SQLite FTS5, RRF, MCP.
- **Web & mobile:** React, TanStack Start, Next.js, Expo, React Native, Three.js, Tailwind CSS.
- **Backend & data:** Node.js, PostgreSQL, Supabase, Drizzle ORM, REST, Edge Functions, RLS, RBAC.
- **Commerce:** Mercado Pago, Pix, webhooks, entitlements, attribution, PostHog.
- **Infrastructure:** Docker, Linux, Nginx, GitHub Actions, Vercel, EAS, CI/CD.
- **Quality:** Vitest, Playwright, Maestro, TDD.

## Education & Certifications

- **B.Sc. Software Engineering** — Universidade de Franca *(2025–2029, in progress)*
- Santander Bootcamp: Rust and AI-Integrated Application Development *(2026)*
- Computational Forensics and Digital Evidence Investigation — Universidade Cruzeiro do Sul *(2026)*
- LEAD1x: Exercising Leadership — HarvardX / edX *(2026)*

## Languages

Portuguese (native) · English (C1) · Spanish (fluent)

## Connect

Based in Franca, Brazil. Open to remote roles across Latin America and relocation to Santiago, Chile.

[Portfolio](https://richardwollyce.com) | [CV](https://richardwollyce.com/richard-wollyce-cv.pdf) | [LinkedIn](https://linkedin.com/in/richardwollyce-/) | [GitHub](https://github.com/richard-wollyce) | [Email](mailto:mail@richardwollyce.com)
