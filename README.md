# Daichi Zaha

AI engineer based in Fukuoka, Japan.
Building production AI/LLM systems with Python, GCP, and modern AI tooling —
and engineering the *agent development loop itself* so it stays reliable over
long, semi-autonomous runs.

**🔗 Portfolio → [daichiz-dev.github.io](https://daichiz-dev.github.io/)**

---

## 🛠 Tech Stack

```
AI / LLM       LLM APIs (Claude / GPT / Gemini), RAG, agentic workflows, guardrails
ML / DL        PyTorch, Diffusers, Transformers, XGBoost / LightGBM / SHAP, VLM + Diffusion Policy
Agent dev      Claude Code (custom skills, role-separated subagents, hooks, MCP), Codex
Backend        Python (FastAPI, asyncio, SQLAlchemy), Node.js (ESM)
Frontend       React, Vite, TailwindCSS
Cloud          GCP — Cloud Run, Run Jobs, BigQuery, Scheduler, Secret Manager, Firestore, Vertex
DevOps         GitHub Actions, pre-commit hooks, CI/CD, Docker, launchd
```

---

## 💡 Areas of Focus

- **AI implementation** — turning research-stage LLM ideas into production systems
- **Agent-driven development** — running Claude Code as a built environment (skills / subagents / hooks), separating the generator from the judge, with silent-failure monitoring
- **ML breadth** — data-prep-to-training pipelines, classification & SHAP, diffusion models, and physical AI (VLM + Diffusion Policy robot imitation learning)
- **Production reliability** — pre-deploy gates, integrity tests, and observability for AI pipelines

---

## 📦 Open Source

- **[claude-code-ops-kit](https://github.com/daichiz-dev/claude-code-ops-kit)** — practical operating machinery for running AI coding agents semi-autonomously without silent rot: discipline skills, an assume-broken verifier subagent, a launchd watchdog, and idempotent housekeeping. *MIT.*
- **[fastapi-llm-rag-starter](https://github.com/daichiz-dev/fastapi-llm-rag-starter)** — production-ready FastAPI + RAG starter with pluggable LLM providers (Claude / Gemini), ChromaDB, and offline-runnable tests. *CI green.*
- **[oboegaki](https://github.com/daichiz-dev/oboegaki)** — file-based long-term memory for AI agents: one fact per file with an index, so context survives across sessions (55 tests, MIT)

---

## 📫 Contact

- Location: Fukuoka, Japan (remote) · English working proficiency
