# 👋 Hi, I'm Jarede Silva

Software engineer focused on **backend, systems integration, and automation** — building everything from middleware that talks to on-premise ERPs to command-line tools for my own workflow.

## 📊 Skills overview

Engineering capability stays constant across tools; technology depth doesn't. Each axis is a tech-agnostic capability; the emoji marks which technology currently drives it, and how far along it is — a chart I'll keep updating as it evolves.

![Hand-drawn-style engineering capabilities radar with a technology emoji at each vertex: Python at Backend and APIs and at Systems integration, Docker at DevOps and CI/CD, SQL/Oracle at Databases, Shell/Fish at Automation and tooling, and React at Frontend. A Rust emoji sits near the second ring on the Backend and APIs axis, and another sits close to the center on Systems integration, marking how far it still has to go on each](assets/skills-progress-full.svg)

## 🕰️ Timeline

☕ **2004** — Developed Java applications for task automation; evolved into commercial desktop projects using Swing
🐍 **2006** — Started developing web services using Python
🐙 **2011** — Joined GitHub
📦 **2013** — Shipped a demand-forecasting and replenishment system for retail stores and warehouses
🐳 **2014** — Adopted Docker and self-hosted GitLab (Community Edition)
📊 **2015** — Shipped a BI reporting system for a distribution center and a public-facing supplier delivery-scheduling portal (BPM/workflow) — both still running in production today
🛒 **2016** — Shipped order integration between an ERP and an e-commerce marketplace — still running in production today
🤖 **2017** — Shipped ML-driven forecasting (supervised linear regression) for the replenishment system, rolled out company-wide across all stores and warehouses
🔀 **2019** — Shipped a middleware orchestrating pricing, commercial agreements, and logistics data between an ERP, supply-chain systems, and store-floor systems — still running in production today
🦀 **2020** — Started learning Rust
⚙️ **2026** — Shipped my first Rust CLI

## 🧰 Languages & Stacks

🐍 **Python** — my main language: FastAPI, Flask, Pydantic, Pandas, oracledb, ldap3, pytest (incl. BDD with `pytest-bdd`)
🦀 **Rust** — Axum (web), Clap (CLI), Tokio, rusqlite, deep-dive learning projects (`edition 2024`)
🐚 **Shell / Fish** — environment automation, lint/test watchers with `entr`
🍎 **Swift** — macOS utility apps (menu bar, Cocoa/AppKit)
🗄️ **SQL / PL-SQL** — Oracle (analytical queries, `DBMS_SCHEDULER`, RAC lock monitoring)
🎨 **Frontend** — React, TypeScript, Vite, Bun, Tailwind CSS, Bootstrap, server-rendered UIs with Jinja2

## 🏗️ Architecture & Integrations

🔀 **Middleware / EAI** — orchestration of commercial and logistics integrations between ERPs, supply systems, and store-floor systems, with documented flows, ADRs, and bounded contexts (DDD-lite)
🌐 **REST APIs** — FastAPI as the standard for new services, with typed client generation from OpenAPI specs; authentication via Active Directory/LDAP
📈 **Real-time dashboards** — logistics operations and job/lock monitoring (Chart.js, Alpine.js, Jinja2)
🗃️ **Databases** — Oracle (production), SQLite (local analytics), query/view modeling for legacy systems
🖨️ **Hardware automation** — label printer automation via a dedicated API
🗺️ **Geoprocessing** — pipelines with open geographic data, spatial clustering, map rendering, and PDF generation
🔌 **Third-party API integrations** — productivity/spreadsheet APIs, live currency exchange, geocoding

## 🚢 DevOps & Quality

🔁 **CI/CD** — GitLab CI (multiple environments: dev/qa/prod), GitHub Actions (cross-platform builds, automated releases)
🐳 **Containers** — multi-stage Docker/Docker Compose, Apple's native `container` CLI on macOS, reverse proxy with per-environment certificates
📦 **Packaging & distribution** — self-hosted Homebrew tap and Scoop bucket to distribute a cross-platform Rust CLI (macOS/Linux/Windows)
✅ **Code quality** — Ruff, Pyright/mypy, pytest with coverage and parallelization (`pytest-xdist`), Rust unit tests
🔍 **Observability** — structured logging (`tracing` in Rust, `loguru` in Python), job/lock monitoring dashboards

## 🤖 AI-assisted workflow

💬 Daily use of **Claude Code** and **OpenCode** as part of my development process, with my own tools to measure and analyze that usage (hours, costs, tokens per model)
📝 Agent-oriented documentation (`CLAUDE.md`, `AGENTS.md`, skills) in my own repositories to keep context consistent across sessions

## 🖥️ Dev environment

✏️ **Editor** — Neovim (LazyVim), configured for Python/Rust LSP workflows, custom colorscheme and status line
🖲️ **Terminal** — tmux with a custom status bar (CPU/GPU/RAM), fish shell with functions/watchers for lint and tests
🍏 **macOS** — native menu bar utility apps built with Swift/Cocoa, devcontainer tooling for remote/Linux dev

## 🌱 Featured personal projects

🛠️ [`dev-cli`](https://github.com/jarede/dev-cli) — Rust CLI ("swiss army knife"), a learning project with automated releases, a self-hosted Homebrew tap, and a Scoop bucket
