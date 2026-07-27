# Sparsh Bhatnagar
### I turn messy data into decisions that businesses can act on.
**Data Analytics · SQL · Python · Power BI · Tableau · Open to Opportunities**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sparshbhatnagar-blue?style=flat&logo=linkedin)](https://linkedin.com/in/sparshbhatnagar)
[![Email](https://img.shields.io/badge/Email-sparsh.bhatnagar13@gmail.com-red?style=flat&logo=gmail)](mailto:sparsh.bhatnagar13@gmail.com)
[![Tableau](https://img.shields.io/badge/Tableau-Public-orange?style=flat&logo=tableau)](https://public.tableau.com)

---

## 📋 Table of Contents
- [👋 About Me](#-about-me)
- [🔍 What I Work On](#-what-i-work-on)
- [🛠️ Tools & Technologies](#-tools--technologies)
- [📁 Projects](#-projects)
- [🌱 Currently Learning](#-currently-learning)
- [📬 Let's Connect](#-lets-connect)
- [📊 GitHub Stats](#-github-stats)

---

## 👋 About Me

I'm a Data Analytics professional and MCA student specialising in Machine Learning & AI at Amity University, Noida.

My interest in data started simply — I wanted to understand why businesses make the decisions they do. Turns out, the answer is almost always hiding inside a dataset somewhere.

I recently completed an internship at DS Group (Dharampal Satyapal Group) — one of India's largest FMCG conglomerates — where I worked on their loyalty wallet platform serving 289,000+ active users. I wrote production SQL queries, cleaned large datasets, and built Tableau dashboards that went straight to executive stakeholders.

That experience taught me something important: good analytics isn't about the tools — it's about asking the right question first.

A few things that make my profile a little different:

- 🇩🇪 I hold a German B1 certification from Goethe-Institut — which I actively use in projects targeting European markets
- 🏭 My internship was in FMCG — a domain where data directly touches supply chains, pricing, and millions of end consumers
- 🔨 Every project on this profile is built from scratch — not downloaded, not template-filled

---

## 🔍 What I Work On

I don't just make charts. The work I do usually follows this pattern:

**Business Question → Data Pipeline → SQL / Python Analysis → Visual Insight → Recommendation**

That full cycle — from a raw CSV to a dashboard a manager can act on — is what I build through every project.

Where I spend most of my time:

- Writing SQL queries that answer real business questions — joins, window functions, CTEs, cohort analysis
- Cleaning messy data properly — not just dropping nulls, but understanding why they exist
- Building churn and segmentation models with scikit-learn
- Designing Power BI and Tableau dashboards that tell a story, not just display numbers

---

## 🛠️ Tools & Technologies

**Data & Analytics**

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-336791?logo=postgresql)
![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Tableau](https://img.shields.io/badge/Tableau-Desktop-orange?logo=tableau)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)
![Excel](https://img.shields.io/badge/Excel-Advanced-217346?logo=microsoftexcel)

**Python Libraries**

![Pandas](https://img.shields.io/badge/pandas-2.0-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.24-013243?logo=numpy)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Viz-4C72B0)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-ORM-red)

**Platforms & Tools**

![GitHub](https://img.shields.io/badge/GitHub-black?logo=github)
![pgAdmin](https://img.shields.io/badge/pgAdmin-4-336791?logo=postgresql)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode)
![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?logo=amazonaws)

---

## 📁 Projects

*Each project was built to answer a specific business problem — not just to demonstrate a tool.*

---

### ✈️ India Flight Delay Intelligence — End-to-End Analytics Project

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql)
![Python](https://img.shields.io/badge/Python-blue?logo=python)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas)
![matplotlib](https://img.shields.io/badge/matplotlib-11557c)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-measures-F2C811)

**The business problem:** India's domestic aviation sector moved 167 million passengers in 2025 — but growth is masking a punctuality crisis. Which airlines are declining? Which airports create bottlenecks? Which routes drive the most demand?

End-to-end aviation analytics pipeline on 11 years of DGCA data (2015–2026) built with an industry-level workflow:

- Ingested and cleaned 4 raw DGCA datasets — 67,220 rows across carrier, route, OTP, and daily tables
- Unpivoted wide-format daily data (one column per airline) into a long table using Python for proper Power BI filtering
- Built a PostgreSQL city-level traffic rollup using UNION ALL — combining origin + destination into a single airport footprint table
- Engineered 4 supporting dimension tables — DimAirline, DimMonth, DailyLong, airport_traffic — to resolve relationship conflicts in Power BI
- Wrote 9 DAX measures including YoY growth, market share %, Pareto cumulative share, and a cross-table OTP scorecard measure using LOOKUPVALUE + TREATAS
- Delivered a 5-page Power BI dashboard with 3 cross-page slicers, conditional formatting, and a custom dark-navy theme

**Key findings:**

| Finding | Value |
|---|---|
| Total passengers (2025) | 167.1 million across 1.14 million flights |
| YoY passenger growth (2024 → 2025) | +3.6% |
| IndiGo market share growth | 36.8% (2015) → 64.1% (2025) |
| Industry OTP (trailing 12 months) | 74.8% — below 80% benchmark hit in 2022 |
| Best punctuality airline — 2024 | Akasa Air — 80.9% |
| SpiceJet OTP trajectory (2021 → 2026) | 90.3% → 47% (collapse) |
| Airline-months below DGCA minimum | 25 of 35 (71%) in 2024 |
| Hub concentration | Top 3 airports carry 41% of all traffic |
| Busiest route (2015–2026) | Bengaluru → Delhi — 42.6M cumulative passengers |
| Peak travel month | December — 128M passengers |
| Unique routes tracked | 2,034 city-pairs across 179 airports |

8 business recommendations delivered — including operational review for SpiceJet, infrastructure prioritisation at top 6 hubs, and capacity expansion on under-served secondary corridors.

**Skills demonstrated:** end-to-end pipeline design · PostgreSQL database engineering · Python EDA · wide-to-long data transformation · Power BI star schema modelling · DAX time intelligence · business insight generation

---

### 💳 Credit Card Fraud Detection — End-to-End Analytics Project

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql)
![Python](https://img.shields.io/badge/Python-blue?logo=python)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0)
![matplotlib](https://img.shields.io/badge/matplotlib-11557c)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-red)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi)
![DAX](https://img.shields.io/badge/DAX-measures-F2C811)

**The business problem:** A financial institution needs to understand where, when, and why fraud is happening — and what to do about it.

End-to-end fraud analytics pipeline on 1,000 credit card transactions built with an industry-level workflow:

- Designed a PostgreSQL database with proper constraints, indexes, and KPI views
- Connected Python to PostgreSQL via SQLAlchemy and cleaned all 1,000 rows
- Engineered 8 new features — Age Group, Amount Bucket, Hour, Time of Day, Risk Flag
- Built 9 publication-quality charts using matplotlib and seaborn
- Delivered a 3-page Power BI dashboard with 6 cross-page slicers and DAX measures

**Key findings:**

| Finding | Value |
|---|---|
| Overall Fraud Rate | 49.1% (industry avg: 2%) |
| Highest Risk Category | Online Shopping — 62.3% |
| Strongest Predictor | ≥3 Failed Attempts — 75.6% fraud |
| International Fraud Rate | 61.6% |
| Highest Risk City | Chennai — 54.6% |
| Total Fraud Amount | $1,473,833 |
| Peak Fraud Hour | 7 PM |

8 business recommendations delivered — including real-time ML scoring, geo-velocity alerts, auto-card-lock after 3 failed attempts, and 3DS enforcement for online transactions.

**Skills demonstrated:** end-to-end pipeline design · SQL database engineering · Python EDA · Power BI dashboard · DAX · business insight generation

---

### 🛒 FMCG Customer Churn Intelligence Platform

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql)
![Python](https://img.shields.io/badge/Python-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn)
![Tableau](https://img.shields.io/badge/Tableau-orange?logo=tableau)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas)
![Random Forest](https://img.shields.io/badge/Random%20Forest-ML-green)

End-to-end churn analytics on 250,000 loyalty wallet users across 9 NCR Delhi hubs. Model flagged 75,210 high-risk users with ₹2.12 Crore in wallet revenue at stake.

---

### 🛍️ Zepto Product Analytics — SQL Case Study

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql)
![pgAdmin](https://img.shields.io/badge/pgAdmin-4-336791?logo=postgresql)
![SQL](https://img.shields.io/badge/SQL-pure-336791)

Pure SQL analysis of 3,732 SKUs across 14 quick-commerce categories. Found 453 out-of-stock products and clear pricing gaps in premium SKUs.

---

### 🚲 Bike Sales Analytics — Excel Dashboard

![Excel](https://img.shields.io/badge/Excel-Advanced-217346?logo=microsoftexcel)
![Pivot Tables](https://img.shields.io/badge/Pivot%20Tables-217346)
![Dashboard](https://img.shields.io/badge/Dashboard%20Design-217346)

Customer purchase analysis across 1,026 buyers in 3 global regions. Key finding: income gap between buyers and non-buyers is just $2,447 — age and commute matter far more.

---

## 🌱 Currently Learning

- Advanced Tableau — LOD expressions, parameter actions, story points
- Machine Learning fundamentals — clustering and time-series forecasting
- AWS Analytics services — building on Cloud Practitioner foundation
- Applying German B1 practically — European market datasets and DACH-focused analysis

---

## 📬 Let's Connect

I'm actively looking for Data Analyst / Business Intelligence / Data Science roles — full-time or internship — where the work involves real business problems, not just reporting.

I'm particularly interested in **FMCG, FinTech, MNCs, and E-Commerce** — or any organisation with European operations where my German language background adds genuine value.

If you're a recruiter, hiring manager, or fellow analyst — my inbox is always open.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/sparshbhatnagar)
[![Email](https://img.shields.io/badge/Email-sparsh.bhatnagar13@gmail.com-red?logo=gmail)](mailto:sparsh.bhatnagar13@gmail.com)

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Sparsh9876&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Sparsh9876&layout=compact&theme=tokyonight&hide_border=true)

---

📍 Ghaziabad, India &nbsp;·&nbsp; 🎓 MCA — ML & AI, Amity University, Noida &nbsp;·&nbsp; 🇩🇪 German B1 — Goethe-Institut
