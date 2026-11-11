# bess1lie

I build detection-first security tooling — Python CLIs for recon automation, REST API security testing, and GraphQL security analysis. MIT-licensed, CI-tested, open source.

[Site](https://bess1lie.github.io) · [GitHub](https://github.com/bess1lie)

## Featured projects

| Project | What it does |
|---|---|
| **[apihunter](https://github.com/bess1lie/apihunter)** | REST API security testing for OpenAPI surfaces: discovery (22 known paths), authentication analysis, 8 heuristic checks (BOLA/IDOR, CORS, auth bypass, rate limiting, injection probes, info disclosure), scope-aware execution, SQLite persistence, HTML/Markdown/SARIF reports. PyPI: `pip install apihunter-bess1lie` |
| **[bounthunt](https://github.com/bess1lie/bounthunt)** | Scope-aware recon orchestration for bug bounty programs: scope guard blocks out-of-scope targets, diff monitoring of hosts/ports/findings across runs, checkpoint/resume, SQLite persistence, HTML/Markdown reports, Telegram/Discord notifications, Docker. PyPI: `pip install bounthunt` |
| **[gqlhunter](https://github.com/bess1lie/gqlhunter)** | GraphQL security analysis: endpoint discovery (18 paths), introspection-driven risk classification (IDOR/BOLA, auth gaps, depth/batching), query variants, SARIF output, local dashboard, CI with a ≥70% coverage gate. PyPI: `pip install gqlhunter` |

## Other work

**[bess1lie.github.io](https://github.com/bess1lie/bess1lie.github.io)** — personal site with live demo sites built for small businesses (barbershop, coffee shop, furniture store, salon, medical center, fitness, education, auto service).

## How I work

- **Detection-first** — analyse and verify before attempting anything intrusive
- **Scope-aware** — no request happens against a target without explicit authorization in scope files
- **Evidence over opinions** — every finding carries reproducible output: SQLite history, HTML/Markdown reports, SARIF
- **Open formats** — SQLite, HTML, Markdown, SARIF 2.1.0, no opaque state
- **Readable code** — typed Python, small modules, CI on every push

## Stack

Python · Typer · HTTPX · SQLite · Docker · GitHub Actions · GraphQL · OpenAPI / SARIF

## Contact

- Site: https://bess1lie.github.io
- Email: [bess1iework@gmail.com](mailto:bess1iework@gmail.com)
