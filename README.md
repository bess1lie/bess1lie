# bess1lie

`Security Engineer` · `Bug Bounty Hunter` · `Security Tooling`

Building detection-first, scope-aware CLIs for recon, API security and GraphQL analysis — Python 3.11+, Typer, Rich, HTTPX.

---

## Selected Work

### [`apihunter`](https://github.com/bess1lie/apihunter)
REST API security testing CLI — OpenAPI/Swagger discovery, authentication auditing, heuristic scanning (IDOR, CORS, rate limiting, info disclosure), multi-format reports (HTML/Markdown/SARIF), SQLite storage, scope-aware.

`Python` `Typer` `Rich` `HTTPX` `Jinja2` `PyYAML` `SQLite`

[![CI](https://github.com/bess1lie/apihunter/actions/workflows/ci.yml/badge.svg)](https://github.com/bess1lie/apihunter/actions/workflows/ci.yml) 243 tests passing · 86% coverage

---

### [`bounthunt`](https://github.com/bess1lie/bounthunt)
Bug bounty recon orchestration — subfinder/dnsx/httpx/naabu/nuclei/katana pipeline, YAML scope guard (allow/deny), checkpoint/resume, diff monitoring, SQLite history, Dockerized.

`Python` `Typer` `Rich` `HTTPX` `Jinja2` `PyYAML` `SQLite` `Docker`

[![CI](https://github.com/bess1lie/bounthunt/actions/workflows/ci.yml/badge.svg)](https://github.com/bess1lie/bounthunt/actions/workflows/ci.yml) 91 tests passing

---

### [`gqlhunter`](https://github.com/bess1lie/gqlhunter)
GraphQL recon & analysis — 18-path discovery, introspection with depth control, risk classification (IDOR/BOLA), auth comparison, schema diff, SARIF 2.1.0 export, built-in dashboard.

`Python` `Typer` `Rich` `HTTPX` `aiosqlite` `Jinja2` `PyYAML` `GraphQL`

[![CI](https://github.com/bess1lie/gqlhunter/actions/workflows/ci.yml/badge.svg)](https://github.com/bess1lie/gqlhunter/actions/workflows/ci.yml) 202 tests passing · SARIF 2.1.0 export

---

## Current Focus

Finishing gqlhunter SARIF 2.1.0 compliance and dashboard hardening. Actively hunting on Standoff 365 (Broken Access Control, DOM XSS submissions).

---

## Evidence

| Project | Tests | Coverage | CI | Key Feature |
|---------|-------|----------|----|-------------|
| [`apihunter`](https://github.com/bess1lie/apihunter) | 243 passing | 86% | ✅ | OpenAPI discovery + SARIF |
| [`bounthunt`](https://github.com/bess1lie/bounthunt) | 91 passing | — | ✅ | Recon orchestration + diff |
| [`gqlhunter`](https://github.com/bess1lie/gqlhunter) | 202 passing | — | ✅ | GraphQL risk + SARIF 2.1.0 |
| [`bess1lie.github.io`](https://bess1lie.github.io) | — | — | — | Interactive terminal, dark/light |

---

## Engineering Principles

| Principle | Implementation |
|-----------|----------------|
| Detection only | Recon & analysis only — never payloads or exploitation |
| Scope-aware | Every request gated by `scope.yaml` allow/deny lists |
| Open formats | SQLite, HTML, Markdown, SARIF 2.1.0 |
| Open source | MIT licensed, community-driven |

---

## Stack

`Python 3.11+` `Typer` `Rich` `HTTPX` `PyYAML` `Jinja2` `SQLite` `aiosqlite` `GraphQL` `OpenAPI` `SARIF` `Docker` `GitHub Actions`

---

## Connect

[`site`](https://bess1lie.github.io) · [`apihunter`](https://github.com/bess1lie/apihunter) · [`bounthunt`](https://github.com/bess1lie/bounthunt) · [`gqlhunter`](https://github.com/bess1lie/gqlhunter)  
[GitHub](https://github.com/bess1lie)

---

Almaty, Kazakhstan · detection-first security tooling · MIT licensed