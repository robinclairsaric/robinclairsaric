<h1 align="center">Robin Clair-Saric</h1>

<p align="center">
  Quantitative trader · Rust systems engineer
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tokio-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

---

### About

- Quantitative trader at a hedge fund.
- Designing and building a proprietary trading system, from market-data ingestion to order execution.
- Background in finance and engineering: HEC Paris × IMT Atlantique.

### Areas of work

- **Trading systems in Rust** — hexagonal architecture, domain-driven design, CQRS, event-driven pipelines.
- **Cross-venue, multi-asset execution** — centralized and decentralized exchanges and a TradFi brokerage,
  unified behind one domain model.
- **Pricing** — options (Black-Scholes, implied volatility, term structure), perpetual funding, outcome
  pricing, and cost models that refuse to trade rather than guess when an input is missing.
- **Performance engineering** — allocation-free hot paths, Criterion-measured changes.

### Tech

| | |
|---|---|
| **Languages** | Rust · Python |
| **Services** | Tokio · axum (REST) · tonic (gRPC) · PostgreSQL (sqlx) |
| **Trading** | market microstructure · order-book engines · derivatives and outcome pricing · EVM and Solana integration |
| **Practice** | `tracing` observability · Criterion benchmarks · property-based testing · Docker |

### Featured project — Argos

A cross-venue trading engine written in Rust. Venues and strategies are adapters behind ports, so either
can be added without modifying the tested core; every strategy goes through the same pre-trade risk
checks and the same cost model.

| | |
|---|---|
| **Venues** | 22 venue adapters — CEX, DEX and TradFi brokerage |
| **Codebase** | ~1.62M lines of Rust in 2,044 files |
| **Tests** | 26,069 unit and async test functions · 72 property-based test blocks |
| **Benchmarks** | 76 Criterion benchmark programs |
| **Status** | pre-production |

<sub>Figures counted from the source tree (snapshot of 2026-11-05) with the same definitions as before, over the Rust workspace.</sub>

The source is private. An architecture and code walkthrough is available under NDA on request.

---

### Contact

<p align="center">
  <a href="https://www.linkedin.com/in/robin-clair-saric-461326206"><img src="https://img.shields.io/badge/LinkedIn-Robin_Clair--Saric-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:robinclair24@gmail.com"><img src="https://img.shields.io/badge/Email-robinclair24@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>
