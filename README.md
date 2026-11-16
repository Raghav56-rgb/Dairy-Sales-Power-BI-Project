# Dairy Goods Sales Analysis

An interactive Power BI dashboard for exploring dairy sales performance, product trends, inventory health, and farm and customer metrics. The report is designed to turn sales and operational data into clear visual insights that can support business monitoring and decision-making.

## Project Overview

The **Dairy Goods Sales Analysis** project uses Microsoft Power BI to present an integrated view of a dairy business. Instead of relying on separate spreadsheets and static reports, the dashboard brings important performance indicators and detailed breakdowns together in one interactive report.

The main focus of the project is its visual analytics experience. Four core dashboard pages provide different perspectives on business performance, while additional Q&A pages offer supplementary ways to explore the data.

## Dashboard Pages

The report contains four primary analytical pages.

### 1. Executive Dashboard

The Executive Dashboard provides a high-level summary of the business through KPI cards and overview visuals.

Key elements include:

- **KPI cards** for headline measures such as Total Revenue, Total Quantity Sold, Total Products, Total Brands, Total Stock, Total Farm Locations, and other summary indicators.
- **Donut chart** to show the composition of a selected business measure across categories.
- **Column and bar charts** to compare performance across relevant groups.
- **Line chart** to show changes and patterns over time.
- **Summary table** for a more detailed view of selected figures.
- **Slicers** to filter the dashboard and focus on particular periods or business segments.

This page is intended to help users understand the overall position of the business quickly before exploring individual areas in more detail.

### 2. Sales & Product Analysis

This page focuses on sales performance and product-level comparisons.

Key visualizations include:

- **Bar charts** for comparing sales or other measures across products and brands.
- **Donut chart** for viewing the distribution of a selected measure.
- **Line chart** for identifying sales patterns over time.
- **Table visual** for reviewing product-level details.
- **Slicers** for narrowing the analysis by available dimensions such as date, product, brand, or sales channel.

These visuals make it easier to compare products, identify stronger and weaker performers, and explore how sales are distributed across the available categories.

### 3. Inventory Analysis

The Inventory Analysis page presents the stock position and inventory-related indicators.

Key visualizations include:

- **KPI cards** for important inventory measures, including Total Stock, Total Inventory Value, and stock-status percentages.
- **Clustered column charts** for comparing inventory measures across categories.
- **Treemap** for displaying the relative contribution of different groups to an inventory measure.
- **Bar chart** for ranking or comparing inventory across selected items.
- **Matrix visual** for examining inventory details across multiple dimensions.
- **Slicers** for filtering the inventory view.

Measures such as Critical Stock %, Warning Stock %, Healthy Stock %, Average Shelf Life, and Total Inventory Value help provide a more complete view of inventory conditions.

### 4. Farm & Customer Analysis

This page brings together farm-level and customer-related analysis.

Key visualizations include:

- **KPI cards** for selected farm and customer indicators.
- **Column charts** for comparing measures across locations or other categories.
- **Bar chart** for clear category-to-category comparisons.
- **Treemap** for showing the relative contribution of different groups.
- **Matrix visual** for a more detailed breakdown.
- **Slicers** for focusing on specific locations, customers, or other available dimensions.

This page helps users explore how performance varies across farm locations and customer segments.

## Visualization and Dashboard Design

Visualizations are the central part of this project. Each visual type is used to answer a different kind of analytical question:

| Visualization | Purpose in the dashboard |
| --- | --- |
| KPI cards | Highlight important business metrics in a compact format. |
| Bar charts | Compare values across products, brands, locations, or other categories. |
| Column charts | Compare category-level performance vertically. |
| Line charts | Reveal changes, patterns, and trends over time. |
| Donut charts | Show how a total is distributed among categories. |
| Treemaps | Display hierarchical or category contributions using proportional areas. |
| Tables | Present exact values and supporting details. |
| Matrix visuals | Compare measures across multiple row and column dimensions. |
| Slicers | Let users interactively filter the report. |

The dashboard combines summary visuals with more detailed views. KPI cards provide an at-a-glance overview, comparison charts help reveal differences between categories, and tables or matrices provide supporting detail when users need to inspect specific values.

## Interactivity

The report includes slicers and navigation controls to make analysis more flexible. Users can apply available filters and explore how the displayed visuals respond to their selections.

Depending on the page, filters can be used to investigate dimensions such as:

- Date and time period
- Product and brand
- Sales channel
- Location and customer location
- Other fields available in the report

The interactive design allows users to move from a broad overview to a more focused analysis without needing a separate static report for every business question.

## Additional Q&A Pages

The report also contains 13 supplementary Q&A pages covering topics such as date analysis, products, customers, geography, sales, profitability, discounts, order quantities, category comparisons, trends, relationships, top and bottom performers, and manager-level analysis.

These pages provide additional question-led exploration. They are supporting features of the report; the four main dashboard pages and their visual analytics are the primary focus of the project.

## Key Metrics

The report includes measures such as:

- Total Revenue
- Total Quantity Sold
- Total Products
- Total Brands
- Total Stock
- Total Farm Locations
- Total Inventory Value
- Average Selling Price
- Critical Stock %
- Warning Stock %
- Healthy Stock %
- Average Shelf Life
- Revenue Per Cow
- Revenue Per Acre

The exact values shown in the dashboard depend on the report's data and filter selections.

## Data Model

The Power BI model includes the following main entities identified in the report:

- **Fact_DairySales** – the main sales and business fact table used by the report visuals.
- **Calendar** – the date-related table used for time-based analysis.
- **Measures (2)** – a measures table containing calculated business metrics used in the dashboard.

The report uses fields such as product name, brand, sales channel, location, customer location, year, and year-month in its visual analysis.

## Tools and Technologies

- **Microsoft Power BI Desktop** – dashboard development and data visualization.
- **Power Query** – data preparation and transformation within Power BI.
- **DAX** – measures and calculations used in report visuals.
- **Data modeling** – organizing the fact and calendar data for analysis.

## Repository Contents

A suggested GitHub repository structure is:

```text
Dairy-Goods-Sales-Analysis/
|
|-- README.md
|-- Dairy_Goods_Sales_Analysis.pbix
|-- Dataset/
|   |-- dairy_sales_data.xlsx
|
|-- Screenshots/
|   |-- executive-dashboard.png
|   |-- sales-product-analysis.png
|   |-- inventory-analysis.png
|   |-- farm-customer-analysis.png
|
|-- Documentation/
    |-- Dairy_Goods_Sales_Analysis_GitHub_Project_Report.pdf
```

Adjust the filenames and folders to match the files you actually upload. Include the dataset only if you have permission to redistribute it.

## How to View the Dashboard

1. Download or clone this repository.
2. Open `Dairy_Goods_Sales_Analysis.pbix` using Microsoft Power BI Desktop.
3. If Power BI requests a data source, connect the report to the corresponding dataset.
4. Refresh the data if required.
5. Navigate through the report pages and use the available slicers and controls to explore the visuals.

## Project Highlights

- Four main dashboard pages focused on executive, sales and product, inventory, and farm and customer analysis.
- A combination of KPI cards, comparison charts, trend charts, treemaps, tables, and matrix visuals.
- Interactive filtering for exploring different business dimensions.
- Business measures covering revenue, quantity, products, stock, inventory health, and farm-related performance.
- Supplementary Q&A pages for additional question-led analysis.

## Possible Future Enhancements

- Add a clearly documented data dictionary and refresh instructions.
- Include more time-intelligence measures for period-over-period comparisons.
- Add drill-through pages for detailed product, location, and customer analysis.
- Improve accessibility with consistent titles, labels, and color contrast.
- Add validated business insights after reviewing the actual dashboard values and source data.

## Notes

- The dashboard's displayed values change according to the selected filters.
- The README describes the report structure and visual types; it does not claim specific sales results or business conclusions.
- Replace the example repository filenames and screenshot paths above with the actual filenames used in your GitHub repository.

---

If you find this project useful, feel free to explore the report and suggest improvements.
