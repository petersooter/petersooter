## Hi there 👋

**I build systems at the intersection of enterprise software and customer outcomes.**

Forward-deployed engineer and CS infrastructure architect. I spend my days embedding with enterprise customers, diagnosing operational failures, and building the automation that fixes them, usually before anyone thought to ask for it. Currently at [Leaf Agriculture](https://withleaf.io), an agtech Series B where agricultural data infrastructure meets farm-level decision-making.

Fluent in English, Portuguese, and Spanish.

---

## What I'm building

### [leaf-brain](https://github.com/petersooter/leaf-brain)
A 16-agent autonomous AI operating system I built to run Customer Success operations without me initiating any of it. Integrates Gmail, Calendar, Slack, Granola, Salesforce, and Google Sheets. Fires 16 scheduled processes via macOS launchd. At its core: a 7-signal composite churn scoring model and a K-Shape Divergence framework for early account trajectory detection. Eliminated 40+ hours/week of manual processing.

> `Python` `Claude API` `launchd` `Salesforce` `Google Workspace` `Slack`

### [demand-forecasting-api](https://github.com/petersooter/demand-forecasting-api) — [Live Demo](https://demand-forecasting-api-ig88.onrender.com/docs)
FastAPI endpoint serving demand forecasts from a scikit-learn GradientBoosting model. 14-feature input, point forecast with 80% confidence interval output. Containerized with Docker, deployed and live. Built to demo the FDE motion: here is a working solution, here is the business problem it solves, here is how to run it in your environment.

> `Python` `FastAPI` `scikit-learn` `Docker`

### [customer-health-os](https://github.com/petersooter/customer-health-os)
Python implementation of the 7-signal churn scoring model powering leaf-brain. Self-contained: accepts a CSV of account signals, outputs risk scores, confidence levels, and recommended interventions. Calibrated against real post-mortems.

> `Python` `pandas` `scikit-learn`

### [k-shape-divergence](https://github.com/petersooter/k-shape-divergence)
Account trajectory analysis module. Takes engagement timeseries data and classifies accounts as accelerating toward value or stalling toward churn, within the first 60 days, before divergence becomes irreversible.

> `Python` `pandas` `numpy`

### [meeting-quality-framework](https://github.com/petersooter/meeting-quality-framework)
10-dimension meeting quality scoring system with trend tracking, rolling averages, and low-value streak alerts. CLI for interactive scoring and portfolio reporting. Triggers intervention prompts when three consecutive meetings fall below threshold.

> `Python` `CLI`

### [crop-insurance-data-analysis](https://github.com/petersooter/crop-insurance-data-analysis)
The analysis that saved a $76K contract in 3 days. 341K+ data points, no engineering support. Documented as a reproducible Jupyter notebook demonstrating Leaf's data accuracy within 3.7% of the industry baseline vs the client's own tool at 8.2%.

> `Python` `Jupyter` `pandas` `matplotlib`

### [automotive-etl-pipeline](https://github.com/petersooter/automotive-etl-pipeline)
Production ETL pipeline built for a global automotive manufacturer. Ingests complex daily data dumps from multiple source formats, normalizes and transforms into production-ready analytical datasets, and outputs to BI reporting layers. Handles schema inconsistencies, failed delivery recovery, and incremental loading across high-volume daily runs.

> `Python` `pandas` `SQL`

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Claude API](https://img.shields.io/badge/Claude_API-CC785C?style=flat&logo=anthropic&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Background

15+ years running enterprise CS and technical operations across SaaS, agtech, and CX platforms. The through-line isn't the industry. It's always been the same thing: diagnose what's broken operationally, build the infrastructure to fix it, make it run without babysitting.

At Worthix I built the full CS org from zero: 30+ CSMs, the training curriculum, the health scoring system, and the Power BI dashboards that replaced 5 weekly status meetings. At Leaf I inherited a manual operation and turned it into leaf-brain. The work is always the same. Figure out what shouldn't require a human, then build the thing that doesn't.

---

## Links

[petersooter.dev](https://petersooter.dev) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/peter-sooter-51254935/) &nbsp;·&nbsp; Atlanta, GA
