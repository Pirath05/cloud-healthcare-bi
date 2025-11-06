# Cloud Healthcare BI Dashboard

This repository contains the Power BI dashboard developed as part of the Cloud Healthcare Unit project, a full data engineering and business intelligence pipeline built using Talend, Hadoop/Hive, and Power BI.

---

## 📊 Dashboard overview

| Page | Content |
|-------|---------|
| 1. Global Overview | KPIs on consultations, hospitalizations, deaths, satisfaction |
| 2. Consultations | Trends by establishment, diagnosis, healthcare professional |
| 3. Hospitalizations | Analysis by age, sex, diagnostic, time period |
| 4. Deaths | Geographic mortality visualization (map) |
| 5. Satisfaction | Regional comparison of satisfaction rates (2019–2020) |

---

## 🔗 Download the dashboard

Click below to download the `.pbix` file:

👉 **[Download Power BI dashboard (.pbix)](https://github.com/Pirath05/cloud-healthcare-bi/releases/download/v1.0/Nga.pbix)**

*(File size: 123 MB — requires Power BI Desktop to open)*

---

## 🛠️ Technologies used

| Layer | Stack |
|--------|-------|
| ETL / Integration | Talend for Big Data |
| Storage | Hadoop / Hive / HDFS |
| BI & Reporting | Microsoft Power BI (DAX, DirectQuery) |
| Network Access | Tailscale VPN + ODBC |
| Data Modeling | Constellation schema (facts + dimensions) |

---

## 👨‍💻 About the project

The dashboard is based on a medical data warehouse integrating multiple sources (PostgreSQL, CSV, FTP datasets) and provides national-scale analytics to support hospital decision-making.

The system enables the tracking of hospital activity, mortality, patient satisfaction, and medical performance over time.

---



