# Zubair Hashmat - Data Analyst Portfolio

## About

Hi, I'm Zubair Hashmat! I'm a junior data analyst who enjoys turning messy data into clear answers.

My projects start with a business question, move through careful cleaning and analysis, and end with findings that a non-technical reader can act on. I check my numbers (row counts, reconciliations) before reporting them, and I write down the limitations of every analysis. I work with Python, SQL (PostgreSQL), Excel and Power BI, and I hold the Google Data Analytics Professional Certificate.

## Table of Contents

- [About](#about)
- [Portfolio Projects](#portfolio-projects)
  * SQL, Excel and Power BI
    + [Customer Churn Analysis](#customer-churn-analysis)
  * Python
    + [World Economic Indicators Analysis](#world-economic-indicators-analysis)
- [Education](#education)
- [Certificates](#certificates)
- [Contact](#contact)

## Portfolio Projects

### Customer Churn Analysis

**Code:** [Repository](https://github.com/Zubair61-ui/customer-churn-analysis-sql-powerbi) | [`telco_churn_clean.sql`](https://github.com/Zubair61-ui/customer-churn-analysis-sql-powerbi/blob/main/telco_churn_clean.sql) | [`telco_churn_analysis.sql`](https://github.com/Zubair61-ui/customer-churn-analysis-sql-powerbi/blob/main/telco_churn_analysis.sql)

**Goal:** To find out which customers of a telecom provider leave, and why, and which segments the retention team should prioritise.

**Description:** The dataset covers 7,043 customers with demographic, service, billing and churn information, including the reason each churned customer gave. The project followed a full workflow: a business requirements document, profiling in Excel, loading and cleaning in PostgreSQL (staging table, typed clean table, validation checks, analysis views), and a five-page Power BI dashboard (Overview, Customer profile, Drivers, Reasons, Priority segments).

**Skills:** business requirements writing, data profiling, data cleaning and validation, joins and aggregation, CTEs, window functions, views, DAX measures, dashboard design, distinguishing churn rate from share of churners.

**Technology:** Excel, PostgreSQL, Power BI (DAX).

**Results:** 26.5% of customers churned, taking 30.5% of monthly revenue with them because churners pay more and leave sooner (18.0 vs 37.6 months of tenure). Month-to-month customers are 88.6% of churners. One segment (month-to-month, fiber optic, electronic check) is 19% of customers but 42% of churners and about 49% of lost monthly revenue. A third of churned customers (33.2%) cited a competitor, and the attitude of the support person was the most common single reason (10.3%).

### World Economic Indicators Analysis

**Code:** [Repository](https://github.com/Zubair61-ui/world_economic_indicators) | [`world_economic_indicators_analysis.ipynb`](https://github.com/Zubair61-ui/world_economic_indicators/blob/main/world_economic_indicators_analysis.ipynb)

**Goal:** To understand what World Bank and UN data say about economic growth, human development and life expectancy across about 190 countries.

**Description:** The project combines two sources (World Bank indicators, 1960-2018, and UN Human Development Index data, 1990-2021). It involved reshaping the HDI table from wide to long format, merging the two sources on country codes, deriving population from GDP, and answering four questions: whether population and GDP growth overlap, which regions gained the most HDI since 2000, what correlates with life expectancy, and what separates high from low income countries.

**Skills:** data cleaning, reshaping and merging, growth-rate calculation, correlation analysis, significance testing, robustness checks, data visualisation, documenting limitations.

**Technology:** Python, pandas, NumPy, Matplotlib, SciPy, Google Colab.

**Results:** Fast population growth and fast GDP growth rarely coincide: only Jordan and Lebanon appear in both top-15 lists between 1990 and 2018. South Asia and Sub-Saharan Africa gained the most HDI since 2000, but most of that is catch-up from low starting points. Life expectancy is most strongly correlated with infant mortality, internet use, birth rate, GDP per capita and electricity use, which overlap heavily. The same five indicators almost perfectly separate high from low income countries.

### Olist E-Commerce Analysis

**Code:** [Repository](https://github.com/Zubair61-ui/Olist_E-Commerce_Analysis) | [`Data_cleaning_for_all_tables_separately.sql`](https://github.com/Zubair61-ui/Olist_E-Commerce_Analysis/blob/main/Data_cleaning_for_all_tables_separately.sql)

**Goal:** To understand what drives revenue and customer satisfaction on a Brazilian online marketplace, with delivery performance as the main thread.

**Description:** The dataset covers about 100,000 orders from 2016 to 2018 across nine related tables (orders, items, payments, reviews, customers, products, sellers, categories and geolocation). The project involved loading all tables into PostgreSQL, running the same five cleaning checks on every table (duplicates, missing values, data types, logical errors, inconsistent categories), and building an order-level view so that orders with several items or payments were not counted twice. I then answered five business questions in SQL and built a 3-page Power BI dashboard on top of the SQL views.

**Skills:** Multi-table joins, data cleaning and validation, handling join duplication, CTEs and window functions (LAG, RANK), delivery-time and late-order metrics, review analysis, repeat-customer analysis, dashboard design and writing insights.

**Technology:** PostgreSQL, SQL, Power BI.

**Results:** Revenue grew from about R$137K in January 2017 to a peak of R$1.17M in November 2017, then stayed flat through August 2018. About 8% of orders were delivered late, and those orders averaged a 2.57 review score compared with 4.30 for on-time orders. Scores fell sharply once delivery took 22 days or more (3.00 on average). Only about 3% of customers ordered more than once, and São Paulo sellers brought in about two-thirds of revenue but had one of the lowest review scores.

## Education

University of Agriculture, Faisalabad:
Bachelor of Science (BS), Computer Science, 2021 - 2025
Relevant coursework: Database Systems, Statistics and Probability, Data Structures and Algorithms, Big Data Analytics, Artificial Intelligence

## Certificates

Certificates I have completed:

- [Google Data Analytics Professional Certificate](https://www.credly.com/badges/1eea0b2a-a3d1-422b-a929-483940885aba/public_url)) (December 30, 2025) (Coursera, Google). It covers the full analysis process, from asking questions to sharing results.

## Contact

- LinkedIn: www.linkedin.com/in/zubair-hashmat
- Email: hashmatzubair32@gmail.com
