# João Gabriel Toni

### Applied AI & Automation Engineer · AI Deployment · Evaluated and observable LLM systems

I build AI and automation systems that survive contact with production:
source-grounded, evaluated, monitored, and accountable.

Based in Rennes, France · Open to remote AI Engineering and AI Deployment roles

[LinkedIn](https://www.linkedin.com/in/joao-toni) ·
[Email](mailto:joaotoni2@gmail.com) ·
[Featured project](https://github.com/JoaoToni12/verifiable-agent-runtime)

## What I work on

- **Production AI systems:** source-grounded assistants, constrained tool use,
  prompt caching, cost-aware model routing, and human approval gates.
- **Evaluation:** citation-correctness scoring, adversarial and out-of-corpus
  cases, multi-turn behavior, and prompt-injection tests.
- **Reliability:** monitoring for explicit failures, silent non-execution, data
  anomalies, PII-safe alerts, and health checks outside the primary orchestrator.
- **AI automation at scale:** version-controlled delivery, schema validation,
  deployment controls, graceful degradation, and operational ownership.

## Current production scope

My employer repositories remain private. The numbers below describe my verified
scope at **NG.CASH**; no company source code, data, prompts, workflows, or
business rules are published here.

| Evidence | Scope |
|---|---|
| Repository ownership | Primary contributor across **18 private repositories** and roughly **760 commits** |
| Workflow engineering | Created most of approximately **148 production-orchestrator workflows** across **7 workspaces**; maintained or governed roughly half |
| LLM evaluation | Built a **1,000-question** graded set, including **950 expected-source labels** for citation-correctness evaluation |
| Agentic reporting | Developed a **63-node** weekly pipeline with **16 prompt-specialized analysts** and a synthesis stage |
| Operational outcomes | Replaced reporting and curation processes measured at approximately **15 hours/month** and **2–3 hours/week** respectively |

## Public work

### [Verifiable Agent Runtime](https://github.com/JoaoToni12/verifiable-agent-runtime)

[![CI](https://github.com/JoaoToni12/verifiable-agent-runtime/actions/workflows/ci.yml/badge.svg)](https://github.com/JoaoToni12/verifiable-agent-runtime/actions/workflows/ci.yml)

A clean-room FastAPI control plane for policy-gated AI actions. It demonstrates
payload-bound approvals, request-bound idempotency, deterministic risk policies,
shadow and kill-switch modes, and a hash-chained audit ledger. The repository
includes strict typing, tests, CI, Docker Compose, Kubernetes manifests, a threat
model, and an ADR.

## Stack

`Python` · `SQL` · `FastAPI` · `n8n` · `Snowflake` · `REST APIs` · `Docker` ·
`Kubernetes` · `ArgoCD` · `CI/CD` · `Git` · `Linux`

## Next clean-room builds

- **rag-or-not:** compare cached long-context and retrieval using the same public
  corpus and evaluation harness across quality, citation correctness, latency,
  and cost.
- **silent-failure-detector:** distinguish a failed job from one that silently
  did not run or ran with anomalous volume, using synthetic events and an
  independent dead-man's-switch.

## Education

- **CentraleSupélec** — incoming double-degree Engineering Curriculum,
  Electronics, 2026–2028.
- **Instituto Tecnológico de Aeronáutica (ITA)** — Electronics Engineering,
  expected 2028; GPA 8.63/10, ranked 3rd of 20.

> Public repositories are independent clean-room work built with synthetic data
> and public interfaces. Employer systems and implementation details stay private.
