# 🌐 NewsMemoryOKF & Living Knowledge Portal

[![GitHub Pages Live](https://img.shields.io/badge/GitHub%20Pages-Live%20Portal-brightgreen?style=for-the-badge&logo=github)](https://rajramakalai.github.io/hello-world/)
[![Entity Dossier](https://img.shields.io/badge/Entity-NVIDIA-76b900?style=for-the-badge&logo=nvidia)](https://rajramakalai.github.io/hello-world/)
[![Specification](https://img.shields.io/badge/Standard-Living%20OKF%20v1.0-blue?style=for-the-badge)](./LIVING_OKF_SPECIFICATION.md)
[![Origin](https://img.shields.io/badge/Cloud-Raj%20AI%20Cloud-purple?style=for-the-badge)](https://raj-ai.duckdns.org/news/)

Welcome to the public gateway for **NewsMemoryOKF**, the 24/7 autonomous living intelligence memory desk running on Raj AI Cloud (Oracle Cloud ARM VM).

> 🚀 **Live Interactive Web Portal:** [**https://rajramakalai.github.io/hello-world/**](https://rajramakalai.github.io/hello-world/)

---

## 📌 Portal Features

This repository powers a multi-tab GitHub Pages portal:

1. **📰 Live Cloud News Feed (`<iframe>` Portal):**
   - Direct embedded window into [`https://raj-ai.duckdns.org/news/`](https://raj-ai.duckdns.org/news/).
   - Governed by **CloudAuth IAM**: administrators can toggle public access or require Google OAuth Single Sign-On (SSO).
   - Features 1-click external launch and frame reload controls.

2. **⚡ NVIDIA Living OKF Wiki (Sample Page):**
   - Standalone, 100% self-contained production HTML page representing the canonical Object Knowledge Format (OKF) living dossier for **NVIDIA Corporation** ([`https://raj-ai.duckdns.org/news/wiki/nvidia`](https://raj-ai.duckdns.org/news/wiki/nvidia)).
   - Fully interactive offline with Bootstrap 5 dark theme, knowledge graph connections, audit changelog table, and metadata cards.

3. **🧠 Living OKF Specification (For Peer Agents):**
   - Comprehensive technical design specification in [`LIVING_OKF_SPECIFICATION.md`](./LIVING_OKF_SPECIFICATION.md) for any autonomous AI agent to implement the Dual-Layer Living Memory pattern.

---

## 📄 Living OKF Specification for AI Agents

For developers and autonomous AI agents looking to reference and implement the Living Memory Architecture:
👉 **[Read the Full Living OKF Specification (v1.0.0)](./LIVING_OKF_SPECIFICATION.md)**

### Architecture Highlights:
- **Dual-Layer Memory:** Layer 1 Episodic Memory (transient 90-day TTL in SQLite + FTS5) $	o$ Layer 2 Semantic Living Memory (permanent `.okf.md` files).
- **Sleep-Cycle Consolidation:** Autonomous agents reconcile new events every 6 hours, resolve contradictions, and rewrite the ~200-word executive essence.
- **Bi-Directional WikiLinks:** Interconnects entities and topics using `[[Target]]` syntax.
- **Audit Provenance:** Every update increments semantic versioning and appends an immutable changelog row with the authoring agent's ID.

---

## 📂 Repository File Index

| File | Purpose |
| :--- | :--- |
| [`index.html`](./index.html) | Interactive GitHub Pages portal with iframe cloud embed, NVIDIA sample, and spec reader. |
| [`LIVING_OKF_SPECIFICATION.md`](./LIVING_OKF_SPECIFICATION.md) | Full architectural standard & Python reference implementation for AI agents. |
| [`nvidia.okf.md`](./nvidia.okf.md) | Canonical raw Object Knowledge Format (OKF) markdown dossier with YAML frontmatter. |
| [`README.md`](./README.md) | Repository overview and documentation hub. |
