# 🚀 InsightFlow – Customer Journey & Growth Analytics Platform

> **An enterprise-grade Growth Analytics platform that simulates customer journeys, marketing attribution, funnel analytics, and A/B experimentation for a modern fintech ecosystem.**

![Status](https://img.shields.io/badge/Status-In%20Development-success?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-red?style=for-the-badge&logo=streamlit)
![SQL](https://img.shields.io/badge/SQL-Analytics-orange?style=for-the-badge)

---

# 📌 Project Overview

**InsightFlow** is an end-to-end Product & Growth Analytics platform inspired by real-world analytics systems used by fintech companies such as PhonePe, Paytm, Razorpay, Groww, CRED, and Slice.

The platform simulates the complete customer lifecycle—from marketing acquisition to loan disbursal—and provides actionable insights through funnel analytics, attribution modeling, experimentation, and interactive dashboards.

The project follows enterprise software engineering and analytics engineering practices, including modular architecture, configuration-driven pipelines, validation frameworks, reproducible synthetic data generation, SQL analytics, and executive reporting.

---

# 🎯 Business Problem

A fictional fintech company, **PaisaOne**, spends over **₹12 Crore/month** on digital marketing across:

- Google Ads
- Meta Ads
- Affiliate Networks
- Influencer Campaigns

Despite attracting over **2 million app downloads**, only **0.4%** of users successfully receive loan disbursals.

The marketing team currently relies on **Last-Touch Attribution**, making it impossible to accurately identify which acquisition channels truly drive business value.

InsightFlow is designed to solve this challenge through data-driven analytics.

---

# 🎯 Project Objectives

- Build an enterprise-grade synthetic customer data platform
- Simulate realistic fintech customer journeys
- Analyze customer conversion funnels
- Compare marketing attribution models
- Evaluate A/B experiments statistically
- Build executive dashboards for business stakeholders

---

# 🚀 Core Features

## 📊 Synthetic Data Generation

- Enterprise synthetic data engine
- 100,000+ configurable customer records
- Configuration-driven architecture
- Weighted probability distributions
- Business-rule validation
- Reproducible datasets using random seeds

---

## 👤 Customer Profiles

Each generated user includes:

- Demographics
- Geography
- Occupation
- Monthly Income
- Credit Score (CIBIL)
- Device Type
- Acquisition Channel
- Registration Date

---

## 📈 Funnel Analytics *(Upcoming)*

- Customer Journey Funnel
- Stage Conversion Analysis
- Drop-off Diagnostics
- Cohort Analysis
- Customer Segmentation

---

## 🎯 Marketing Attribution *(Upcoming)*

Supported Models

- First-Touch Attribution
- Last-Touch Attribution
- Time-Decay Attribution

Business Metrics

- Marketing ROI
- Revenue Attribution
- Channel Performance
- Campaign Effectiveness

---

## 🧪 Experiment Analytics *(Upcoming)*

- A/B Testing Engine
- Lift Analysis
- Confidence Intervals
- Statistical Significance
- p-value Calculation
- Decision Recommendation

---

## 📊 Interactive Dashboard *(Upcoming)*

Built using Streamlit

Modules:

- Funnel Analytics
- Attribution Analytics
- Experiment Analytics

---

# 🏗️ Project Architecture

```text
Marketing Channels
        │
        ▼
Synthetic User Generator
        │
        ▼
Journey Simulation Engine
        │
        ├───────────────┐
        ▼               ▼
Marketing Events     App Events
        │               │
        └───────┬───────┘
                ▼
           Loan Events
                │
                ▼
         PostgreSQL Database
                │
                ▼
          SQL Analytics
                │
                ▼
       Business Intelligence
                │
                ▼
        Streamlit Dashboard
```

---

# 📂 Repository Structure

```text
InsightFlow/

├── config/
├── dashboard/
├── docs/
├── notebooks/
├── sql/
├── src/
│   └── data_generation/
├── tests/
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 💻 Technology Stack

### Programming

- Python

### Database

- PostgreSQL

### Data Processing

- Pandas
- NumPy

### Statistics

- SciPy
- Statsmodels

### Visualization

- Plotly

### Dashboard

- Streamlit

### Configuration

- YAML
- Pydantic

### Version Control

- Git
- GitHub

---

# 📅 Development Progress

## ✅ Sprint 1 – Business Discovery

- Business Requirements
- KPI Dictionary
- Stakeholder Analysis
- Event Tracking Specification
- Project Architecture

---

## ✅ Sprint 2 – Data Architecture

- Synthetic Dataset Design
- Business Rules
- Geography Mapping
- Validation Strategy
- Configuration Layer

---

## ✅ Sprint 3 – Synthetic User Generation Engine

Completed:

- Pydantic Configuration
- YAML Configuration
- Generator Factory
- Demographics Generator
- Geography Generator
- Customer Profile Generator
- Validation Framework
- Export Pipeline
- Automated Tests

### Generated Output

- ✅ 100,000 Synthetic Users
- ✅ Enterprise Validation Report
- ✅ 33 Automated Tests Passing

---

## 🚧 Current Sprint

Building the **Customer Journey Simulation Engine**

Upcoming datasets:

- marketing_events.csv
- app_events.csv
- loan_events.csv
- experiments.csv

---

# 📊 Current Progress

| Module | Status |
|----------|--------|
| Business Discovery | ✅ Complete |
| Data Modeling | ✅ Complete |
| Architecture | ✅ Complete |
| Synthetic User Engine | ✅ Complete |
| Journey Simulation | 🚧 In Progress |
| PostgreSQL Integration | ⏳ Planned |
| SQL Analytics | ⏳ Planned |
| Funnel Analytics | ⏳ Planned |
| Attribution Models | ⏳ Planned |
| Dashboard | ⏳ Planned |

---

# 🎯 Business Value

InsightFlow enables organizations to:

- Improve marketing ROI
- Reduce customer acquisition costs
- Identify funnel bottlenecks
- Compare attribution models
- Measure campaign effectiveness
- Evaluate A/B experiments
- Support executive decision-making

---

# 🔮 Roadmap

### Phase 1 ✅

- Business Design
- Synthetic User Engine

### Phase 2 🚧

- Journey Simulation
- Event Generation

### Phase 3

- PostgreSQL Database
- SQL Analytics

### Phase 4

- Funnel Analytics
- Attribution Models
- A/B Testing

### Phase 5

- Streamlit Dashboard
- Deployment
- Executive Business Memo

---

# 👨‍💻 Author

**Mohith Krishna**

B.Tech Computer Science Engineering (AI & Data Engineering)

Interested in:

- Data Analytics
- Product Analytics
- Business Intelligence
- Growth Analytics

**GitHub:** https://github.com/mohithkrishnaa

**LinkedIn:** https://linkedin.com/in/mohith-krishnaa

---

## ⭐ Project Status

🚧 **Active Development**

This repository documents the complete development lifecycle of an enterprise-style Growth Analytics platform—from business discovery and synthetic data engineering to SQL analytics, attribution modeling, experimentation, and business intelligence dashboards.
