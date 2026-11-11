<div align="center">

# BESS1LIE

<sup><strong>SECURITY TOOLING BUILDER</strong> · detection-first · scope-aware · open source</sup>

[Site](https://bess1lie.github.io) &nbsp;·&nbsp; [Email](mailto:bess1iework@gmail.com) &nbsp;·&nbsp; [GitHub](https://github.com/bess1lie)

</div>

---

## About

I build command-line security tooling for recon, API security and GraphQL analysis — scoped to run only with an explicit allowlist, with every finding shipped as reproducible evidence.<br>
Also building a static web portfolio for small businesses — [bess1lie.github.io](https://bess1lie.github.io).

<hr>

## Selected work

### MUTATION EVIDENCE
**mutvera** — defensive mutation testing for the security tests of Python + FastAPI webhook receivers. Injects controlled defects into isolated project copies and re-runs your suite — showing which mutations your tests catch, and which they silently miss. MIT-licensed, local-first, RU/EN web UI.

`git clone https://github.com/bess1lie/mutvera-public.git` &nbsp;·&nbsp; [GitHub](https://github.com/bess1lie/mutvera-public)

<hr>

### REST API SECURITY
**apihunter** — OpenAPI discovery across 22 known paths, authentication analysis, 8 evidence-backed heuristic checks (BOLA/IDOR, CORS, auth bypass, rate limiting, injection probes, information disclosure), scope-gated execution, SQLite history, HTML/Markdown/SARIF reports.

`pip install apihunter-bess1lie` &nbsp;·&nbsp; [GitHub](https://github.com/bess1lie/apihunter)

<hr>

### RECON AUTOMATION
**bounthunt** — scoped recon orchestration. Chains subfinder → dnsx → httpx → naabu → nuclei → katana behind an allowlist gate. Diff monitoring across runs, checkpoint/resume for long campaigns, SQLite history, Docker, Telegram/Discord notifications.

`pip install bounthunt` &nbsp;·&nbsp; [GitHub](https://github.com/bess1lie/bounthunt)

<hr>

### GRAPHQL SECURITY
**gqlhunter** — endpoint discovery (18 paths + POST introspection), IDOR/auth/depth risk classification, query variants, SARIF 2.1.0 export, local dashboard. CI enforces a ≥ 70% coverage gate on Python 3.11–3.13.

`pip install gqlhunter` &nbsp;·&nbsp; [GitHub](https://github.com/bess1lie/gqlhunter)

<hr>

## How I work

- **Evidence over opinions** — every finding ships with reproducible output
- **Scope-aware by default** — no request without an explicit allow rule
- **Open formats** — SQLite · HTML · Markdown · SARIF

## Stack

Python &nbsp;·&nbsp; Typer &nbsp;·&nbsp; HTTPX &nbsp;·&nbsp; SQLite &nbsp;·&nbsp; Docker &nbsp;·&nbsp; GitHub Actions &nbsp;·&nbsp; GraphQL

<hr>

<div align="center">

**bess1lie** &nbsp;·&nbsp; detection-first &nbsp;·&nbsp; scope-aware &nbsp;·&nbsp; open source

[Site](https://bess1lie.github.io) &nbsp;·&nbsp; [Email](mailto:bess1iework@gmail.com) &nbsp;·&nbsp; [GitHub](https://github.com/bess1lie)

</div>
