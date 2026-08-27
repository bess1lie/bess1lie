<div align="center">

# bess1lie

**`security engineer` · `bug bounty` · `detection-first tooling`**

> recon, api and graphql security — built to detect, never to exploit.

![pwn](https://img.shields.io/badge/%3E__whoami-bess1lie-0d1117?style=for-the-badge&labelColor=58a6ff)

</div>

```text
$ gqlhunter discover target.example --scope scope.yaml
[+] GraphQL endpoint discovered
[+] Schema introspection complete → 42 types / 18 queries / 7 mutations
[+] Risk analysis complete

$ gqlhunter scan target.example/graphql --scope scope.yaml
[+] Introspection enabled (depth 5)
[+] 42 types stored · 3 high (IDOR) · 2 medium
[+] SARIF report → gqlhunter.sarif
```

## Work

### [apihunter](https://github.com/bess1lie/apihunter)
REST API security CLI — OpenAPI discovery, auth auditing, IDOR / CORS / rate-limit heuristics, SARIF · HTML · Markdown, scope-aware.
`OpenAPI` `IDOR` `CORS` `SARIF`
<br>
![apihunter](https://raw.githubusercontent.com/bess1lie/apihunter/main/docs/screenshots/scan.svg)
**243 tests · 86% coverage · CI passing** — [View repository →](https://github.com/bess1lie/apihunter)

<br>

### [bounthunt](https://github.com/bess1lie/bounthunt)
Bug bounty recon orchestration — `subfinder → dnsx → httpx → naabu → nuclei → katana`, scope-gated, diff monitoring, dockerized.
`Recon` `Pipeline` `Scope` `Docker`
<br>
![bounthunt](https://raw.githubusercontent.com/bess1lie/bounthunt/main/screenshots/terminal.png)
**91 tests · CI passing** — [View repository →](https://github.com/bess1lie/bounthunt)

<br>

### [gqlhunter](https://github.com/bess1lie/gqlhunter)
GraphQL recon & risk — introspection with depth control, IDOR/BOLA classification, schema diff, SARIF 2.1.0, built-in dashboard.
`GraphQL` `IDOR` `SARIF` `Dashboard`
<br>
![gqlhunter](https://raw.githubusercontent.com/bess1lie/gqlhunter/main/screenshots/dashboard-preview.png)
**202 tests · CI passing · SARIF 2.1.0** — [View repository →](https://github.com/bess1lie/gqlhunter)

## What I build

`API Security` · `Recon Automation` · `GraphQL Security` · `Security Automation` · `Detection Tooling`

## Principles

**Detection only** — recon & analysis, never payloads
<br>**Scope-aware** — every request gated by `scope.yaml` allow/deny
<br>**Open formats** — SQLite · HTML · Markdown · SARIF 2.1.0
<br>**Open source** — MIT licensed

## Stack

<p align="left">
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=python,docker,sqlite,githubactions&theme=dark" alt="core stack" /></a>
  <br>
  <img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0d1117" alt="python" />
  <img src="https://img.shields.io/badge/Typer-CLI-58a6ff?style=for-the-badge&labelColor=0d1117" alt="typer" />
  <img src="https://img.shields.io/badge/Rich-Terminal-3fb950?style=for-the-badge&labelColor=0d1117" alt="rich" />
  <img src="https://img.shields.io/badge/HTTPX-Async-8b949e?style=for-the-badge&labelColor=0d1117" alt="httpx" />
  <img src="https://img.shields.io/badge/GraphQL-API-f0883e?style=for-the-badge&logo=graphql&logoColor=white&labelColor=0d1117" alt="graphql" />
  <img src="https://img.shields.io/badge/OpenAPI-Spec-85e3ff?style=for-the-badge&labelColor=0d1117" alt="openapi" />
  <img src="https://img.shields.io/badge/SARIF-2.1.0-d29922?style=for-the-badge&labelColor=0d1117" alt="sarif" />
</p>

## Now

Currently hardening `gqlhunter` SARIF & dashboard. Active research on Standoff 365 — Broken Access Control / DOM XSS.

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bess1lie&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff&count_private=true&include_all_commits=true" alt="stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bess1lie&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=6" alt="langs" height="150" />
  <br>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=bess1lie&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ff0078&area=true" alt="graph" width="100%" />
</p>

<div align="center">

[site](https://bess1lie.github.io) · [apihunter](https://github.com/bess1lie/apihunter) · [bounthunt](https://github.com/bess1lie/bounthunt) · [gqlhunter](https://github.com/bess1lie/gqlhunter)

`detection-first` `scope-aware` `open-source` · MIT licensed

</div>
