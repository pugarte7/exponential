**Best with:** Python · SQL · Apache Kafka · ClickHouse · Apache Airflow
**Familiar with:** Go · dbt · Snowflake · Kubernetes · Terraform · AWS

> 💡 **TL;DR** – I build real-time data platforms end to end. At Fever I own one holding 17 billion rows that answers ~3.3M queries a month at sub-second p95, fed by ~150M change events a day. I started as a robotics technician and wrote my first Python following a Udemy course, so most of what I know came from being curious enough to take things apart. What pulls my best work out of me is scale, knowing thousands of people are actually using the thing I built, plus a bit of pressure.

---

## About Pablo Ugarte

Senior Data Engineer in Spain, six years in. I started on a factory floor as a robotics technician and learned Python from a Nate Gentile course and FreeCodeCamp. Five companies later I am at Fever, working next to people far smarter than me, which is a job I could only dream about a few years ago.

Building is mostly curiosity for me. I spend my day in the terminal, so my free time goes into tweaking Neovim configs or breaking and fixing my Kubernetes homelab, just to see how things work underneath. The moment something works my head goes straight to what is next. It has never felt like forced ambition, it is just how I think.

### Main Achievements

- **Fever's real-time analytics platform.** Designed and built it on Tinybird and ClickHouse: 1.3 TB, 17 billion rows, ~3.3M queries a month at sub-second p95, ~1.4 PB scanned monthly.
- **33 Postgres tables streaming live.** Debezium CDC at ~150M change events a day, around 1B a week, mine from the Terraform-managed connector down to the serving endpoints.
- **A Redis layer that removed the ceiling on launches.** Built from scratch to decouple dashboard traffic from query load, so a big event can be watched by any number of people at once.
- **Code merged into Apache Airflow and Debezium.** The two tools I use most, so it felt fair.

### Most-Prideful Builds

| Project | Your role & stack | Impact / Demo |
|---------|------------------|---------------|
| **Fever real-time analytics platform** | Owner and sole designer • ClickHouse + Tinybird + Kafka + Debezium + Redis | 17B rows, 3.3M queries/mo, sub-second p95. Internal, walkthrough on request |
| **[CS skins trading bot](https://github.com/pugarte7/csgo2_skins_analytics)** | Solo • Python + Airflow + DynamoDB | Scrapes marketplaces and hunts arbitrage between them. Honest status: the algorithm is still wrong |
| **[spanish-top-tech-companies](https://github.com/pugarte7/spanish-top-tech-companies)** | Solo • Python + GitHub Actions | 261 companies mapped, 112 paying seniors 60k+. Open dataset, anyone can contribute |

### Experience (TL;DR)

- **Senior Data Engineer / Fever** – _Mar 2026 to now._ Own the real-time analytics platform, from CDC off 33 Postgres tables to sub-second serving and the Redis cache in front of it.
- **Senior Data Engineer / IFS** – _Jul 2025 to Mar 2026, Stockholm, remote._ Real-time platform for 10,000+ data entry points per second on Azure and Kubernetes, feeding analytics, ML models and alerting. Go microservices, Kafka and NiFi, Airflow across streaming and batch.
- **Data Engineer / Leadtech** – _Jul 2024 to Jul 2025, Barcelona, remote._ On the Macropay payment gateway. Brought Kafka in, migrated search from ElasticSearch to OpenSearch, built real-time ETL on Glue, Lambda and DynamoDB.
- **Data Engineer / Datu(a) IA** – _Jul 2023 to Aug 2024, Bilbao, remote._ ETLs for a client running 170 photovoltaic plants worldwide, pulling live data off thousands of solar panels. Designed and maintained the Kubernetes clusters and the Terraform behind them.
- **Software Engineer / i2U** – _Jan 2022 to Jul 2023, San Sebastián._ Automating overhead cranes in steel warehouses. Sensor data over OPC-UA into Python and Postgres, APIs in FastAPI and Flask, Siemens PLCs in TIA Portal.
- **Automation Engineer / iLine Microsystems** – _Nov 2019 to Jan 2022._ Where I wrote my first production Python, automating production-line maintenance.
- **Community** – Contributor to Apache Airflow and Debezium. Regular at meetups, summits and community days around Spain. Active on r/cscareerquestionsEU.

---

## How I Work

- **Gets me pumped:** Scale. Knowing thousands of people are using what I built brings out my best work. Add pressure or a hard problem and I feel genuinely alive.
- **Disappoints me:** Being handed a black box and told not to open it. If I cannot see how something works I cannot fix it at 3am.
- **Strengths:** Perseverance. I went from robotics technician to Senior Data Engineer through five companies and a lot of evenings, and that is the same way I get through a hard system.
- **Improvement points:** I move to the next thing too fast. I rarely stop to mark that something worked, which is not always the right call for a team.
- **Known behaviours / comms style:** Direct and short. I say what I know and what I do not. Happy to explain anything I built, in writing or in person.

---

## Other

### Some personal stuff

- Terminal first. Neovim, Kitty, and a Kubernetes homelab I keep breaking on purpose. Dotfiles at [pugarte7/dotfiles](https://github.com/pugarte7/dotfiles).
- I go to as many meetups, summits and community days around Spain as I can fit in. The energy of a live event is hard to beat.
- Currently losing a slow argument with a Counter-Strike skins trading bot.
- I think pay in Spanish tech should be public, so I built the dataset that makes it public.

### My vision

I want to keep building real-time platforms, with more scope than one team's roadmap allows. Spain and Europe are full of startups hitting the point where their data stops fitting in a Postgres query, and that is exactly the problem I have already solved at scale.

In five years I want to be the person a company brings in to build that layer from zero. I am proud of how far I have come and very aware of how much I still have left to learn, so the Fellowship is mostly about getting into rooms with people who are further along than me.
