# 📊 Black Friday Sales Analysis with SQL

## 📌 About the Project

This project analyzes historical sales data from previous Black Friday events to identify sales trends, evaluate supplier performance, and generate insights to support business decision-making.

The analysis focuses on sales behavior over the last four years, investigating supplier performance, overall sales trends, and monthly sales patterns.

## 🎯 Objectives

- Analyze supplier performance during previous Black Friday events.
- Compare sales performance among major suppliers.
- Identify historical sales trends over the last four years.
- Investigate monthly sales patterns and seasonality.
- Develop an SQL metric to compare current Black Friday sales against the historical average.

## 🛠️ Tools & Technologies

- **SQL** — Data querying and analysis.
- **SQLite** — Database engine used for querying sales data.
- **Google Sheets** — Data visualization and chart creation.

## 🔎 Analysis & Key Findings

### 1. NebulaNetworks Supplier Performance

The analysis identified NebulaNetworks as the lowest-performing supplier in the previous year's Black Friday, with 529 sales.

Historical data also showed a declining sales trend for this supplier over the four-year period analyzed.

### 2. Comparison Between Major Suppliers

The main suppliers showed similar sales patterns over time.

The analysis did not identify clear evidence that a specific supplier was responsible for the overall decline in sales.

### 3. Overall Sales Trends

Total sales showed a declining trend over the four years analyzed.

This historical context is important when evaluating current Black Friday results and considering potential external factors.

### 4. Monthly Sales Patterns

The monthly analysis identified higher sales volumes in January, November, and December.

May also showed a recurring increase in sales across the years analyzed, suggesting a pattern worth investigating further.

## 📈 SQL Business Metric

A SQL query was developed to compare November sales in a selected year against the average November sales of previous years.

The metric calculates the percentage difference between current sales and the historical average.

**Example:**

| Metric | Value |
|---|---:|
| Historical Average Sales | 2,049.5 |
| Current November Sales | 3,200 |
| Percentage Change | +56.14% |

This metric can help the business team quickly evaluate Black Friday performance against historical results.

*Note: The values above illustrate the metric's output and should be interpreted according to the dataset and comparison period used.*

## 💡 Business Recommendations

Based on the analysis, the following next steps are recommended:

- Investigate product categories and brands to identify additional sales patterns.
- Expand the set of performance indicators used to monitor Black Friday results.
- Continue tracking sales trends across different periods.
- Investigate potential factors associated with the historical decline in sales.

## 📂 Project Files

- `relatorio_black_friday.pdf` — Complete business analysis report, including charts and findings.
- `metricas_black_friday.sql` — SQL queries used to calculate the business metric.

## 👨‍💻 Author

**Tiago Simao**

Data Analytics | SQL | Python | Power BI

GitHub: [TiagoSimaodev](https://github.com/TiagoSimaodev)
