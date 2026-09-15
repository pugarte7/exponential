**Best with:** Python · SQL · Apache Kafka · AWS · Apache Airflow
**Familiar with:** Go · dbt · Snowflake · Kubernetes · Terraform · Clickhouse

> 💡 **TL;DR** – I build real-time data platforms end to end. At Fever I own one holding 17 billion rows that answers ~3.3M queries a month at sub-second p95, fed by ~150M change events a day. I started as a robotics technician and wrote my first Python following a Udemy course, so most of what I know came from being curious enough to take things apart. What pulls my best work out of me is scale, knowing thousands of people are actually using the thing I built, plus a bit of pressure.

---

## About Pablo Ugarte

Senior Data Engineer in Spain, seven years in. I started on a factory floor as a robotics technician and learned Python from a Nate Gentile course and FreeCodeCamp. Five companies later I am at Fever, working next to really bright people far smarter than me, which is a job I could only dream about a few years ago.

Building is mostly curiosity for me. I spend my day in the terminal, so my free time goes into tweaking Neovim configs or breaking and fixing my Kubernetes homelab, just to see how things work underneath. The moment something works, my head goes straight to what is next. 

On a personal side, I am a cinephile, I love cooking (and eating), I'm a wannabe good chess player, and I love training. I've also started climbing—there are just many things that I want to learn and do.

### Main Achievements

- **Fever's real-time analytics platform.** Designed and built it on Tinybird and ClickHouse: 1.3 TB, 17 billion rows, ~3.3M queries a month at sub-second p95, ~1.4 PB scanned monthly.
- **33 Postgres tables streaming live.** Debezium CDC at ~150M change events a day, around 1B a week, mine from the Terraform-managed connector down to the serving endpoints.
- **A Redis layer that removed the ceiling on launches.** Built from scratch to decouple dashboard traffic from query load, so a big event can be watched by any number of people at once.
- **Contributed to Apache Airflow and Debezium.** The two tools I use most, so it felt fair.

### Proudest Builds

| Project | Your role & stack | Impact / Demo |
|---------|------------------|---------------|
| **Fever real-time analytics platform** | Owner and sole designer • ClickHouse + Tinybird + Kafka + Debezium + Redis | 1.3 TB and 17B rows, 3.3M queries/mo at sub-second p95, 1.4 PB scanned monthly. Walkthrough on request. |
| **IFS high-throughput streaming platform** | Pipeline architect and Go developer • Azure + Kubernetes + Kafka + NiFi + Airflow | 10,000+ data entry points per second feeding analytics, ML models and alerting. Hot to cold lifecycle policies cut storage cost. |
| **Solar telemetry pipeline at Datu(a)** | Owned pipelines and infra • Python + Airflow + Kubernetes + Terraform + Cassandra | Live data off thousands of panels across 170 photovoltaic plants worldwide. |

### Experience (TL;DR)

- **Senior Data Engineer / Fever** – _Mar 2026 to now, remote._ Own the real-time analytics platform, from CDC off 33 Postgres tables to sub-second serving and the Redis cache in front of it.
- **Senior Data Engineer / IFS** – _Jul 2025 to Mar 2026, Stockholm, remote._ Real-time platform for 10,000+ data entry points per second on Azure and Kubernetes, feeding analytics, ML models and alerting. Go microservices, Kafka and NiFi, Airflow across streaming and batch.
- **Data Engineer / Leadtech** – _Jul 2024 to Jul 2025, Barcelona, remote._ On the Macropay payment gateway. Brought Kafka in, migrated search from ElasticSearch to OpenSearch, built real-time ETL on Glue, Lambda and DynamoDB.
- **Data Engineer / Datu(a) IA** – _Jul 2023 to Aug 2024, Bilbao, remote._ ETLs for a client running 170 photovoltaic plants worldwide, pulling live data off thousands of solar panels. Designed and maintained the Kubernetes clusters and the Terraform behind them.
- **Software Engineer / i2U** – _Jan 2022 to Jul 2023, San Sebastián._ Automating overhead cranes in steel warehouses. Sensor data over OPC-UA into Python and Postgres, APIs in FastAPI and Flask, Siemens PLCs in TIA Portal.
- **Automation Engineer / iLine Microsystems** – _Nov 2019 to Jan 2022._ Where I wrote my first production Python, automating production-line maintenance.
- **Community** – Contributor to Apache Airflow and Debezium. Regular at meetups, summits and community days around Spain. Active on r/cscareerquestionsEU.

---

## How I Work

- **Gets me pumped:** Scale. Knowing thousands of people are using what I built brings out my best work. Add pressure or a hard problem and I feel genuinely alive.
- **Disappoints me:** Bureaucracy. I love being agile, so obviously I dislike working for big enterprises where things are usually super bureaucratic and slow.
- **Strengths:** Perseverance. I went from robotics technician to Senior Data Engineer through five companies and a lot of evenings. I am extremely stubborn (*soy un cabezón*)—when I set my mind to something, I achieve it.
- **Improvement points:** I move to the next thing too fast. I rarely stop to mark that something worked, which is not always the right call for a team.
- **Known behaviours / comms style:** Direct and short. I say what I know and what I do not. Happy to explain anything I built, in writing or in person.

---

## Other

### Some personal stuff

- Terminal first. Neovim, Kitty, and a Kubernetes homelab I keep breaking on purpose. Dotfiles at [pugarte7/dotfiles](https://github.com/pugarte7/dotfiles).
- I go to as many meetups, summits and community days around Spain as I can fit in. The energy of a live event is hard to beat.
- Love cooking, watching films, gym training, running, and getting into bouldering.
- Obsessed with geopolitics, the economy, and understanding global conflicts.

### My vision

I want to keep building real-time platforms, with more scope than one team's roadmap allows. I love startup culture and highly dynamic companies. I need some pressure to be at 100%.

In five years I want to be the person a company brings in to build that layer from zero. I am proud of how far I have come and very aware of how much I still have left to learn.
