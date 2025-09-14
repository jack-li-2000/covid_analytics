🦠 COVID‑19 Data Analytics (SQL Project)

Summary

This project uses SQL to analyze global COVID‑19 data, focusing on trends in confirmed cases, deaths, and vaccination rates. The goal is to uncover patterns over time, compare regions, and identify factors that may influence the spread and impact of the virus. The analysis is performed entirely in SQL, making it portable and easy to adapt to different relational database systems.

Hypothesis

* Countries with higher vaccination rates will show a slower growth rate in new cases and deaths over time.
* Population density and GDP per capita may correlate with infection and mortality rates.
* The timing of vaccination rollouts significantly impacts peak case counts.

Methods

Data Source: Public COVID‑19 datasets (e.g., Our World in Data, WHO, or Johns Hopkins University).

Tools Used:

  SQL (tested on MySQL/PostgreSQL/SQL Server)

Process:

* Data Import – Loaded CSV datasets into relational database tables.
* Data Cleaning – Removed duplicates, standardized date formats, handled missing values.
* Exploratory Queries – Aggregated daily case and death counts by country and continent.
* Trend Analysis – Used window functions to calculate rolling averages and growth rates.
* Correlation Checks – Joined COVID data with vaccination and demographic datasets to explore relationships.
* Visualization Prep – Created summary tables for export to BI tools (e.g., Tableau, Power BI).

Conclusion

* Vaccination Impact – Countries with early and high vaccination coverage generally experienced lower mortality rates in later waves.
* Regional Differences – Infection and death trends varied significantly by continent, often influenced by public health measures and healthcare capacity.
* Data Gaps – Some countries had incomplete or inconsistent reporting, which may affect the accuracy of comparisons.

Also, check out the dashboard made using some of this data! 
https://public.tableau.com/app/profile/jack.li2849/viz/CovidGlobalInfectionAnalysis/Dashboard1?publish=yes
