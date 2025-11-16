##  About the project

**Goal:**  
Explore drivers of happiness (GDP per capita, life expectancy, freedom, social support, generosity) across countries and years (2015–2019) and present interactive, actionable visualizations for non-technical stakeholders.

**Tools used:**  
- Python (pandas, numpy) for data cleaning & EDA  
- Tableau Public for interactive dashboards  
- Git & GitHub for version control

---

##  Data sources

- World Bank GDP data: https://data.worldbank.org/indicator/NY.GDP.MKTP.CD

---

##  Data cleaning (summary)
- Combined yearly CSVs into a single dataset
- Standardized column names and added `Year`
- Handled missing values (left as NaN or interpolated where noted)
- Exported final `clean_world_happiness.csv`


---

##  Visualizations & Dashboards
Key views included in Tableau:
- Global happiness choropleth map (filter by year)  
- GDP vs Happiness scatter with trendline  
- Top 10 countries (by selected year) bar chart  
- Time-series of happiness for selected countries  
- KPI cards (Avg Happiness, Avg GDP, etc.)


