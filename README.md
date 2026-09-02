# Richard Wollyce

**Tech Lead & Full-Stack Software Engineer | AI Systems**

I build the infrastructure other software depends on. My main project is [Ulpia](https://github.com/richard-wollyce/ulpia), an open-source local-first memory and retrieval layer for AI agents written in Rust: RAG where retrieval is plain software with no model in the path, with its evaluation harness published beside it. The rest of my work is commerce: infoproducts, payment flows, and the attribution and conversion systems that report what each launch actually earned.

## Focus Areas

- **AI retrieval & evaluation infrastructure:** RAG for agents with deterministic, offline retrieval; abstention as a real verdict; an evaluation harness (LongMemEval-S, a blind adversarial set) published beside the product.
- **Platform architecture & leadership:** design clear system boundaries, lead delivery, and stay accountable after launch.
- **Commerce & conversion engineering:** Mercado Pago and Pix checkout (Pix is Brazil's instant account-to-account rail), idempotent webhooks, entitlements, attribution, server-side tracking, and revenue reconciliation.
- **Web & mobile products:** responsive web apps, PWAs, and native mobile experiences.
- **Production reliability:** testing, CI/CD, monitoring, incident response, and recovery across managed and self-hosted infrastructure.

## Selected Work

### [Ulpia](https://github.com/richard-wollyce/ulpia) - Local-First AI Memory Infrastructure
**Rust | Apache 2.0 | [ulpia.io](https://ulpia.io)**

A memory and retrieval layer for fleets of AI agents: RAG with no embedding model in the retrieval path, which is what lets it run offline, return the same answer twice, and say that nobody covers a question instead of handing back the least wrong file.

- Two scorers, a keyword index built from the keys each file declares plus SQLite FTS5, fused with Reciprocal Rank Fusion behind a confidence gate.
- Evaluated rather than asserted: 28 of 30 out-of-scope questions declined by the deterministic layer on a blind adversarial set, 0.68 ms p50 warm route latency, and 97 percent on abstention across the 500 questions of LongMemEval-S.
- An MCP server with four read-only tools, so Claude and any other MCP client reads the same base. There is deliberately no write tool a model can reach.
- Privacy derived from git rather than configuration: a file git does not track is a file the system will not serve.
- Roughly 17,000 lines of Rust across three crates, one runtime dependency, over 200 tests, and 36 architecture decision records.

### Casa Seth - Infoproducts, Commerce & Conversion Systems
The house I lead engineering for. It ships digital products and infoproducts, plus the measurement layer underneath them: Mercado Pago and Pix checkout, UTM attribution, server-side conversion tracking, event deduplication, financial reconciliation, and a generative-image pipeline whose failed jobs retry without duplicating paid work.

**[BiblinhaPlay](https://biblinhaplay.com)** is the longest-running product inside it: a cross-platform learning and entertainment subscription serving roughly 500 users across a production web/PWA and an Expo/React Native client, with video streaming, music, printables, interactive games, gamification, entitlement-based access, protected media delivery, and BiblinhaCraft, a custom Three.js voxel experience.

### [RoadToCyberSec.com](https://roadtocybersec.com) - Cybersecurity Learning Hub
A structured learning path covering threat analysis, MFA, safe browsing, incident response, networking fundamentals, and digital evidence handling.

## Experience Highlights

- **Ulpia - Creator & Maintainer** *(August 2026 - Present)*: design and build a local-first AI memory layer in Rust, with its benchmark harness, MCP server, and decision record published in the same repository.
- **Casa Seth - Tech Lead & Software Engineer** *(April 2026 - Present)*: lead architecture and delivery across infoproducts, payments, attribution and conversion systems, and the BiblinhaPlay subscription platform.
- **MG Laser - Software Engineer** *(November 2025 - April 2026)*: built and operated an ERP for inventory, sales, and daily operations; improved data quality, performance, access control, and production recovery.
- **Freelance - Independent Software Engineer** *(2018 - Present)*: deliver full-stack applications, integrations, operational tools, and client-facing systems from discovery through live support; from 2018 to 2025 the same practice also covered IT support and systems work for people and small businesses.
- **Earlier**: IT Support & Operations Assistant at São Joaquim Hospital e Maternidade *(August 2017 - April 2018)*, and Technical Instructor & IT Support Technician at Escola Remington *(April 2015 - April 2016)*.

## Core Technologies

- **Languages:** TypeScript, JavaScript, Rust, SQL; working knowledge of Python and Bash.
- **AI & retrieval:** RAG for AI agents, LLM evaluation (benchmarks, adversarial sets, abstention), local-first memory architecture, deterministic retrieval, SQLite FTS5, Reciprocal Rank Fusion, confidence gating, MCP, benchmark design.
- **Web & mobile:** React, TanStack Start, Next.js, Expo, React Native, Three.js, Vite, Tailwind CSS.
- **Backend & data:** Node.js, PostgreSQL, Supabase, Drizzle ORM, REST APIs, Edge Functions, RLS, RBAC.
- **Commerce & analytics:** Mercado Pago, Pix, hosted checkout, idempotent webhooks, entitlements, attribution, server-side conversion tracking, revenue reconciliation, PostHog.
- **Infrastructure & delivery:** Docker, Linux, Nginx, GitHub Actions, Vercel, EAS, Cargo, Tauri, CI/CD.
- **Quality:** Vitest, Playwright, Maestro, TDD, automated validation, production monitoring.

## Education & Certifications

- **B.Sc. Software Engineering** - Universidade de Franca *(2025 - 2029, in progress)*
- Santander Bootcamp: Rust and AI-Integrated Application Development *(2026)*
- Computational Forensics and Digital Evidence Investigation - Universidade Cruzeiro do Sul *(2026)*
- LEAD1x: Exercising Leadership: Foundational Principles - HarvardX / edX *(2026)*

## Languages

Portuguese (native), English (C1), Spanish (fluent).

## Connect

Based in Franca, Brazil. Open to remote roles across Latin America and to relocation to Santiago, Chile.

[Portfolio](https://richardwollyce.com) | [Curriculum Vitae](https://richardwollyce.com/richard-wollyce-cv.pdf) | [LinkedIn](https://linkedin.com/in/richardwollyce-/) | [GitHub](https://github.com/richard-wollyce) | [Email](mailto:mail@richardwollyce.com)
