# E-Commerce User Funnel Analysis & Dashboard

End-to-end funnel analytics project tracing 10,000 simulated shoppers through **Browse → Add to Cart → Checkout → Purchase**. Built with Python (Pandas, Plotly), analyzed in Jupyter, and visualized in a 3-page interactive Power BI dashboard. Uncovered a **69% checkout-stage drop-off** and delivered data-backed growth recommendations.

---

## 📌 Project Overview

Every online store loses customers somewhere between their first click and checkout — the challenge is knowing exactly where, and why. This project simulates and analyzes a complete e-commerce conversion funnel from the ground up: generating realistic session-level event data, exploring and segmenting it in Python, and packaging the findings into a business-ready Power BI dashboard and Excel report.

**Goal:** Quantify conversion and drop-off across the funnel, and identify the highest-leverage opportunities to improve revenue.

---

## 🧰 Tech Stack

| Tool | Purpose |
|---|---|
| **Python** (Pandas, NumPy) | Data generation, cleaning, feature engineering |
| **Faker** | Synthetic user & session data generation |
| **Jupyter Notebook** | End-to-end exploratory & funnel analysis |
| **Plotly / Matplotlib / Seaborn** | Visualizations |
| **Power BI** | 3-page interactive executive dashboard |
| **Excel** | Structured multi-sheet corporate reporting export |

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `Funnel_data_generator.py` | Generates the synthetic 10,000-user funnel dataset |
| `funnel_analysis_data.csv` | Raw event-level dataset (21,663 events) |
| `Funnel_Analysis.ipynb` | Full analysis notebook — cleaning, funnel metrics, segmentation, insights |
| `funnel_analysis_report.xlsx` | Exported multi-sheet report (funnel, channel, region, device, product, time trends) |
| `Dashboard.pbix` | Power BI dashboard (3 pages) |
| `funnel_conversion_rates.png` | Overall funnel conversion chart |
| `Funnel_Analysis_Case_Study.pptx` / `.pdf` | Project case-study deck summarizing the full analysis |

---

## 🔍 Methodology

1. **Data Generation** — A custom Python generator (Faker) simulates 10,000 users progressing through 4 funnel stages, with realistic stage-drop probabilities, timestamps 2–5 minutes apart, and device/region/channel/category attributes.
2. **Cleaning & Feature Engineering** — Validated nulls/duplicates, parsed timestamps, derived date/hour/weekday features, and aggregated raw events into session-level records.
3. **Funnel Analysis** — Calculated conversion and drop-off rates at each stage, overall and segmented by channel, region, device, and product category.
4. **Dashboard Design** — Wireframed and built a 3-page Power BI dashboard tailored to three audiences: executives, UX/optimization teams, and marketing.
5. **Reporting** — Exported all findings to a structured Excel workbook for stakeholders.

---

## 📊 Key Findings

- **Overall conversion rate:** 10.80% (1,080 purchases from 10,000 sessions)
- **Total revenue:** $1,176,406 | **Average order value:** $1,089
- **Stage-to-stage conversion:**
  - Browse → Add to Cart: **70.59%**
  - Add to Cart → Checkout: **49.92%**
  - Checkout → Purchase: **30.65%** ← biggest single-step drop-off (69.35%)
- **Best channel:** Organic (11.19% conversion, zero media spend)
- **Best region:** South (11.25% conversion)
- **Best product category:** Beauty (11.43% conversion); Electronics lags (10.17%)

---

## 💡 Strategic Recommendations

1. **Fix checkout friction** — Prioritize guest checkout, fewer form fields, visible trust badges, and saved payment options to address the 69% checkout-stage drop-off.
2. **Double down on Organic** — Shift incremental budget from paid channels into SEO/content, given Organic's leading conversion at zero spend.
3. **Replicate South region strategies** — Audit its channel mix, promotions, and pricing to apply learnings elsewhere.
4. **Promote Beauty, investigate Electronics** — Feature top-converting categories more prominently; diagnose friction in underperforming ones.

---

## 📈 Power BI Dashboard

The dashboard has three pages, each designed for a different audience:

1. **Executive Overview** (CEO / Head of Marketing) — KPI cards, funnel chart, revenue by channel/device/region
2. **Funnel Drop-off Diagnostics** (UX / PM / Optimization teams) — drop-off heatmap, device-wise drop-off, channel treemap
3. **Customer & Behavior Insights** (Marketing) — returning users, bounce rate, revenue by category, sessions by time of day

All pages include interactive filters for date range, region, device, and marketing channel.

---

## 🚀 How to Explore This Project

- **Notebook:** Open `Funnel_Analysis.ipynb` in Jupyter to see the full analysis with code and outputs.
- **Dashboard:** Open `Dashboard.pbix` in Power BI Desktop to interact with the live dashboard.
- **Case study:** View `Funnel_Analysis_Case_Study.pdf` for a visual summary of the entire project.
- **Raw data:** `funnel_analysis_data.csv` contains the underlying event-level dataset.

---

## 🎯 Skills Demonstrated

Synthetic data generation · Python data wrangling · Funnel & cohort analysis · Business storytelling · Power BI dashboard design · Cross-segment reporting

---

*This is a portfolio project using fully synthetic, generated data — no real user or company data was used.*
