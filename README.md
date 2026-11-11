# Nicolás Iglesias

**Junior AI Engineer** · Python · LLMs · RAG · n8n · Buenos Aires, Argentina

> Desarrollador Python orientado a IA aplicada y automatización. Busco mi primer rol como AI Engineer Jr. o en Automatización con IA.

I build AI applications in Python and automations that connect language models with real business processes.

- **In production:** at AutoFlow (used by a real client) I built the assistant (OpenAI API, read-only tool calling) and worked on the WhatsApp → n8n order integration (webhook).
- **Learning by building:** a RAG system over code and documentation, with hybrid search, citations, abstention and held-out evaluation.
- **How I work:** AI-assisted development with Claude Code and Codex, checked with tests and evaluation.

## Featured work

### Codebase Explorer (RAG) · [Live demo](https://codebase-explorer-rag.onrender.com) (may take ~1 min to wake up) · [Code](https://github.com/NicolasIgles/codebase-explorer-rag)
Ask questions about a codebase and its docs; answers cite the file and line, and the system abstains when the evidence is not enough. Personal learning project built in 3 days with Claude Code.
- Hybrid search (lexical + embeddings, rank fusion); structure-aware ingestion (Python `ast`, Tree-sitter for JS/TS), Markdown, TXT and PDF
- Held-out eval: expected sources retrieved in **7/7**, correct citation in **6/7** answers, correct abstention in **2/2** (small set, limits documented)
- **72 tests**, FastAPI, deployed on Render (Dockerfile)

### AutoFlow (production, private code)
Multi-company (multi-tenant) management platform, in production with a real client. I work on development in a team of three.
- Built the assistant with the OpenAI API and read-only tool calling
- Built server-side access checks by user and company
- Worked on the WhatsApp orders → webhook → n8n → platform integration

### CSV Processing Automation · [Code](https://github.com/NicolasIgles/csv-processing-automation)
Python + pandas CLI that cleans, normalizes and consolidates CSV files (per-file deduplication), with per-file reports, logs and pytest tests.

## Tech stack

- **AI:** OpenAI API, tool calling, RAG, embeddings, hybrid search, RAG evaluation
- **Automation & APIs:** n8n, webhooks, REST APIs, FastAPI, WhatsApp integration
- **Languages & data:** Python, SQL, PostgreSQL, pandas; TypeScript and Next.js (AI-assisted)
- **Tools:** Claude Code, Codex, Git, pytest, unittest, Render, Docker (basic)

## Right now

- Studying English on my own (today: intermediate technical reading, basic speaking)
- Planning an AI engineering course to go deeper

## Contact

Open to **Junior AI Engineer** and **AI Automation** roles (remote, hybrid or on-site in Buenos Aires; employment, contract or freelance).
Best way to reach me: [LinkedIn](https://www.linkedin.com/in/nicolas-iglesias-py).
