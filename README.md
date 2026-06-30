<div align="center">

<h3>bess1lie — security tooling</h3>

detection-only security CLIs · scope-aware · built for bug bounty

</div>

---

## Tools

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">bounthunt</h3>
      <p align="center"><sub>Scope-Aware Bug Bounty Orchestrator</sub></p>
      <p align="center">
        <a href="https://github.com/bess1lie/bounthunt"><img src="https://img.shields.io/badge/repo-bounthunt-22c55e?style=flat-square&logo=github" alt="bounthunt"></a>
        <a href="https://github.com/bess1lie/bounthunt"><img src="https://img.shields.io/badge/version-1.1.0-22c55e?style=flat-square" alt="v1.1.0"></a>
      </p>
      <p align="center">Orchestrates subfinder · dnsx · httpx · naabu · nuclei · katana behind a YAML scope guard. SQLite history, checkpoint/resume, diff monitoring, Markdown/HTML reports.</p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">gqlhunter</h3>
      <p align="center"><sub>GraphQL Recon & Analysis CLI</sub></p>
      <p align="center">
        <a href="https://github.com/bess1lie/gqlhunter"><img src="https://img.shields.io/badge/repo-gqlhunter-3b82f6?style=flat-square&logo=github" alt="gqlhunter"></a>
        <a href="https://github.com/bess1lie/gqlhunter"><img src="https://img.shields.io/badge/version-0.2.0-3b82f6?style=flat-square" alt="v0.2.0"></a>
      </p>
      <p align="center">Discovers GraphQL endpoints, runs introspection, classifies fields by risk, detects IDOR candidates, diffs schema between runs. SARIF export, local dashboard.</p>
    </td>
  </tr>
</table>

## Landing page

All projects in one place — live at **[bess1lie.github.io](https://bess1lie.github.io/)**

<a href="https://bess1lie.github.io/"><img src="https://raw.githubusercontent.com/bess1lie/bounthunt/main/social-preview.png" alt="bess1lie — security tooling" width="100%"></a>

## Philosophy

- **detection only, never exploitation** — recon and analysis requests, never payloads
- **scope-aware** — every network action gated by a YAML scope file
- **open formats** — SQLite, Markdown, HTML, JSON, SARIF 2.1.0
- **two tools, two domains** — infra/host recon vs GraphQL schema/auth — no overlap, no monolith

## Quick install

```bash
# bounthunt (Python >= 3.11 + Go recon tools, or use Docker)
git clone https://github.com/bess1lie/bounthunt.git
cd bounthunt && pip install .

# gqlhunter (pure Python >= 3.11, no external binaries)
git clone https://github.com/bess1lie/gqlhunter.git
cd gqlhunter && pip install .
```

## Links

- [github.com/bess1lie](https://github.com/bess1lie)
- [bess1lie.github.io](https://bess1lie.github.io/) — landing page
- [bounthunt](https://github.com/bess1lie/bounthunt) · [docs](https://github.com/bess1lie/bounthunt/tree/main/docs)
- [gqlhunter](https://github.com/bess1lie/gqlhunter) · [docs](https://github.com/bess1lie/gqlhunter/tree/main/docs)

<div align="center">

<sub>MIT licensed · detection-only security tooling</sub>

</div>
