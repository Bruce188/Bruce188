# Bruce

**Student** at Odisee University College

Specializing in **Data & AI**, **System & Business Analysis**, and **System Administration**
with additional coursework in Networking & Cybersecurity and Advanced Software Development

## Certifications

- **CCST Networking** (Cisco)

## Technologies & Tools

![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/-.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/-ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/-Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL_Server-CC2927?style=flat-square&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Entity Framework](https://img.shields.io/badge/-EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SignalR](https://img.shields.io/badge/-SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logoColor=white)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![xUnit](https://img.shields.io/badge/-xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/-Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/-Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![React](https://img.shields.io/badge/-React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![LanceDB](https://img.shields.io/badge/-LanceDB-1E40AF?style=flat-square&logoColor=white)
![Anthropic](https://img.shields.io/badge/-Anthropic-D4A27A?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logoColor=white)
![uv](https://img.shields.io/badge/-uv-DE5FE9?style=flat-square&logoColor=white)

## Featured Projects

### CryptoBargain · private
Autonomous perpetual-futures trading system — Python, on-chain order signing, FastAPI + React 19 ops dashboard
- Risk-first design: hard no-liquidation constraint, enforced by controls that can only reduce exposure
- Cost-aware walk-forward research harness
- systemd-managed live deployment with operator alerting
- Source and strategy are private

### [Castellum](https://github.com/Bruce188/castellum)
Network topology and vulnerability mapper — Spring Boot 3.5 / Java 21 (virtual threads), React 19 + Vite + TypeScript
- Active nmap scanning (argv-only, injection-hardened) + passive pcap4j/ARP/mDNS/LLDP/CDP discovery
- OT/ICS read-only fingerprinting (Modbus/TCP, DNP3, S7comm, BACnet/IP) with function-code whitelist
- Threat-intel pipeline: NVD mirror (~250k CVEs), EPSS daily, CISA KEV → composite CVSS×EPSS×KEV×criticality risk score
- JGraphT attack-graph shortest path with ATT&CK technique edge annotation
- STIX 2.1 bundle export, TAXII 2.1 + MISP push
- Docker container discovery: local CLI, read-only host probe of Docker Engine and adjacent container-platform APIs (flags exposed :2375 daemons as CRITICAL), token-authenticated remote push agent
- JWT HS256 + BCrypt-12, per-IP login rate-limiting, append-only audit log, distroless runtime, CAP_NET_RAW only (no `--privileged`)
- NIST 800-53 control mapping (AC/AU/CM/IA/RA/SC/SI/SR), AAP-31 vocabulary cross-walk

### [debouw](https://github.com/Bruce188/debouw)
Multi-source data-ingestion project: Belgian construction permit risk monitoring prototype — Python 3.12 (uv), Pydantic v2, SQLAlchemy 2.0 async, LanceDB, Streamlit
- Multi-source ingestion pipeline: Gent consultatieomgeving, Brussels OpenPermits (CoBAT), Vlaanderen Inzageloket (Playwright headed Chromium for Anubis-protected pages), RvVb precedent corpus
- Risk engine combining 14 deterministic rule categories with an LLM narrator (Anthropic Sonnet, GPT-4o fallback) and RvVb precedent retrieval over LanceDB (OpenAI text-embedding-3-large)
- Geopunt WMS/WFS spatial overlays, Lambert-72 to WGS84 geometry (pyproj), IIOA/MER heuristics, PDF feature extraction (pdfplumber)
- structlog JSON/console logging, alembic migrations, SQLite WAL, tenacity retry + circuit-breaker, throttled httpx HTTP client
- GDPR posture: no applicant names persisted, identified User-Agent, polite per-source rates, schema-drift lock tests
- 317 tests (314 passing) · 77% coverage

### [hsnotes](https://github.com/Bruce188/hsnotes)
High-security Android notes app — Kotlin + Compose, defense-in-depth at rest
- Argon2id KEK (RFC 9106, calibrated per device) → random DEK double-wrapped (KEK + Keystore key) → SQLCipher 4.6.1 encrypted DB
- Wipe ladder (lock / crypto-erase / nuclear), panic PIN, 14-day dead-man check with HMAC attested clock
- Encrypted backup envelope: HSBK magic + Argon2id + AES/GCM + 4 KiB padding (file size only reveals a 4 KiB bucket)
- FLAG_SECURE recents blanking, CharArray passphrase hygiene, Detekt-enforced ban on `android.util.Log`
- Anti-oracle UI: collapses all auth failures to one indistinguishable error

### [ApexOmni Daily Trading Bot](https://github.com/Bruce188/apex_omni_daily_trader)
Perpetual-futures trading bot for ApexOmni staking-factor optimization — Python 3.11+, Docker Compose, signed orders
- Maximizes Trading Activity Factor (+0.5) by trading 5 unique days/week with auto-selected cheapest tradeable symbol against current balance
- Ethereum key → ZK seeds / L2 key derivation helper for order signing; explicit testnet/mainnet network split with dry-run default and `--live` gate
- Hardcoded safety: minimum-size orders and a mandatory opposite-side market close right after every open, retried up to 5 times; circuit breaker (hardcoded 5-failure threshold)
- Once-per-UTC-day trade guard persisted in `data/trades.json`
- Runs via Docker Compose (health checks, graceful shutdown, log rotation) or can run as a scheduled daily GitHub Actions job
- 210 tests across unit, integration, and security suites

### [pipelinekit](https://github.com/Bruce188/pipelinekit)
Claude Code config kit — guard hooks, a few skills and an installer that overlays `~/.claude` in place, devcontainer-ready
- v0.1.0 cut the earlier multi-agent `/pipeline` kit down to what current Claude Code doesn't ship natively (plan mode, subagents, `/code-review` and auto-memory replaced the rest)
- 9 guard hooks: conventional-commit validation, sensitive-file staging block, dangerous-command block, push-to-main block, protected-file edit block, bare-repo marker block, CI secret-env scrub, post-edit formatting, prompt-injection warning on fetched content; plus native git commit-msg and gitleaks pre-commit hooks
- 7 skills: commit / security / .NET conventions, a single `deploy` skill for Azure, Vercel, Railway, Render and DigitalOcean, Expo, iOS, and a docs-writer that renders self-contained HTML docs
- MCP: serena installed at a pinned commit (`SERENA_REF`); context7 optional
- Idempotent installer: merges hook wiring into `settings.json`, prunes stale entries, turns commit/PR attribution off
- GitHub Codespaces / devcontainer entry point: open in container → post-create runs install.sh → `claude`

## Experience

**Super User** | UPS Belgium - Customs Brokerage Department
- Conducted UAT testing, code reviews, and participated in agile standups
- Built department-wide SharePoint documentation system
- Created technical instruction documents for development teams

## Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logoColor=white)](https://www.linkedin.com/in/bruce-shema-09b79a12a/)
