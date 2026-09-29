# Projects Catalogue

Complete list of my data analysis projects with tech stack, domain and short description.  
For a personal overview and featured work see [my GitHub profile](https://github.com/shpak-yana).

---

## Projects

| Project | Domain | Tools | Description |
|---------|--------|-------|-------------|
| [**Discount Strategy A/B Test**](https://github.com/shpak-yana/Discount-Strategy-A-B-Test) | E-commerce · Experimentation | Python, pandas, scipy, statsmodels, seaborn, parquet, Jupyter | End-to-end evaluation of a simulated discount strategy. Customer-level randomization on Online Retail II (~785k cleaned transactions). Measured uplift in revenue per customer, conversion and AOV with Welch’s t-test, z-test, bootstrap CIs and power analysis. Segmented by UK/non-UK, new/returning and value tier with Holm-Bonferroni correction. Key result: moderate discount lifts conversion but does not significantly increase revenue; return rate rises (guardrail risk). |
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
