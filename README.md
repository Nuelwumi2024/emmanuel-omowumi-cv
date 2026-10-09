# Emmanuel Omowumi

### Data Analyst → Data Engineering | Fintech analytics, pipelines & data storytelling

📍 Lagos, Nigeria · Open to Data Analyst & Data Engineering roles (on-site, hybrid or remote)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-omowumi-98bb03139/)
[![GitHub](https://img.shields.io/badge/GitHub-Nuelwumi2024-181717?logo=github)](https://github.com/Nuelwumi2024)
[![Portfolio](https://img.shields.io/badge/Portfolio-View-1f5fbf)](https://www.datascienceportfol.io/emmanueloluwatobi201)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?logo=gmail&logoColor=white)](mailto:emmanueloluwatobi2015@gmail.com)

---

## Summary

Data analyst who turns complex, messy data into decisions. I work in **SQL, Python, Power BI and Tableau**, and I am deliberately growing into **data engineering**: pipelines that reconcile, models that are tested, and metrics that have one definition.

My path is unusual and it is an advantage. Several years in **laboratory science, food quality assurance and agricultural operations** taught me to treat data as evidence: validate it, document it, trace deviations to root cause and report findings to management. I now apply that discipline to business and fintech data.

## Key achievements

| Area | Achievement |
| --- | --- |
| **Data engineering** | Built a payments ETL that processed **117,891** raw records, loaded **116,137**, quarantined **1,051** bad rows with reasons and removed **703** duplicates. The run fails unless `rows_in = loaded + rejected + duplicates`. |
| **Analytics engineering** | Built a dbt warehouse of **8 models and 12 data tests, all passing (20/20)**, with CI running `dbt build` on every push. |
| **Fraud analytics** | Showed fraud is **~2.9x** likelier at night and **~2.8x** likelier on accounts under 14 days old. Four simple rules catch **29%** of fraud while reviewing only **7.7%** of traffic. |
| **Growth analytics** | Found that customers with 6+ transactions in their first 14 days are **1.9x** more likely to still be active at month 4, and that the top 10% of customers drive **42%** of volume. |
| **Credit risk** | Implemented PAR 30/60/90, NPL proxy and vintage analysis as unit-tested code on a NGN 46.1m book (PAR 30 = 17.1%, PAR 90 = 11.7%). |
| **Career** | Moved from microbiology and quality assurance into analytics, with a Master's degree and a growing record of hands-on analytics work. |

> All portfolio projects use **synthetic, seeded data** that mimics a Nigerian payments and lending business. This is stated in each repo. The point is method and engineering judgement.

## Experience

### Data Analyst · Softrays Information Technology
*January 2024 – Present · Ilorin, Kwara State, Nigeria*

- Build and maintain **Tableau and Power BI dashboards** that track KPIs for projects and teams.
- Analyse customer survey data in Excel, R and Python to find trends that shape marketing strategy.
- Clean and prepare data for data science work, improving data accuracy and model performance.
- Work with cross-functional teams to turn findings into reports, presentations and clear recommendations.
- Query relational databases with SQL for filtering and aggregation, and apply statistical methods (hypothesis testing, correlation, regression).

### Quality In-Process Analyst · Olam
*February 2021 – December 2023 · Ilorin, Kwara State, Nigeria*

- Ran quality checks and **microbiological analysis** on raw materials, in-process samples and finished livestock-feed products to prevent contamination.
- Wrote and rolled out **SOPs** and quality control procedures that kept product quality consistent.
- Led **risk assessments and root cause analysis** on quality deviations.
- Produced QA reports with **trend analysis and non-conformance reports** for management.
- Kept production compliant with **GMP, GHP and HACCP**, and trained production staff in food safety.

### Green House Manager · Vine Dresser Farm, Food & Processing Ltd
*November 2017 – December 2018 · Owode, Ogun State, Nigeria*

- Managed daily greenhouse operations: cultivation, irrigation, pest control and climate control.
- **Analysed sensor and crop-monitoring data** to spot trends, optimise processes and decide on inputs.
- Kept records of yields, production costs and environmental data; supervised and trained staff.

## Featured projects

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| [**Naira Payments ETL Pipeline**](https://github.com/Nuelwumi2024/naira-payments-etl-pipeline) | Batch ETL, star schema, bad-record quarantine, row-count reconciliation, quality gates that fail the run, audit table, Airflow DAG | Python, pandas, DuckDB, SQL, pytest, Airflow, GitHub Actions |
| [**Fintech dbt Analytics Warehouse**](https://github.com/Nuelwumi2024/fintech-dbt-analytics-warehouse) | Layered dbt models (staging → marts), 12 tests incl. FK integrity, custom singular test, Jinja macros, CI | dbt, DuckDB, SQL, Jinja, GitHub Actions |
| [**Transaction Fraud Analysis**](https://github.com/Nuelwumi2024/transaction-fraud-analysis) | Fraud lift by segment, rule precision/recall trade-offs, review-queue sizing, ranked recommendation | SQL, Python, DuckDB, Matplotlib |
| [**Wallet Churn & Retention Story**](https://github.com/Nuelwumi2024/wallet-churn-retention-story) | Cohort retention heatmap, channel quality, activation analysis with a correlation-vs-causation caveat | SQL, Python, DuckDB, Matplotlib |
| [**Loan Portfolio Risk Dashboard**](https://github.com/Nuelwumi2024/loan-portfolio-risk-dashboard) | PAR 30/60/90, NPL proxy, vintage curves, segment delinquency, unit-tested metric definitions | Python, pandas, Matplotlib, pytest |
| [**Data Portfolio Interview Guide**](https://github.com/Nuelwumi2024/data-portfolio-interview-guide) | Documentation of the five projects above: trade-offs, results and honest limitations | Markdown |

### Earlier analytics work
- **Financial Sales Data Analytics** (*Excel, MySQL*): analysed a global sales company's 2013–2014 performance; built relational tables and visualised manufacturing cost, profit margin and customer reviews.
- **Sales Analytics & Operations Dashboard** (*Excel, Power BI*): turned fragmented sales records into an interactive dashboard by region, product and customer segment.
- **Global Store Finance Records** (*Excel, MySQL*): consolidated high-volume transactions to assess efficiency, supply constraints and margins.
- **Chocolate Revenue Pipeline & Dashboard** (*Power Query, Power BI, Excel*): cleaned data with missing values, built an ETL process and identified seasonal demand and top products.

## Technical skills

| Area | Tools & concepts |
| --- | --- |
| Languages | Python, SQL, R |
| Data engineering | ETL/ELT design, star-schema modelling, dbt, DuckDB, data-quality testing, Airflow (DAG authoring), GitHub Actions CI |
| Databases | MySQL, SQL Server, DuckDB |
| BI & visualisation | Power BI, Tableau, Excel, DAX |
| Data processing | pandas, NumPy, Power Query, data wrangling |
| Analytics | Cohort and retention analysis, statistical analysis, regression, risk and KPI reporting |
| Domain | Fintech (payments, wallets, digital lending), fraud, credit risk, food quality & lab operations |
| Lab & quality | LIMS, Good Laboratory Practice (GLP), GMP, HACCP, food microbiology |

## Training & certifications

- **Microsoft PL-300: Power BI Data Analyst Associate**: exam preparation in progress
- **Advanced Data Analytics 2025**: Excel, SQL, Power BI, Python
- **Advanced BI & DAX Modelling**: Excel / Power Query

## Education

| Qualification | Institution | Period |
| --- | --- | --- |
| M.Sc. Microbiology | Kwara State University, Malete | Mar 2021 – May 2023 |
| B.Sc. Microbiology | Kwara State University, Malete | Jan 2018 – Dec 2020 |
| B.Sc. Botany / Plant Biology | University of Ilorin | Sep 2013 – Aug 2017 |

## What I bring

- **Pipeline thinking:** extract, validate, model, load, test, monitor, with reconciliation built in.
- **Data quality as a feature:** tests and failing builds instead of silent bad data.
- **Scientific rigour:** hypothesis-driven analysis, SOPs, root cause analysis and honest caveats.
- **Communication:** findings written for decision-makers, ending in ranked recommendations.
- **Engineering habits:** version control, unit tests, CI and reproducible runs.

## Contact

- LinkedIn: [emmanuel-omowumi-98bb03139](https://www.linkedin.com/in/emmanuel-omowumi-98bb03139/)
- Email: [emmanueloluwatobi2015@gmail.com](mailto:emmanueloluwatobi2015@gmail.com)
- GitHub: [Nuelwumi2024](https://github.com/Nuelwumi2024)
