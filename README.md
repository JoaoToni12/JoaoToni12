# João Gabriel Toni

Applied AI engineer. I build LLM systems you can check: evaluation sets that
catch silent failures, guardrails that fail closed, and audit trails a third
party can read.

ITA × CentraleSupélec · [joaotoni12.github.io](https://joaotoni12.github.io) ·
[LinkedIn](https://www.linkedin.com/in/joao-toni) · joaotoni2@gmail.com

Open to a 2027 engineering internship in Applied AI, Forward-Deployed or LLMOps
roles, from 26 April (about 21 weeks).

## Public work

**[Verifiable Agent Runtime](https://github.com/JoaoToni12/verifiable-agent-runtime)** ·
Python, FastAPI. Lets AI agents propose actions without silently acquiring
authority: payload-bound approvals, request-bound idempotency, deterministic risk
policies, shadow and kill-switch modes, and a hash-chained audit ledger. Tests,
CI, threat model, ADR.

**[Claude Code guardrails](https://github.com/JoaoToni12/claude-code-guardrails)** ·
Node.js. Deterministic `PreToolUse` and `PostToolUse` hooks that classify shell
and write actions as allow, ask or deny, fail closed on malformed input and block
path escapes. 46 dependency-free tests, CI on Node.js 22 and 24.

**Mapa de Falhas** · in review, public in January 2027. An open failure map for
Portuguese-language support assistants: 260 cases in 12 failure types (synthetic
personal-data leaks, prompt injection written in Portuguese, LGPD requests,
invented answers, long-conversation drift), a fictional company's knowledge base
with deliberate traps, and a reference RAG app in five configurations.

## In production

My employer repositories are private. These are scope counts at **NG.CASH**; no
company code, data, prompts, workflows or business rules are published here.

| Evidence | Scope |
|---|---|
| Repository contribution | Primary contributor across **18 private repositories**, roughly **760 commits** |
| Workflow engineering | Created most of approximately **148 production-orchestrator workflows** across **7 workspaces**; maintained or governed roughly half |
| LLM evaluation | A **1,000-question** graded set, **950** with expected-source labels for citation-correctness checks |
| Agentic reporting | A **63-node** weekly pipeline with **16 prompt-specialized analysts** and a synthesis stage |
| Operational outcomes | Replaced reporting and curation processes measured at about **15 hours/month** and **2–3 hours/week** |

## Education

- **CentraleSupélec**, double-degree Engineering Curriculum, Electronics, 2026–2028.
- **ITA**, Electronics Engineering, expected 2028. GPA 8.66/10, ranked 3rd of 20.

`Python` · `SQL` · `FastAPI` · `Claude Code` · `n8n` · `Snowflake` · `Docker` ·
`Kubernetes` · `ArgoCD` · `CI/CD`

Public repositories are clean-room work built with synthetic data and public
interfaces.
