**Best with:** Python · SQL · Apache Kafka · ClickHouse · Apache Airflow
**Familiar with:** Go · dbt · Snowflake · Spark · Kubernetes · Terraform · AWS

> 💡 **TL;DR** – I build real-time data platforms end to end, from the moment a row changes in Postgres to a dashboard answering in under a second. At Fever I own a platform holding 17 billion rows and serving 3.3M queries a month at sub-second p95, fed by ~150M change events a day. My super-power is taking the whole path instead of a slice of it: the Debezium connector, the Kafka ACLs, the materialised views, the cache, the backfill that has to reconcile to the row. I started out programming PLCs on a factory floor, which is where I learned that a system nobody can debug at 3am is not finished. What drives me is owning something whole.

---

## About Pablo Ugarte

Senior Data Engineer, based in Spain, six years in. I started automating production lines with Python, PLCs and robots, spent a year and a half making overhead cranes in steel warehouses talk to a backend, and then moved through ETL into streaming. Now I spend my days on Kafka, Debezium, ClickHouse, Snowflake and dbt.

Most of my career has been real-time data coming off something physical: solar panels, cranes, production lines, and now millions of people buying tickets. What I enjoy is the unglamorous half of the job. The connector that cannot drop a row. The historical backfill that has to reconcile against the source. The caching layer that keeps a launch alive when all the traffic arrives at once.

Kubernetes is the part of the stack I keep going deepest into, and I care a lot about engineering communities. I work in Neovim and Kitty and I read other people's infrastructure for fun.

### Main Achievements

- **Built Fever's real-time analytics platform.** Designed and shipped it on Tinybird and ClickHouse: ~1.3 TB and 17 billion rows under management, ~3.3M queries a month at sub-second p95, ~1.4 PB scanned monthly.
- **Owned Postgres to serving, end to end.** 33 tables streaming through Debezium CDC at ~150M change events a day, around 1B a week, from the Terraform-managed connector and Kafka ACLs all the way to ClickHouse materialised views and the endpoints that serve them.
- **Removed the ceiling on concurrent viewers.** Built a Redis caching layer from scratch that decouples dashboard traffic from Tinybird query load, so a big event launch serves any number of viewers at once instead of fanning out into queries.
- **Ran 170 photovoltaic plants' worth of telemetry.** Real-time ETLs collecting from thousands of solar panels worldwide into Postgres and Cassandra, on Kubernetes clusters I designed and maintained myself.
- **Certified across the stack I actually use:** AWS Solutions Architect Associate, Snowflake SnowPro Core, Certified Kubernetes Application Developer, Azure Data Engineer Associate.

### Most-Prideful Builds

| Project | Your role & stack | Impact / Demo |
|---------|------------------|---------------|
| **Fever real-time analytics platform** | Owner and sole designer • ClickHouse + Tinybird + Kafka + Debezium + Redis | 17B rows, 3.3M queries/mo, sub-second p95, 1.4 PB scanned monthly. Internal, walkthrough on request |
| **[spanish-top-tech-companies](https://github.com/pugarte7/spanish-top-tech-companies)** | Solo • Python + YAML + GitHub Actions | 261 companies mapped, 112 paying seniors 60k+. Open dataset, CI-validated, open to contributions |
| **[AgentLayer](https://github.com/pugarte7/AgentLayer)** | Solo • Cloudflare Workers + FastAPI + Postgres + Redis | Edge layer that tells AI agents from humans and rewrites what agents get, so publishers still get paid when nobody visits the page |

### Experience (TL;DR)

- **Senior Data Engineer / Fever** – _Mar 2026 to present._ Own the real-time analytics platform end to end, from CDC off 33 Postgres tables to sub-second serving. ClickHouse, Tinybird, Kafka, MSK, Debezium, Redis, Snowflake, dbt, Airflow, Terraform.
- **Senior Data Engineer / IFS** – _Jul 2025 to Mar 2026, Stockholm, remote._ Built a high-throughput real-time platform handling 10,000+ data entry points per second on Azure and Kubernetes, feeding analytics, ML models and custom alerting. Go microservices with schema enforcement, Kafka and NiFi for ingestion, Airflow across streaming and batch, lifecycle policies moving data between hot and cold storage.
- **Data Engineer / Leadtech** – _Jul 2024 to Jul 2025, Barcelona, remote._ On the Macropay payment gateway. Brought Kafka in for real-time streaming, migrated search from ElasticSearch to OpenSearch and refactored the Lambda functions behind bulk operations, built real-time ETL on Glue, Lambda and DynamoDB, added monitoring on CloudWatch and Grafana.
- **Data Engineer / Datu(a) IA** – _Jul 2023 to Aug 2024, Bilbao, remote._ ETLs for a client running 170 photovoltaic plants worldwide, pulling real-time data off thousands of solar panels into Postgres and Cassandra. Designed and maintained the Kubernetes clusters and the Terraform behind them.
- **Software Engineer / i2U** – _Jan 2022 to Jul 2023, San Sebastián._ Automating overhead cranes in steel warehouses. Sensor data through OPC-UA into Python and Postgres, REST APIs in FastAPI and Flask, Siemens PLCs programmed in TIA Portal.
- **Automation Engineer / iLine Microsystems** – _Nov 2019 to Jan 2022._ Automated production-line maintenance with Python. Omron PLCs, ABB robotics, Modbus, PROFINET.
- **Open source and community** – Maintain an open salary dataset for engineers in Spain, plus Neovim tooling and dotfiles. Active in local engineering communities.

---

## How I Work

- **Gets me pumped:** Owning a system whole instead of a ticket inside it. Problems where the answer is not on the internet yet. Watching a p95 drop after a week spent on a query pattern nobody wanted to touch.
- **Disappoints me:** Work handed over in slices, where nobody can say what happens after their part. Meetings that replace a decision instead of making one. Numbers everyone quotes and nobody has ever checked against the source.
- **Strengths:** End-to-end ownership across the whole path, infrastructure included. I sit comfortably at the boundary between data and platform, so I fix the Kubernetes and Terraform side instead of filing a ticket for it. Calm when something is on fire at scale.
- **Improvement points:** I go deep before I ask, which sometimes costs a day I could have saved with one question. Working on writing things down earlier so the context lives outside my head.
- **Known behaviours / comms style:** Direct and short. I say what I know and what I do not. Async and in writing by default, with the numbers attached. I would rather show you the dashboard than describe it.

---

## Other

### Some personal stuff

- [Hobbies, sports, what you do away from a screen]
- [Values or worldview, in a line or two]
- Terminal-first. Neovim and Kitty, dotfiles in the open at [pugarte7/dotfiles](https://github.com/pugarte7/dotfiles).
- I think pay in Spanish tech should be public, so I built the dataset that makes it public.

### My vision

I want to keep building real-time platforms, but with more scope than one team's roadmap allows: the kind of ownership where the architecture, the cost and the product decision sit with the same person. Spain and Europe are full of startups hitting the wall where their data stops fitting in a Postgres query, and that transition is exactly the thing I have already done at scale, twice.

In five years I want to be the person a company brings in to build that layer from zero, and to have kept giving the open parts of it back. The Fellowship is the fastest way I know to be in the room with the founders doing that work, instead of applying through a form.
