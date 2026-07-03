# 👋 Hi, I'm Jarede Silva

Software engineer focused on **backend, systems integration, and automation** — building everything from middleware that talks to on-premise ERPs to command-line tools for my own workflow.

## 🕰️ Timeline

- **2004** — Developed Java applications for task automation; evolved into commercial desktop projects using Swing
- **2006** — Started developing web services using Python
- **2020** — Started learning Rust
- **2026** — Shipped my first Rust CLI

## 🧰 Languages & Stacks

- **Python** — my main language: FastAPI, Flask, Pydantic, Pandas, oracledb, ldap3, pytest (incl. BDD with `pytest-bdd`)
- **Rust** — Axum (web), Clap (CLI), Tokio, rusqlite, deep-dive learning projects (`edition 2024`)
- **Shell / Fish** — environment automation, lint/test watchers with `entr`
- **Swift** — macOS utility apps (menu bar, Cocoa/AppKit)
- **SQL / PL-SQL** — Oracle (analytical queries, `DBMS_SCHEDULER`, RAC lock monitoring)
- **Frontend** — React, TypeScript, Vite, Bun, Tailwind CSS, Bootstrap, server-rendered UIs with Jinja2

## 🏗️ Architecture & Integrations

- **Middleware / EAI** — orchestration of commercial and logistics integrations between ERPs, supply systems, and store-floor systems, with documented flows, ADRs, and bounded contexts (DDD-lite)
- **REST APIs** — FastAPI as the standard for new services, with typed client generation from OpenAPI specs; authentication via Active Directory/LDAP
- **Real-time dashboards** — logistics operations and job/lock monitoring (Chart.js, Alpine.js, Jinja2)
- **Databases** — Oracle (production), SQLite (local analytics), query/view modeling for legacy systems
- **Hardware automation** — label printer automation via a dedicated API
- **Geoprocessing** — pipelines with open geographic data, spatial clustering, map rendering, and PDF generation
- **Third-party API integrations** — productivity/spreadsheet APIs, live currency exchange, geocoding

## 🚢 DevOps & Quality

- **CI/CD** — GitLab CI (multiple environments: dev/qa/prod), GitHub Actions (cross-platform builds, automated releases)
- **Containers** — multi-stage Docker/Docker Compose, Apple's native `container` CLI on macOS, reverse proxy with per-environment certificates
- **Packaging & distribution** — self-hosted Homebrew tap and Scoop bucket to distribute a cross-platform Rust CLI (macOS/Linux/Windows)
- **Code quality** — Ruff, Pyright/mypy, pytest with coverage and parallelization (`pytest-xdist`), Rust unit tests
- **Observability** — structured logging (`tracing` in Rust, `loguru` in Python), job/lock monitoring dashboards

## 🤖 AI-assisted workflow

- Daily use of **Claude Code** and **OpenCode** as part of my development process, with my own tools to measure and analyze that usage (hours, costs, tokens per model)
- Agent-oriented documentation (`CLAUDE.md`, `AGENTS.md`, skills) in my own repositories to keep context consistent across sessions

## 🌱 Featured personal projects

- [`dev-cli`](https://github.com/jarede/dev-cli) — Rust CLI ("swiss army knife"), a learning project with automated releases, a self-hosted Homebrew tap, and a Scoop bucket
