# Bruce

**Student** at Odisee University College

Specializing in **Data & AI**, **System & Business Analysis**, and **System Administration**
Additional coursework in Networking & Cybersecurity and Advanced Software Development

## Certifications

- **CCST Networking** (Cisco)

## Technologies & Tools

![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/-.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/-ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/-Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Entity Framework](https://img.shields.io/badge/-EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SignalR](https://img.shields.io/badge/-SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Web3](https://img.shields.io/badge/-Web3.py-F16822?style=flat-square&logo=web3dotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
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
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![uv](https://img.shields.io/badge/-uv-DE5FE9?style=flat-square&logoColor=white)

## Featured Projects

### [debouw](https://github.com/Bruce188/debouw)
Multi-source data-ingestion project: Belgian construction permit risk monitoring prototype — Python 3.12 (uv), Pydantic v2, SQLAlchemy 2.0 async, LanceDB, Streamlit
- Multi-source ingestion pipeline: Gent open data, Brussels CoBAT, Vlaanderen Inzageloket (Playwright headed Chromium for Anubis-protected pages), Geopunt spatial overlays, RvVb precedent corpus
- Risk engine combining deterministic rules with Claude Sonnet narrator and RvVb precedent retrieval over LanceDB (OpenAI text-embedding-3-large)
- Geopunt spatial overlays, Lambert-72 geometry, IIOA/MER heuristics, PDF feature extraction (pdfplumber)
- structlog JSON-in-prod logging, alembic migrations, SQLite WAL, tenacity retry + circuit-breaker, httpx + crawl4ai HTTP stack
- GDPR posture: salted-hash PII, identified User-Agent, polite per-source rates, schema-drift lock tests
- 314 tests · 80%+ coverage · pipeline-driven workflow (analyze → plan → implement → review → merge)

### [Castellum](https://github.com/Bruce188/castellum)
NATO-track network topology and vulnerability mapper — Spring Boot 3.5 / Java 21 (virtual threads), React 19 + Vite + TypeScript
- Active nmap scanning (argv-only, injection-hardened) + passive pcap4j/ARP/mDNS/LLDP discovery
- OT/ICS read-only fingerprinting (Modbus/TCP, DNP3, S7comm, BACnet/IP) with function-code whitelist
- Threat-intel pipeline: NVD mirror (~250k CVEs), EPSS daily, CISA KEV → composite CVSS×EPSS×KEV×criticality risk score
- JGraphT attack-graph shortest path with ATT&CK technique edge annotation
- STIX 2.1 bundle export, TAXII 2.1 + MISP push (NCIRC-compatible)
- JWT HS256 + BCrypt-12, append-only audit log, distroless runtime, CAP_NET_RAW only (no `--privileged`)
- NIST 800-53 control mapping (AC/AU/CM/IA/RA/SC/SI/SR), AAP-31 vocabulary cross-walk

### [FundingRateArb](https://github.com/Bruce188/FundingRateArb)
Automated funding rate arbitrage bot for perpetual futures — .NET 8, Clean Architecture
- Monitors funding rate differentials across DEXs (Lighter, Aster) and CEXs (HyperLiquid)
- Real-time dashboard with SignalR WebSocket updates and KPI tracking
- Polly resilience pipelines, position health monitoring, and emergency close
- CI/CD with GitHub Actions, Docker multi-stage builds, and Azure deployment via OIDC
- Unit, integration, and E2E tests (xUnit, Playwright)

### [hsnotes](https://github.com/Bruce188/hsnotes)
High-security Android notes app — Kotlin + Compose, defense-in-depth at rest
- Argon2id KDF (RFC 9106, calibrated per device) → Keystore-bound DEK wrap → SQLCipher 4.6.1 encrypted DB → Tink AEAD prefs
- 4-level wipe ladder (lock / soft / crypto-erase / nuclear), panic PIN, dead-man HMAC attested clock
- Encrypted backup envelope: HSBK magic + Argon2id + AES/GCM + 4 KiB padding (size-blind to note count)
- FLAG_SECURE recents blanking, CharArray passphrase hygiene, Detekt-enforced ban on `android.util.Log`
- Anti-oracle UI: collapses all auth failures to one indistinguishable error

### [ApexOmni Daily Trading Bot](https://github.com/Bruce188/apex_omni_daily_trader)
Perpetual-futures trading bot for ApexOmni staking-factor optimization — Python 3.11, Docker Compose, ZK-signed orders
- Maximizes Trading Activity Factor (+0.5) by trading 5 unique days/week with auto-selected cheapest tradeable symbol against current balance
- ZK seed → L2 key derivation for on-chain order signing; explicit testnet/mainnet network split with `DRY_RUN` gate
- Hardcoded safety invariants: 1× cross margin only, immediate position closing — eliminates leverage and overnight market exposure
- Circuit breaker (configurable failure threshold + reset window) with continuous-mode daemon scheduling (4h interval default)
- Production deployment via Docker Compose with health checks, graceful shutdown, and structured logs
- 210 tests across unit, integration, and security suites

## Experience

**Super User** | UPS Belgium - Customs Brokerage Department
- Conducted UAT testing, code reviews, and participated in agile standups
- Built department-wide SharePoint documentation system
- Created technical instruction documents for development teams

## Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bruce-shema-09b79a12a/)
