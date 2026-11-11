<div align="center">

# bess1lie

<sup>Detection-first security tooling · scope-aware automation · open source</sup>

[Site](https://bess1lie.github.io) · [Email](mailto:bess1iework@gmail.com) · [GitHub](https://github.com/bess1lie)

</div>

---

**About.** I build command-line security tooling — recon automation, API security, GraphQL analysis — with a detection-first, scope-aware posture: nothing runs against a target without an explicit allowlist, and every finding ships with reproducible evidence.

**Also building.** Static web products and a demo portfolio for small businesses — barbershop, coffee shop, furniture store, salon, medical center, fitness, education, auto service — at [bess1lie.github.io](https://github.com/bess1lie/bess1lie.github.io).

## Selected work

### apihunter — REST API security testing
OpenAPI discovery (22 known paths), authentication analysis, 8 evidence-backed heuristic checks (BOLA/IDOR, CORS, auth bypass, rate limiting, injection probes, information disclosure), scope-gated execution, SQLite history, HTML/Markdown/SARIF reports.

`pip install apihunter-bess1lie` · [GitHub](https://github.com/bess1lie/apihunter)

### bounthunt — scope-aware recon orchestration
Chains subfinder → dnsx → httpx → naabu → nuclei → katana behind an allowlist gate. Diff monitoring of hosts/ports/findings across runs, checkpoint/resume for long campaigns, SQLite history, Docker, Telegram/Discord notifications.

`pip install bounthunt` · [GitHub](https://github.com/bess1lie/bounthunt)

### gqlhunter — GraphQL security analysis
Endpoint discovery (18 paths + POST introspection), IDOR/auth/depth risk classification, query variants, SARIF 2.1.0 export, local dashboard. CI enforces a ≥ 70% coverage gate on Python 3.11–3.13.

`pip install gqlhunter` · [GitHub](https://github.com/bess1lie/gqlhunter)

All three are MIT-licensed, CI-tested, and detection-first.

## How I work

- **Detection before action** — analyse first; never exploit by default
- **Scope-aware by default** — no request without an explicit allow rule
- **Evidence over assertions** — every finding carries reproducible output: SQLite, HTML/Markdown, SARIF
- **Open formats** — inspectable, diffable, CI-friendly

## Stack

Python · Typer · HTTPX · SQLite · Docker · GitHub Actions · GraphQL · OpenAPI / SARIF

---

<div align="center">

**bess1lie** · detection-first · scope-aware · open source

[Site](https://bess1lie.github.io) · [Email](mailto:bess1iework@gmail.com) · [GitHub](https://github.com/bess1lie)

</div>
