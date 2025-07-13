
# 🛠️ Database Engineer Journey (6-Month Roadmap)

This repository documents my transition from a MySQL DBA/DataOps Engineer to a full-fledged Database Engineer with reference material.

🔥 A curated list of awesome links related to Database Internals 
- [Introducton to Databases- Stanford DbClass](https://www.youtube.com/playlist?list=PLroEs25KGvwzmvIxYHRhoGTz9w8LeXek0)
- [Linkedin School of SRE- Linux, Databases ](https://linkedin.github.io/school-of-sre/level101/linux_basics/intro/)
- [How Indexes work](https://use-the-index-luke.com/sql/anatomy/)
- [Database Scaling](https://dev.to/kaustubhyerkade/maximizing-performance-best-practices-for-database-scaling-2fkn)
- [Transaction Isolation Levels](https://medium.com/@abhinav.23.april/understanding-transaction-isolation-levels-in-sql-databases-a-practical-guide-4abe98fd9f8e)
- [What is Database Sharding?](https://www.youtube.com/watch?v=XP98YCr-iXQ)
- [Best Practices for Database Scaling](https://dev.to/kaustubhyerkade/maximizing-performance-best-practices-for-database-scaling-2fkn)

  
- [Database Internals by Alex Petrov](https://www.oreilly.com/library/view/database-internals/9781492040330/)
- [Podcasts on Modern Databases](https://www.youtube.com/playlist?list=PLL7QpTxsA4scSeZAsCUXijtnfW5ARlrsN)
- [Whitepaper : Amazon DynamoDB](https://lnkd.in/djcQnzAG)
- [How Amazon S3 Works ](https://newsletter.systemdesign.one/p/s3-architecture)
- [How DNS works](https://newsletter.systemdesign.one/p/what-is-a-dns-server-and-how-does-it-work)
- [How Google Ads Was Able to Support 4.77 Billion Users With a SQL Database](https://newsletter.systemdesign.one/p/cloud-spanner-database)
  
## 🔍 Areas of Focus
- MySQL Internals & Tuning
- Cloud Databases: AWS RDS, Aurora, DynamoDB
- DevOps & Monitoring (Prometheus, Grafana)
- Schema Design, Partitioning, SQL Optimization
- Resiliency & PITR Testing
- Automation with Python & CI/CD

---

## 🗓️ Weekly Progress

| Week | Topic | Status | Key Link |
|------|-------|--------|----------|
| 1    | MySQL Architecture | ✅ Done | [Notes](./week01_mysql_architecture.md) |
| 9    | AWS RDS & Aurora | 🟡 In Progress | [Setup](./week09_rds_aurora.md) |

---

## 📦 Mini Projects

- [`mysql_pitr_tool`](./projects/mysql_pitr_tool): Point-in-time recovery automation
- [`aurora_failover_test`](./projects/aurora_failover_test): Simulate AWS Aurora failover with logs
- [`mysql_monitoring_stack`](./projects/mysql_monitoring_stack): Dockerized Prometheus + Grafana setup

---

## 🧠 Learning Notes

All weekly notes and references are stored under `/notes/` organized by week/topic.

---

## 🧪 Tools Used

| Category | Tools |
|----------|-------|
| Cloud    | AWS RDS, DynamoDB, Aurora |
| Monitoring | Prometheus, Grafana |
| Infra-as-Code | Terraform, GitHub Actions |
| Scripting | Python, Bash |
| DB Tools | MySQL Workbench, ProxySQL, Flyway |

---

## 📈 Certification Prep

- MySQL Implementation Associate 1Z0-922 -: ✅ Done
- MySQL 8.0 for Database Administrators: 🔄 In Progress

---

> 👋 Feel free to fork and follow along or contribute suggestions!
