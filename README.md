# Hi, I'm Arup Biswas 👋

**Senior Software Engineer moving into AI Engineering** — 10+ years building backend systems and microservices at scale, now building RAG systems, LLM agents and evaluation tooling.

📍 Kolkata, India · 💼 [LinkedIn](https://www.linkedin.com/in/arup-biswas-ai-engineer/) · ✉️ arupbiswas.tech@outlook.com

## What I've built professionally
- **StemScopes LMS** — architected a microservices platform (Symfony, DynamoDB, GraphQL) serving **500,000+ active users**; integrated **LTI 1.3** with Learnosity, cutting auth latency by **35%**.
- **Backend microservices** — Symfony + RoadRunner services that improved API response times by **40%**.
- **Pearson assessment modernization** — migrated legacy PHP/MySQL tooling to QTI standards and S3 private storage (**30%** faster media loads); led Checkmarx security remediation.
- Led a team of **12+ engineers** across Agile delivery.

## Tech stack
| Area | Tools |
|---|---|
| AI | Python, RAG, LangGraph, pgvector, embeddings, LLM evaluation, Groq API, Ollama |
| API / Tooling | FastAPI, pytest, Docker, GitHub Actions |
| Backend | PHP (Symfony, Laravel), Node.js, REST, GraphQL, microservices |
| Data | PostgreSQL, MySQL, DynamoDB, MongoDB |
| Frontend | React, TypeScript, Streamlit |
| Cloud / DevOps | AWS (Lambda, S3, App Runner), Azure Container Apps, Docker |

## Featured project: [CodeLens](https://github.com/arupbiswas-tech/codelens)
Ask questions about a codebase and get answers with `file:line` citations, and review pull requests with an agent that uses retrieved code as context.

- **Stack:** Python, FastAPI, PostgreSQL + pgvector, LangGraph, Groq (LLM), local embeddings (fastembed), Docker, GitHub Actions.
- **Retrieval:** hybrid search (vector + keyword, merged with Reciprocal Rank Fusion) with an optional reranker, measured against 29 hand-labelled questions over 4 public repos.
- **Grounded answers:** every citation is checked against the code the model was shown; made-up references are dropped. 26/26 answers had a verified citation, 0 made-up citations, 3/3 unanswerable questions correctly refused.
- **PR reviewer:** found 6/6 seeded bugs on the exact line with no comments on 2 harmless diffs, using a rule check plus an LLM self-check. Runs as a GitHub Action.
- **Engineering:** design trade-offs recorded in a decision log, typed errors, timeouts and retries, tests against a real database. Small samples are reported as such.

## Other projects
| Project | Description | Status |
|---|---|---|
| [workout-plan-generator](https://github.com/arupbiswas-tech/workout-plan-generator) | Streamlit app that builds personalised weekly plans with the Groq API | ✅ Live |
| [my-portfolio](https://github.com/arupbiswas-tech/my-portfolio) | Personal portfolio site | ✅ Live |

## Currently
Next: an MCP server and a multi-step tool-using agent with tracing and tests. Building in public toward production-grade AI systems, bringing the reliability, security and scale habits of enterprise backend work to LLM applications.

**Open to** AI Engineer / Backend-AI roles.
