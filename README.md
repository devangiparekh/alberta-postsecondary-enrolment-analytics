# Alberta Postsecondary Enrolment Analytics
#Developed by Devangi Parekh | 2026 | Portfolio Project
## Project Overview

This Power BI project explores Alberta's postsecondary enrolment landscape and the factors that may influence future enrolment demand.

The analysis combines historical enrolment trends, international student participation, institution-level enrolment, and demographic indicators to examine how Alberta's postsecondary sector has evolved and what may shape its future.

The report was designed as a two-page analytical dashboard:

1. **Alberta Enrolment Overview** – examines historical enrolment, international student growth, enrolment composition, institution-level enrolment, and demographic trends.

2. **Drivers & Future Outlook** – explores Alberta's prospective age-18 population pipeline, Canadian birth-cohort trends, international student enrolment context, and the factors that may influence future enrolment growth.

## Key Questions

The analysis was designed to answer several questions:

- How has Alberta postsecondary enrolment changed over time?
- How much of recent enrolment growth has come from international students?
- Which Alberta institutions have the largest enrolment?
- How does enrolment growth compare with Alberta's demographic pipeline?
- What do Canadian birth trends suggest about longer-term postsecondary demand?
- What factors could influence Alberta's postsecondary enrolment over the next decade?

## Tools & Skills

- Power BI
- Power Query
- DAX
- Data modelling
- Data cleaning and transformation
- KPI development
- Data visualization
- Trend analysis
- Demographic analysis
- Data storytelling

## Dashboard Pages

### 1. Alberta Enrolment Overview

Provides an interactive overview of Alberta's postsecondary sector, including:

- Total enrolment
- Year-over-year enrolment growth
- International student enrolment
- International share of total enrolment
- Historical Canadian and international enrolment trends
- Top Alberta institutions by enrolment
- Enrolment growth compared with the age-18 demographic pipeline

### Dashboard Preview

![Alberta Postsecondary Enrolment Overview](alberta-enrolment-overview.png)

### 2. Drivers & Future Outlook

Examines potential drivers of future postsecondary demand through:

- Alberta's prospective age-18 population pipeline
- Canadian birth-cohort trends
- National international-student enrolment trends
- Comparison of demographic, Canadian enrolment, and international enrolment growth
- Analytical interpretation of future enrolment conditions

### Dashboard Preview

![Drivers and Future Outlook](drivers-future-outlook.png)

## Key Insights

### 1. International enrolment has been a major driver of recent growth
Alberta's postsecondary enrolment has grown over the analysis period, but international enrolment has increased substantially faster than Canadian enrolment. By 2023/24, international students represented approximately 17.2% of total enrolment, highlighting the increasing importance of international students to overall sector growth.

### 2. Enrolment growth has outpaced the domestic demographic pipeline
When enrolment and Alberta's prospective age-18 population are indexed to a common baseline, international enrolment rises much more rapidly than the demographic indicator. This suggests that recent enrolment growth cannot be explained by Alberta's traditional college-age population alone.

### 3. Alberta's demographic pipeline strengthens before moderating
The prospective age-18 population indicator strengthens into the early 2030s before moderating later in the decade. This could provide some demographic support for domestic postsecondary demand in the medium term, but demographic growth alone may not sustain the recent pace of overall enrolment growth.

### 4. International-student conditions introduce near-term uncertainty
National international postsecondary indicators show strong growth through 2023/24 followed by a pronounced slowdown in the subsequent estimated years. Because Alberta's recent enrolment growth has become increasingly associated with international students, changes in international-student conditions could create greater near-term enrolment uncertainty.

> **Note:** National figures for 2024/25 and 2025/26 are estimates rather than observed values.

## Data Sources

This project combines publicly available postsecondary and demographic data with derived analytical datasets created in Python.

### Alberta Postsecondary Enrolment
Historical Alberta postsecondary enrolment data was used to analyze:
- Total enrolment
- Canadian and international enrolment
- Institution-level enrolment
- International student share
- Year-over-year and long-term enrolment change

**Source:** Government of Alberta / publicly available postsecondary enrolment data.

### Demographic Context
Historical birth data for Alberta and Canada was used to construct a demographic pipeline indicator. Birth cohorts were shifted approximately 18 years forward to provide a simple indicator of the population approaching traditional postsecondary-entry age.

**Source:** Statistics Canada population and birth statistics.

### Canadian International Student Context
National postsecondary international-student information was used to provide broader context for Alberta's international enrolment trends.

Observed historical data and published estimates were separated in the analysis.

- 2019/20–2023/24: Observed
- 2024/25–2025/26: Estimated

**Sources:** Statistics Canada and publicly available postsecondary-sector publications.

## Methodology

### Data Preparation
Python was used to clean, standardize, validate, and combine the source datasets before loading the analytical tables into Power BI.

Key preparation steps included:
- Standardizing academic-year formats
- Separating institution and provincial-level records
- Reconciling Canadian and international enrolment totals
- Checking duplicate and missing records
- Calculating enrolment shares and changes
- Creating institution-level growth measures
- Creating indexed demographic and enrolment measures
- Separating observed values from estimates

### Demographic Pipeline
Historical Alberta birth cohorts were shifted forward approximately 18 years to create an indicator of the population approaching traditional postsecondary-entry age.

The resulting series is used as contextual evidence rather than as a formal enrolment forecast.

### Indexed Comparison
Demographic, Canadian enrolment, and international enrolment series were indexed to a common baseline to compare relative growth despite differences in their absolute values.

### Power BI
Power BI was used for:
- Data modelling and table relationships
- DAX measures and KPI calculations
- Interactive academic-year filtering
- Institution-level ranking
- Trend and composition analysis
- Data storytelling and dashboard design

## Analytical Limitations

This analysis identifies patterns and associations rather than establishing causation.

The demographic pipeline represents an approximate age-18 population indicator and does not account for participation rates, migration, student mobility, economic conditions, institutional capacity, or individual education decisions.

International-student conditions are influenced by policy, visa issuance, institutional behaviour, labour-market conditions, and other factors outside the scope of this dashboard.

Values identified as estimates should not be interpreted as observed enrolment counts.



## Source References

The analysis uses publicly available data and research from official statistical and postsecondary sources.

### Postsecondary Enrolment Data

**Statistics Canada – Postsecondary Student Information System (PSIS)**  
Used for postsecondary enrolment analysis, including institution-level and student-status trends.

Statistics Canada Table 37-10-0277-01:  
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3710027701

### Birth & Demographic Data

**Statistics Canada – Canadian Vital Statistics, Birth Database (CVSB)**  
Historical birth counts for Canada and Alberta were used to construct the approximate age-18 demographic pipeline.

https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getInstanceList&Id=1324420

Birth cohorts were shifted approximately 18 years forward for analytical comparison with postsecondary enrolment. This is a demographic indicator rather than an enrolment forecast.

### International Student Context

**Statistics Canada – Postsecondary Student Information System (PSIS)**  
National international-student data were used to provide context for recent changes in Canadian postsecondary enrolment.

Observed values: 2019/20–2023/24  
Estimated values: 2024/25–2025/26

### Supporting Statistics Canada Research

The following Statistics Canada research publications were reviewed to provide broader context around postsecondary education, labour-market conditions and changing student demand:

https://www150.statcan.gc.ca/n1/pub/36-28-0001/2026001/article/00001-eng.htm

https://www150.statcan.gc.ca/n1/pub/36-28-0001/2025004/article/00002-eng.htm

## Data Interpretation Note

External indicators are used to provide context for Alberta's enrolment trends. Relationships shown in this project should not be interpreted as proof of causation.

Estimated values are explicitly identified, and the demographic pipeline is intended as a contextual indicator rather than a formal forecast.
