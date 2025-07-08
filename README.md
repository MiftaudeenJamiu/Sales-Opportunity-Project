# Sales-Opportunity-Project

## Table of Contents 
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data analysis](data-analysis)
- [Visualisations and report](Visualisation-and-reports)
- [Results and Findings](#results-and-findings)
- [Conclusions](#conclusions)

  
### Project Overview
---
This Sales Opportunity project showcases how Power BI was used to simulate realistic sales data, perform data cleaning, and conduct in-depth analysis using DAX measures. The report identifies key sales trends, conversion bottlenecks, and potential areas for revenue growth.

## Data Sources
--- 
The dataset was sourced from Kaggle, a public data platform that hosts real-world and synthetic datasets for analysis. It included structured information on sales leads, deal stages, customer details, and opportunity status, making it suitable for simulating a sales funnel and analysing performance across different sales phases.

## Data Cleaning
---
The raw dataset sourced from Kaggle was cleaned using transform options in Power BI before loading it for visualisation. The following steps were taken:
1. Data Loading & Initial Review
   Opened each sheet (Sales Opportunity, Sales Person), changed the data type, scanned for blank fields, unusual values and structural issues.

2. Handling Missing Values
  Filtered and filled rows with missing average values of Opportunity Value.
  Replaced nulls in optional Fields (e.g, Country)

3. Formatting
  Ensured Reporting Date was in the proper date-time format
  Formatted columns (e.g., Country, Sales Stage, Opportunity Value) consistently
  Standardised text case for categorical columns like Sales Stage

4. Data Cleaning
 Removed duplicate entries across all sheets
 Checked for invalid or negative values and corrected them
 Verified IDs were consistent across related tables
 Preparation for Power BI
 Confirmed columns had appropriate headers

### Exploratory Data Analysis
---
EDA phase uncovers patterns in lead conversion, evaluates sales performance, and understands where the sales pipeline gains or loses value and answers key questions such as;

- Which sources, people, or regions generate the most leads? Volume Analysis
- Where do we lose deals and why? Conversion Analysis
- Where is revenue growing or leaking? Value Analysis
- Who is over- or under-performing? Performance Benchmarking

### Data Analysis (Dashboard Development in Power BI)
---
As part of the data analysis process to develop the Power BI dashboard, several key insights and breakdowns were created to visualise and interpret sales opportunity performance, including:
- Sales Channel Breakdown: Analysed the volume of opportunities by channel (e.g., Telesales, F2F, Partners, Website) to identify the most productive lead sources feeding into the pipeline.
- Opportunity Stage Analysis: Assessed the distribution of opportunities across pipeline stages (e.g., Qualification, Proposal, Negotiation, Closed) to detect where leads commonly stall or exit the funnel.
- Top Salesperson Performance: Ranked the top 5 salespeople based on opportunity value and opportunities, helping to recognise high performers and set internal benchmarks.
- Funnel Metrics (Win Rate & Conversion Rate)
- Revenue Analysis (Value Won vs. Lost): Evaluated the total monetary value of won versus lost opportunities to understand the financial impact of sales outcomes.
- Geographic Distribution: Mapped opportunity counts by country to identify performance differences across regional markets.
- Salesperson Deep Dive: Developed a secondary dashboard view focusing on individual sales reps.


### Visualisations and Reports
---
This section showcases the Power BI dashboards built to analyse sales opportunities, track pipeline health, and evaluate sales team performance. Each visual was designed to uncover trends in lead conversion, revenue generation, and sales efficiency, using simulated opportunity data.

- Sales Opportunity Dashboard
1. Opportunities by Sales Channel: Donut chart comparing the volume of opportunities sourced through each channel (e.g., Telesales, F2F, Partners, Websites), helping identify top-performing acquisition sources.
2. Opportunities by Sales Stage: Funnel chart showing how leads are distributed across different sales stages (e.g., Validated, Identified, Qualified, Proposal, Won, Lost), highlighting drop-off points in the pipeline.
3. Top 5 Salespeople: Table chart ranking sales reps based on the number of Opportunities Value, used to benchmark performance.
4. Win Rate & Conversion Rate: KPI cards and funnel visuals showing overall win rate and stage-to-stage conversion rates, allowing evaluation of sales efficiency and effectiveness.
5. Opportunities Won vs. Lost: KPI cards and Line Chart comparing the number of opportunities that were successfully converted versus those lost.
6. Opportunity Value (Won vs. Lost): Gauge comparing Win rate and Conversion rate.
7. Opportunities by Country: Map visual highlighting geographical distribution of opportunities, identifying high-performing and underperforming markets.

 See the shots below for an overview of the fraud detection dashboard
 
![Screenshot 2025-07-08 183732](https://github.com/user-attachments/assets/0bb70c4d-3ace-453e-abeb-0c2e4824c10b)


 
- Sales Person Spec Dashboard
  1. SalesPerson Profile Card: Displays the salesperson’s photo alongside key performance metrics including total number of opportunities handled, total opportunity value and win rate.
  2. Opportunity Table: A detailed table showing all opportunities managed by the selected salesperson, with the following fields: Opportunity ID, Reporting Date, Customer Name, Opportunity Value,Country,
  Sales Channel, Sales Stage, Deal Status (Won/Lost) and Close Date.

 See the shots below for an overview of the fraud detection dashboard
 
![Screenshot 2025-07-08 183850](https://github.com/user-attachments/assets/c43abfeb-5b9b-4c1e-b559-99c491bcb1df)


### Results and Findings
---

Sales Opportunities Overview
- Sales Volume & Performance: A total of 1,819 opportunities were recorded, with 133 deals won and 33 lost, indicating significant activity across the funnel.
- The overall win rate stands at 80.12%, while the conversion rate from one stage to the next is 27.03%, suggesting a need to improve movement across stages.
- Sales Stage Bottlenecks: The funnel chart reveals high drop-offs after the 'Proposal' stage, signalling potential friction in final negotiations or proposal alignment. Most leads sit in earlier stages like 'Validated' (456) and 'Identified' (446), suggesting a large top-of-funnel but challenges in converting to revenue.
- Sales Channel Performance: Telesales drives the highest share of opportunities (36.5%), followed by Website (31.06%), while Partners and F2F (Face-to-Face) underperform in volume.
- Geographic Trends: The global map shows concentration in North America, parts of Asia, and Australia, helping prioritise regions for future campaigns or support.
- Top Salespeople: Sales reps like Angela Chen and Bob Harrison stand out in both opportunity volume and value, indicating consistent performance and deal-closing ability.

Salesperson-Specific Insights
- Individual Snapshot
Selected example: Angela Chen handled 139 opportunities with a total value of $560,060 and a strong win rate of 88.24%, making her a top performer.

Detailed Opportunity Review: A table lists all her handled opportunities with key attributes: customer, value, country, stage, and deal status. Most wins occurred in Australia and China, primarily through F2F and Partners, showing her strength in building relationships in high-value regions. Open deals still sit in mid-stage phases such as 'Qualified' and 'Proposal', presenting clear follow-up priorities.


### Conclusions
---
This project involved cleaning, analysing, and visualising sales opportunity data to track pipeline performance and individual sales activity. The dataset was prepared in Power BI using Power Query, and calculated metrics were created using DAX.

The dashboard showed where deals are concentrated, which channels generate the most leads, and where in the sales process drop-offs occur. It also identified top-performing salespeople and detailed their closed and active opportunities. Visuals on won vs. lost deals helped isolate points of failure in the sales funnel.

The dashboard is designed to support daily decision-making by surfacing trends, performance gaps, and conversion issues across regions, channels, and sales reps.



