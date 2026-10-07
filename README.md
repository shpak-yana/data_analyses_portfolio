# Projects Catalogue

Complete list of my data analysis projects with tech stack, domain and short description.  
For a personal overview and featured work see [my GitHub profile](https://github.com/shpak-yana).

---

## Projects

| Project | Domain | Tools | Description |
|---------|--------|-------|-------------|
| [**Discount Strategy A/B Test**](https://github.com/shpak-yana/Discount-Strategy-A-B-Test) | E-commerce · Experimentation | Python, pandas, scipy, statsmodels, seaborn, parquet, Jupyter | This project evaluates discount strategies for an e-commerce retailer using two complementary experiments on the Online Retail II dataset: A/B test (2 groups) — does a 5% discount increase revenue per customer, and is the effect statistically detectable? A/B/C/D test (4 groups) — which discount level (5%, 10%, 15%) maximizes net revenue without deteriorating the guardrail metric (return rate)? The project demonstrates a full production-grade A/B testing pipeline: data cleaning, heavy-tail diagnostics, stratified randomization, A/A validation, winsorization, hypothesis testing, bootstrap confidence intervals, power analysis, and multi-comparison correction. |
| [**UK Road Safety — Local Authority Performance Analytics**](https://github.com/shpak-yana/UK-Road-Safety-Local-Authority-Performance-Analytics) | Public Sector · Transport Safety | Python, pandas, DuckDB, Power BI, parquet, Jupyter | Analysis of 493k+ collisions and 544k casualties (STATS19 2021–2025) enriched with English Indices of Deprivation 2025. Built dimensional model, benchmarked Local Authorities, profiled vulnerable road users and examined the link between deprivation and casualty severity. |
| [**Hotel Booking Demand Analysis**](https://github.com/shpak-yana/Hotel-Booking-Demand-Analysis) | Hospitality · Revenue Management | Python, pandas, matplotlib, seaborn, Tableau, Jupyter | EDA of ~120k hotel bookings (City & Resort). Investigated cancellation drivers, seasonality, source markets, family bookings and room-type mismatches (overbooking proxy). Delivered recommendations and interactive Tableau dashboards. |

---

## Quick filter by skill

| Skill / Topic              | Projects |
|----------------------------|----------|
| A/B testing & statistics   | Discount Strategy A/B Test |
| Experiment design & power  | Discount Strategy A/B Test |
| Segmentation & multiple testing | Discount Strategy A/B Test |
| Public data (UK)           | UK Road Safety |
| Dimensional modelling / DuckDB | UK Road Safety |
| Power BI                   | UK Road Safety |
| Tableau                    | Hotel Booking Demand |
| Customer / revenue analytics | Hotel Booking Demand, Discount Strategy A/B Test |
| EDA & data cleaning        | All projects |

---

## How to use this page

- Click any project name to open the full repository (README + notebooks + data/reports).
- All projects include clear methodology, key findings and reproducible code.
- Treatment effects in the A/B test project are **simulated** for demonstration purposes.
