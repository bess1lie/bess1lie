<div align="center">

# bess1lie

**security engineer** · **bug bounty** · **security tooling**

API, GraphQL and reconnaissance tooling built around detection and analysis.

</div>

<br>

```text
$ gqlhunter discover target.example --scope scope.yaml
[+] GraphQL endpoint discovered
[+] Schema introspection complete
[+] 42 types, 18 queries, 7 mutations
[+] Risk analysis complete

$ gqlhunter scan target.example/graphql --scope scope.yaml
[+] Introspection enabled (depth 5)
[+] 42 types, 18 queries, 7 mutations stored
[!] Risk: 3 high (IDOR), 2 medium
[+] SARIF report written to gqlhunter.sarif
```

<br>

## Work

### [apihunter](https://github.com/bess1lie/apihunter)

REST API security CLI — OpenAPI discovery, authentication auditing, heuristic scanning (IDOR, CORS, rate limiting), SARIF/HTML/Markdown reports, scope-aware.

`OpenAPI` `IDOR` `CORS` `SARIF`

![apihunter](https://raw.githubusercontent.com/bess1lie/apihunter/main/docs/screenshots/scan.svg)

**243 tests · 86% coverage · CI passing**

[View repository →](https://github.com/bess1lie/apihunter)

<br>

### [bounthunt](https://github.com/bess1lie/bounthunt)

Bug bounty recon orchestration — subfinder→dnsx→httpx→naabu→nuclei→katana pipeline, YAML scope guard, checkpoint/resume, diff monitoring, Dockerized.

`Recon` `Pipeline` `Scope` `Docker`

![bounthunt](https://raw.githubusercontent.com/bess1lie/bounthunt/main/screenshots/terminal.png)

**91 tests · CI passing**

[View repository →](https://github.com/bess1lie/bounthunt)

<br>

### [gqlhunter](https://github.com/bess1lie/gqlhunter)

GraphQL recon & risk analysis — introspection with depth control, IDOR/BOLA classification, schema diff, SARIF 2.1.0 export, built-in dashboard.

`GraphQL` `IDOR` `SARIF` `Dashboard`

![gqlhunter](https://raw.githubusercontent.com/bess1lie/gqlhunter/main/screenshots/dashboard-preview.png)

**202 tests · CI passing · SARIF 2.1.0**

[View repository →](https://github.com/bess1lie/gqlhunter)

<br>

## What I build

`API Security` · `Recon Automation` · `GraphQL Security` · `Security Automation` · `Detection Tooling`

<br>

## Principles

**Detection only** — recon & analysis, never payloads or exploitation

**Scope-aware** — every request gated by `scope.yaml` allow/deny

**Open formats** — SQLite · HTML · Markdown · SARIF 2.1.0

**Open source** — MIT licensed, community-driven

<br>

## Stack

`Python 3.11+` `Typer` `Rich` `HTTPX` `PyYAML` `Jinja2` `SQLite` `aiosqlite` `GraphQL` `OpenAPI` `Docker` `GitHub Actions`

<br>

## Now

Finishing gqlhunter SARIF 2.1.0 compliance & dashboard hardening. Active on Standoff 365 (Broken Access Control, DOM XSS submissions).

<br>

<div align="center">

Almaty, Kazakhstan · [site](https://bess1lie.github.io) · [apihunter](https://github.com/bess1lie/apihunter) · [bounthunt](https://github.com/bess1lie/bounthunt) · [gqlhunter](https://github.com/bess1lie/gqlhunter)

</div>