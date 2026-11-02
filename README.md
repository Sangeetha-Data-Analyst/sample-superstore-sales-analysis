# Sample Superstore Sales & Profitability Analysis (Excel)

## Project Overview

This project analyses the Sample Superstore retail dataset in Microsoft
Excel to understand sales performance, profitability, regional and
product trends, and potential sources of profit loss. The aim is to turn
raw transactional data into an interactive dashboard and practical,
data-driven business recommendations.

The analysis looks beyond revenue alone: strong sales do not necessarily
mean strong profitability. By examining profit margins, discounts,
products, regions, customer segments, and time trends, the project helps
identify where performance is strong and where further investigation may
be needed.

## Business Objectives

-   Track sales, profit, profit margin, order volume, and quantity sold.
-   Compare performance across regions, categories, subcategories, and
    customer segments.
-   Analyse monthly sales and profit trends to identify changes over
    time.
-   Identify loss-making products and subcategories, including areas
    with high sales but weak or negative profit.
-   Investigate how discount levels relate to profitability and
    potential losses.
-   Compare sales growth with profit growth to assess whether growth is
    financially healthy.
-   Build an interactive Excel dashboard to support filtering and
    exploration.
-   Translate analytical findings into clear recommendations for
    business stakeholders.

## Tools and Excel Techniques

-   **Microsoft Excel**
-   Data inspection and cleaning
-   Excel Tables and structured references
-   Formulas and calculated metrics
-   PivotTables and PivotCharts
-   Interactive slicers and date filters/timelines, where implemented
-   Conditional formatting
-   KPI cards and dashboard layout
-   Business interpretation and recommendations

## Dataset

The Sample Superstore dataset contains transactional retail records with
fields commonly used to analyse orders, dates, shipping, customer
segments, geographic regions, product categories, sales, discounts,
quantities, and profit.

The initial workbook audit identified **9,994 records and 19 columns**.
No missing values or exact duplicate rows were identified in that
initial check. The `Order Date` and `Ship Date` fields included mixed
date representations (text and date values), so date consistency needed
to be checked and standardised before time-based analysis.

> **Data note:** The figures above describe the initial data audit.
> Update this README if your final cleaned workbook or validation
> results differ. If redistributing the dataset, check the source's
> licence and attribution requirements.

## Key Metrics

  -----------------------------------------------------------------------
  Metric                              Definition
  ----------------------------------- -----------------------------------
  Total Sales                         Sum of sales value

  Total Profit                        Sum of profit

  Profit Margin                       Total profit divided by total sales

  Total Orders                        Distinct count of order IDs

  Quantity Sold                       Sum of quantity

  Average Order Value                 Total sales divided by distinct
                                      orders

  Average Discount                    Average of the recorded discount
                                      values

  Sales Growth                        Change in sales against a
                                      comparable prior period

  Profit Growth                       Change in profit against a
                                      comparable prior period

  Loss-Making Products                Products with negative aggregated
                                      profit over the selected period
  -----------------------------------------------------------------------

**Calculation note:** Profit margin should be calculated as total profit
divided by total sales, rather than averaging row-level margins. Order
counts should use distinct order IDs rather than counting transaction
rows. Loss-making status should be based on aggregated profit for the
selected analysis period.

## Analysis Areas

### 1. Data Understanding and Preparation

-   Review the dataset structure, columns, and data types.
-   Check missing values, duplicate records, inconsistent formats, and
    unusual values.
-   Standardise date fields before building monthly or year-based
    analysis.
-   Preserve valid negative-profit records because they are important
    business signals, not data errors.

### 2. Sales Performance

-   Compare sales across regions and product categories.
-   Examine subcategory and customer-segment performance.
-   Track changes in sales over time.
-   Identify high-revenue areas and weaker performers.

### 3. Profitability Analysis

-   Compare total profit and profit margin across regions and
    categories.
-   Look for high-sales areas that produce relatively little profit.
-   Identify products or subcategories with negative aggregated profit.
-   Compare revenue growth with profit growth.

### 4. Discount Analysis

-   Examine the relationship between discount levels and profit.
-   Investigate whether heavily discounted products or segments are
    associated with lower margins or losses.
-   Treat relationships as associations unless further analysis
    establishes a causal explanation.

### 5. Time-Based Analysis

-   Analyse monthly sales and profit trends.
-   Compare periods where possible, ensuring like-for-like date ranges.
-   Investigate periods where sales rise but profit falls.

### 6. Business Recommendations

Use the results to recommend where management could investigate pricing
and discount policies, product performance, regional strategy, or
product-range decisions. Recommendations should be tied to observed
results and their potential business impact.

## Dashboard

The intended dashboard brings together headline KPIs and interactive
views of sales and profitability. Depending on the final workbook
implementation, these may include:

-   KPI cards for sales, profit, profit margin, and orders
-   Sales by region
-   Sales and profit by category or subcategory
-   Monthly sales and profit trends
-   Discount and profitability comparisons
-   Loss-making product or subcategory analysis
-   Slicers for exploring relevant regions, categories, segments, and
    dates

If you add a dashboard screenshot to the repository, save it as
`images/dashboard.png` and insert:

``` markdown
![Excel Sample Superstore dashboard](images/dashboard.png)
```

## Repository Structure

A simple repository structure could be:

``` text
sample-superstore-excel-analysis/
├── README.md
├── Sample_Superstore_Analysis.xlsx
└── images/
    └── dashboard.png
```

Rename the workbook in this example to match the actual filename you
upload. Include the screenshot only if you have exported one. Avoid
uploading confidential or restricted data.

## Key Questions This Project Explores

-   Which regions and categories generate the most sales?
-   Do the highest-sales regions and categories also generate the most
    profit?
-   Which subcategories or products generate negative profit?
-   Are discounts associated with lower profit margins or losses?
-   Which months show sales and profit moving in different directions?
-   Which customer segments perform best in terms of sales and
    profitability?
-   What areas should management investigate to improve profitable
    growth?

## Findings and Recommendations

Add your **verified results from the completed workbook** here. Useful
findings include:

1.  **Sales performance:** strongest and weakest regions or categories,
    supported by figures.
2.  **Profitability:** categories or products with low margins or
    negative total profit.
3.  **Discounts:** evidence of discount levels associated with weaker
    profitability.
4.  **Time trends:** meaningful monthly or yearly changes in sales and
    profit.
5.  **Recommended actions:** practical next steps linked directly to the
    findings.

Avoid adding generic conclusions or estimated financial impacts that
have not been calculated from the data.

## How to Use

1.  Download or open the Excel workbook.
2.  Navigate to the dashboard worksheet.
3.  Use the available slicers, filters, or timeline to explore different
    periods, regions, categories, and segments.
4.  Review the KPI values and charts together rather than interpreting
    sales in isolation.
5.  Use the supporting analysis worksheets to validate dashboard
    findings and investigate products or subcategories with weak
    profitability.

The exact worksheet names and interactive controls may vary depending on
the final workbook.

## Limitations

-   The analysis is descriptive and depends on the quality and scope of
    the supplied dataset.
-   An association between discounts and losses does not, by itself,
    prove that discounts caused the losses.
-   Findings from the dataset should not automatically be generalised to
    other retailers or periods.
-   Recommendations should be validated against operational context and
    any additional business information available.

## Project Outcome

This project demonstrates an end-to-end Excel analytics workflow:
understanding and preparing transactional data, defining meaningful
business metrics, analysing sales and profitability, presenting results
in a dashboard, and framing evidence-based business recommendations.

------------------------------------------------------------------------

**Author:** Sangeetha\
**Tools:** Microsoft Excel\
**Project type:** Sales analytics, profitability analysis, and
interactive dashboard
