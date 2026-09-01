# Hi, I'm Winston Koh 👋

*Last updated: 2 September 2026* <!-- 2026-09-02 -->

**AI Systems Engineer** | Creator of [Project Athena](https://github.com/winstonkoh87/Athena-Public) | Singapore 🇸🇬

I build **agentic PKM** infrastructure — local-first systems that give any LLM persistent memory and your context, so it helps you decide rather than starting cold every time. **Own the state, rent the intelligence.**

**Website:** [winstonkoh87.com](https://winstonkoh87.com)

---

## 🎯 What I Build

<table>
<tr>
<th width="20%">Project</th>
<th width="35%">What It Does</th>
<th width="45%">Engineering Highlights</th>
</tr>
<tr>
<td><strong><a href="https://github.com/winstonkoh87/Athena-Public">Athena</a></strong></td>
<td>Open-source local-first agentic PKM — persistent memory, structured reasoning, and governed AI agents that work across any LLM (Gemini, Claude, GPT). Full data ownership.</td>
<td>
• Chunk-level hybrid RAG (BM25 + semantic + RRF fusion + cross-encoder rerank)<br>
• Hit@5 0.892 / MRR@5 0.769 on a 65-query gold set, @ $0 infra (Supabase free tier)<br>
• 452 reusable protocols (418 active), 74 slash commands, 43 skills<br>
• Conditional skill activation (~40-60% token savings)<br>
• 1M+ Reddit views + 960+ unique cloners at launch<br>
• 7 IDE integrations, MIT licensed
</td>
</tr>
<tr>
<td><strong><a href="https://winstonkoh87.com">Portfolio</a></strong></td>
<td>11-page performance-first portfolio with 26 articles and 6 live demos</td>
<td>
• Astro 5.0 + Tailwind CSS (zero-JS islands)<br>
• Zero-JS-first architecture, 99/100 Lighthouse
</td>
</tr>
</table>

---

## 🧠 Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**AI & Data**

![Gemini](https://img.shields.io/badge/Gemini-886FBF?style=flat&logo=google&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-CC785C?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)

**Tools & Infrastructure**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

---

## 📊 Athena v9.9.9 — By the Numbers

> *A local-first agentic PKM that helps you make better decisions with your own context. Own the state. Rent the intelligence.*

| Metric | Value | What It Means |
|:---|:---|:---|
| **Sessions** | **2,100+** | Continuous context across 200+ days of bilateral use |
| **Protocols** | **452 (418 active)** | Open-sourced decision frameworks across 26 categories (reasoning, risk, execution, research) |
| **Hybrid RAG** | **Hit@5 0.892** | Chunk-level BM25 + semantic + RRF fusion + cross-encoder rerank — MRR@5 0.769, coverage 0.639, [measured](https://github.com/winstonkoh87/Athena-Public/blob/main/docs/BENCHMARKS.md) on a 65-query gold set |
| **Skills** | **43 active** | Cognitive Cluster architecture — 43 active (17 archived) with conditional activation |
| **Workflows** | **74 commands** | Slash triggers: 55 root + 19 domain-tier workflows |
| **Automation** | **269 scripts** | Python automation stack (boot, shutdown, search, sync, hooks, governance) |
| **Memory Corpus** | **4,386 files** | Grounded episodic and semantic knowledge corpus |
| **Launch Reach** | **1M+ views** | Reddit launch post — 960+ unique cloners, 4.5K+ unique visitors |

**Key Engineering:**

- **Hybrid Search**: pgvector + BM25 keyword + RRF fusion + cross-encoder rerank — Hit@5 0.892 / MRR@5 0.769 on a published 65-query gold set, hardened through logged production regressions
- **Conditional Skill Activation**: Path/topic-triggered dormant skills reduce prompt bloat by ~40-60% (Protocol 530)
- **Epistemic Honesty as a Feature**: public [Validation Status](https://github.com/winstonkoh87/Athena-Public#-validation-status--whats-proven-vs-whats-proposed) ladder grades every claim by evidence level; 18 Crossref-verified academic references ([APA list](https://github.com/winstonkoh87/Athena-Public/blob/main/docs/REFERENCES.md)); mechanisms labeled code-enforced vs agent-discretion
- **Guards That Can Actually Fail** ([v9.9.8](https://github.com/winstonkoh87/Athena-Public/releases/tag/v9.9.8)): an audit found five green checks that could not detect the defect they named — a CI step running the writer instead of the check, a version check scoped to the three files that already agreed, `ruff --exit-zero`, tests asserting a return *type* instead of a behaviour, and a privacy scanner excluding its own config. Standing rule now: any fix to a guard must show it failing before it shows it passing, mutation-tested and recorded in the commit
- **Multi-Agent Orchestration**: Coordinator synthesis discipline with anti-delegation enforcement and token budgeting
- **Atomic Writes**: POSIX-compliant data safety for all memory operations
- **Privacy Pipeline**: CI privacy gate over 41 patterns, with the committed blocklist restricted to shape-only matchers — a public blocklist that names people is an index of what you're hiding, so name patterns live in a repo secret and the scanner audits its own config
- **Semantic Cache**: LRU with disk persistence, cosine matching, and Supabase delta sync
- **Zero Infrastructure Cost**: Runs on Supabase free tier + local compute. No cloud bills.

---

## ⚡ Capability Stack

| Capability | Evidence |
|:-----------|:---------|
| **RAG Pipeline Engineering** | Production hybrid search: BM25 + semantic + RRF fusion + rerank. Hit@5 0.892, $0/month infra |
| **Agentic AI Systems** | 418 active protocols, 74 workflows, 43 skills — full agent lifecycle (boot → work → shutdown) |
| **Multi-Agent Coordination** | Parallel worktree orchestration, coordinator synthesis, conditional skill activation |
| **Full-Stack Web Development** | [7 production sites](https://winstonkoh87.com/portfolio), Astro, zero-JS-first architecture |
| **AI Consulting** | Active client engagements — diagnostics, AI integration strategy, workflow automation |
| **Technical Writing** | [26 articles](https://winstonkoh87.com/writing), 9.8K+ views — clear communication of complex systems |

---

## ✍️ Recent Writing

- [9.8K Views, 750 Cloners: The Day I Shipped My Brain to the World](https://winstonkoh87.com/articles/athena-public-launch)
- [Why I Built My Own Brain (The 5 Pillars of Sovereign AI)](https://winstonkoh87.com/articles/athena-5-pillars)
- [The Trilateral Feedback Loop: Why One AI is Not Enough](https://winstonkoh87.com/articles/trilateral-feedback-loop)
- [The Bionic Operator: Why AI Replaces Tasks, Not Humans](https://winstonkoh87.com/articles/ai-bionic-layer)
- [The Anti-Slop Protocol: How to Write 3,000 Words in 3 Hours](https://winstonkoh87.com/articles/anti-slop-protocol)
- [The Vibe Coder's Trap: Why AI Speed Can't Fix Business Physics](https://winstonkoh87.com/articles/vibe-coding-trap)

---

## 💞️ Open to Collaborate

Looking for **pragmatic builders** who:

- Ship fast, iterate, break things at 70% readiness
- Value robustness over cleverness
- Are comfortable with async communication

📬 **Reach out**: [winstonkoh87@gmail.com](mailto:winstonkoh87@gmail.com) or DM on [LinkedIn](https://linkedin.com/in/winstonkoh87)

---

## 📫 Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-winstonkoh87.com-blue?style=flat&logo=github)](https://winstonkoh87.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-winstonkoh87-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/winstonkoh87)
[![Email](https://img.shields.io/badge/Email-winstonkoh87%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:winstonkoh87@gmail.com)

---

> *"The best way to predict the future is to build it."*
