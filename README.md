# Omnichannel Marketing Campaign & Audience Performance Dashboard

## Project Overview
This end-to-end Business Intelligence project analyzes marketing campaign data to evaluate cross-channel efficiency and audience demographic performance. The objective is to transform raw SQL database tables into an interactive, executive-ready dashboard that assists stakeholders in optimizing budget allocation and maximizing Return on Ad Spend (ROAS).

The project covers the complete data pipeline: **Extraction (SQL)**, **Data Cleaning & Engineering (Excel)**, and **Interactive Visualization (Power BI)**.

---

## Tech Stack & Methodology

### 1. Data Extraction & Transformation (SQL)
* Aggregated raw marketing logs to compute core baseline metrics grouped by communication channel and target demographic.
* Consolidated campaign performance into two structured datasets: Channel Performance and Audience Performance.

### 2. Data Cleaning & Metric Engineering (Excel)
* Applied advanced text and data-cleaning functions (`TRIM`, formatting corrections) to sanitize the exported datasets.
* Engineered critical performance KPIs using the following data models:
  * **Click-Through Rate (CTR):** `[Total Clicks] / [Total Impressions]`
  * **Revenue Per Campaign:** `[Total Revenue] / [Total Campaigns]`
  * **Return on Ad Spend (ROAS):** `[Total Revenue] / ([Total Campaigns] * [Avg Acquisition Cost])`

### 3. Data Visualization & Storytelling (Power BI)
* Built a two-page dynamic workspace on Power BI Service focused on executive readability and operational metrics.
* Implemented **Top N visual filters** to isolate underperforming versus high-growth marketing combinations.

---

## Strategic Insights & Key Takeaways

### Page 1: Channel Performance & Financial Efficiency
* **Revenue Leaders:** **WhatsApp** and **Facebook** generate the highest absolute revenue volume, leading the ecosystem with $47.8M and $36.9M respectively.
* **ROAS Dominance:** Multi-channel strategies incorporating WhatsApp yield the highest financial returns. The combination **WhatsApp + Instagram + YouTube** drastically outpaces single-channel deployments, showcasing an exceptional efficiency multiplier.
* **Operational CTR:** Individual messaging and visual channel syndications consistently sustain a healthy Click-Through Rate above 14%, driving strong digital engagement.

### Page 2: Target Audience & Demographic Segmentation
* **Market Share:** Revenue is evenly balanced across segments, with **Premium Shoppers** representing the largest market slice at **20.75%** ($148M total revenue).
* **High-Engagement Micro-Segment:** **Working Women** lead operational engagement with the highest demographic CTR (**8.58%**), closely followed by *Premium Shoppers* (8.57%), making them prime targets for high-intent conversion messaging.

---

## Dashboard Previews

### Page 1: Marketing Channels & Financial ROAS
`![Channel Dashboard](dashboard_pagina1.png)`

### Page 2: Audience & Demographic Share
`![Audience Dashboard](dashboard_pagina2.png)`

---

## Repository Structure
* `/data`: Contains the cleaned CSV data sheets (`high_revenue_channels_omnichannel.csv`, `audience_performance.csv`).
* `/powerbi`: Contains the source Power BI Desktop binary workbook (`.pbix`).
* `README.md`: Project executive summary and technical write-up.
