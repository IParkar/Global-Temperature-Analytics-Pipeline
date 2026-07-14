# Global-Temperature-Analytics-Pipeline
An end-to-end modern data stack project utilizing Google Cloud BigQuery for heavy-lifting data warehouse analytics and Looker Studio for enterprise-grade visualization.

---

# Tools Used

- Google BigQuery
- Google Looker Studio
- SQL
- Public Climate Dataset

---

## Project Objectives

- Query and analyze climate data in BigQuery
- Use aggregate functions to identify temperature trends
- Apply string functions for data cleaning and transformation
- Create interactive visualizations in Looker Studio
- Build geographic visualizations to compare temperatures across countries

---

## Part 1: Average Temperature Trend by Year

### Query: `Avg_temp_by_year`

This analysis used SQL aggregate functions to calculate the average temperature for each year.

### Concepts Used

- `AVG()`
- `GROUP BY`
- `ORDER BY`

### Purpose

To identify long-term temperature trends and observe changes in average temperatures over time.

### Visualization

A **Line Chart** was created in Looker Studio to display:

- Year on the X-axis
- Average Temperature on the Y-axis

### Key Outcome

The visualization effectively highlights temperature variations and historical climate patterns across multiple years.

---

## Part 2: Average Temperature by Country

### Query: `Avg_temp_by_country`

This analysis focused on calculating average temperatures at the country level.

### Purpose

To standardize country names and improve data quality before aggregation.

### Visualization

The resulting dataset was used to compare average temperatures among countries.

### Key Outcome

Data cleaning through string functions improved consistency and accuracy in country-level analysis.

---

## Part 3: Geographic Temperature Analysis

### Query: `Baseline_temp`

This query prepared climate data for geographic visualization.

### Concepts Used

- Geographic dimensions
- Aggregated temperature metrics
- Data preparation for mapping

### Visualization

A **Geo Chart** was created in Looker Studio to display:

- Countries represented geographically
- Temperature values shown using color intensity
- Interactive filtering and exploration

### Key Outcome

The geo chart provided a clear visual representation of temperature distribution across different regions of the world.

---

## Skills Demonstrated

### BigQuery
- SQL Query Development
- Aggregate Functions
- String Functions
- Data Transformation
- Data Analysis

### Looker Studio
- Data Source Integration
- Line Chart Creation
- Geo Chart Creation
- Dashboard Design
- Data Visualization

### Analytics
- Trend Analysis
- Geographic Analysis
- Data Cleaning
- Data Storytelling

---

## Project Deliverables

- Average Temperature by Year Analysis
- Average Temperature by Country Analysis
- Geographic Temperature Visualization
- Interactive Looker Studio Dashboard

---

## Learning Outcomes

Through this project, I gained hands-on experience with:

- Querying large datasets in BigQuery
- Using aggregate and string functions to prepare data
- Creating meaningful visualizations in Looker Studio
- Transforming raw data into actionable insights
- Building dashboards for business and analytical reporting

---

