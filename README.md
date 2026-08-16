<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.png">
    <img alt="A geological cross-section, fractured by two fault lines, reading: I build systems that cannot conceal their own state" src="./assets/banner-light.png" width="100%">
  </picture>
</p>

<p align="center">
  <strong>Security engineering, open infrastructure, and AI evaluation for systems that should fail visibly, not silently.</strong>
</p>

<p align="center">
  <a href="https://mazzeleczzare.com">mazzeleczzare.com</a> &nbsp;·&nbsp;
  <a href="https://orcid.org/0009-0005-9661-4780">ORCID</a> &nbsp;·&nbsp;
  <a href="mailto:mazze@mazzeleczzare.com">Get in touch</a>
</p>

---

## Thesis

Systems reveal themselves under pressure — that's the working premise behind everything in this profile. I build and test for **observable state**: security tooling, privacy-preserving infrastructure, and human-AI systems designed so that failure surfaces early instead of getting buried under a passing test suite.

Every project here is built against the same constraint: it has to work, be auditable, and be legible to people who aren't security engineers.

---

## Current Excavations

- Hardening privacy-first, local-first infrastructure (Meridian, mindful-dev)
- Building policy guardrails and integrity telemetry for agentic AI (praxis-aegis, stele)
- Extending forensic tooling and MCP-server infrastructure (git-forensics-agent, kairos-mcp)
- Writing on privacy infrastructure and human–AI collaboration

---

## Work Strata

| Domain | Focus | Typical output |
|---|---|---|
| Security & privacy infrastructure | Threat-informed hardening, container/CI security, adversarial-conditions design | tooling, templates, audits |
| Trustworthy & agentic AI | Policy guardrails, integrity telemetry, epistemic decision logging | guardrail libraries, ledgers, research notes |
| Apps & product design | Local-first sync, E2E-encrypted social systems, editorial platforms | shipped apps, calm UX under real constraints |

---

## Bedrock

The load-bearing layer — the sites where the evidence checks out cleanly against the claims. Not a "best of," a "checked."

- [**mazze-leczzare-blog**](https://github.com/mazze93/mazze-leczzare-blog) — 16 published essays, five green CI pipelines (build, CodeQL, dependency review, docs integrity, Lighthouse), live.
- [**secure-container-template**](https://github.com/mazze93/secure-container-template) — non-root enforcement gated in CI, actions pinned to commit SHAs, a release that's actually shipped.
- [**kairos-mcp**](https://github.com/mazze93/kairos-mcp) — MCP server for reasoning frameworks, dual transport, real tests, clean dependency hygiene.
- [**github-mcp-gateway**](https://github.com/mazze93/github-mcp-gateway) — GitHub App OAuth gateway for MCP clients, in active daily use.
- [**stratum**](https://github.com/mazze93/stratum) — dual Python/TS implementation with parity checked in CI, doc-drift detection, a live Cloudflare Worker demo.

---

## Selected Sites

Three exposures, drilled from the same face. Expand a core sample to see what's in it.

<details open>
<summary><strong>Security & privacy infrastructure</strong></summary>
<br>

| Project | What it does |
|---|---|
| [**secure-pride**](https://github.com/mazze93/secure-pride) | Privacy-first cybersecurity tools and standards for LGBTQ+ communities and high-risk groups, built for adversarial conditions |
| [**git-forensics-agent**](https://github.com/mazze93/git-forensics-agent) | Zero-knowledge forensic case-file agent for adversarial git incidents — Durable Object brain, AES-256-GCM, HMAC-signed repair gate |
| [**mindful-dev**](https://github.com/mazze93/mindful-dev) | Claude Code pre-action safety gate — blocks dangerous commands, redacts secrets, guards shell access |

</details>

<details>
<summary><strong>Trustworthy AI & agentic systems</strong></summary>
<br>

| Project | What it does | Live |
|---|---|---|
| [**praxis-aegis**](https://github.com/mazze93/praxis-aegis) | Trust-layer for agentic AI: policy guardrails and signing-aware controls for AI tool use | — |
| [**stele**](https://github.com/mazze93/stele) | Directive compiler and integrity telemetry — governance-as-code for AI-assisted work | [stele.mazzeleczzare.com](https://stele.mazzeleczzare.com) |
| [**context-synapse**](https://github.com/mazze93/context-synapse) | Experimental engine for modeling how humans and AI systems negotiate context | — |
| [**adaptive-response**](https://github.com/mazze93/adaptive-response) | Schema-driven AI response engine — Cloudflare Worker + Zod-validated typed output, deny-by-default CORS | — |

</details>

<details>
<summary><strong>Apps & product design</strong></summary>
<br>

| Project | What it does |
|---|---|
| [**meridian**](https://github.com/mazze93/meridian) | Privacy-first, local-first calendar for Apple platforms — Tailscale-only peer sync, no cloud |
| [**lockr**](https://github.com/mazze93/lockr) | Privacy-first dating and social app for the LGBTQ+ community — E2E encryption, safety-first design |
| [**daedalus-switch**](https://github.com/mazze93/daedalus-switch) | Identity & context switcher — one command switches VPN, terminal, browser, and filesystem context |

</details>

---

## Instrument Panel

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
  <img alt="Tailscale" src="https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white">
</p>

The instruments that show up across these sites, not a full résumé of tools.

---

## Research Line

Essays, technical notes, and research on privacy infrastructure, human–AI collaboration, and open-source systems thinking.

→ [mazzeleczzare.com](https://mazzeleczzare.com) &nbsp;·&nbsp; [ORCID 0009-0005-9661-4780](https://orcid.org/0009-0005-9661-4780)

---

## Build Philosophy

Software should be **secure**, **humane**, **understandable**, and accessible to people who aren't security engineers.

That's not a nice-to-have. That's the constraint every project here is built against.

---

## Work Together

Open to collaboration on privacy tooling, secure infrastructure, and human–AI systems — especially with researchers, independent builders, and mission-driven organizations.

Open an issue, or [reach out directly](https://mazzeleczzare.com).
