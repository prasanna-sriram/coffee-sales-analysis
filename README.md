# Coffee Sales Analysis for Retail Performance Optimization

---

### Table of Contents

- [Executive Summary](#executive-summary)
- [Business Problem](#business-problem)
- [Methodology](#methodology)
- [Data](#data)
- [Skills](#skills)
- [Results and Business Recommendation](#results-and-business-recommendation)
- [Project Files](#project-files)
- [How To Run](#how-to-run)
- [Next Steps](#next-steps)
- [License](#license)
- [Author Info](#author-info)

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Executive Summary

This project uses **Power BI** to analyse point-of-sale data from a coffee shop chain. The business challenge was a lack of visibility into product performance, seasonal demand, and customer purchase trends. I built an interactive dashboard that highlights top-selling items, order frequency, and revenue peaks, giving managers actionable insights into inventory, promotions, and staffing. The analysis revealed that just five products drive over 60% of sales and that weekends deliver consistent spikes. With further work, the dashboard could expand to include profitability and customer segmentation, enabling owners to boost margins and loyalty.

![Coffee Sales Dashboard](/images/CoffeeSalesDashboard.png)

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Business Problem

Coffee shop owners often rely on intuition to decide what to stock, when to schedule staff, or how to promote seasonal items. Without clear insight into sales drivers, they risk stockouts, overstaffing, or missed revenue opportunities. 
This project set out to answer: 
   - ***Which products and categories generate the most revenue?***
   - ***When are the busiest times?***
   - ***What is the typical order value?***
By solving these, the business can make more informed operational and marketing decisions.

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Methodology

The workflow began with **data cleaning and profiling** in Power Query to remove duplicates and fix nulls. A **custom Date table** was modelled to support time-based analysis. I created **DAX measures** to calculate key KPIs such as total sales, order count, average sale per order, and quantity sold. The final dashboard included three key views: **Sales Overview**, **Product Breakdown**, and **Time-Based Trends**. Power BI was chosen because of its interactive visuals, ability to handle Excel data directly, and ease of use for non-technical stakeholders.

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Data  

- **Source**: Internal point-of-sale export [data](data/CoffeeShopSales.xlsx)
- **Description**:
  - File: `CoffeeShopSales.xlsx`
  - Key fields: `Product`, `OrderDate`, `Sales`, `Quantity`, `TransactionID`, `Category`
  - Rows: ~1,000 transactions across multiple product categories and time periods

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Skills

- **Power BI:** Interactive dashboards, relationships, visuals (bar, line, card, pie)
- **Power Query:** Data profiling, cleaning, handling nulls/duplicates
- **DAX:** Custom measures (SUM, COUNTROWS, AVERAGEX), KPI creation
- **Data Modelling:** Custom Date table for time intelligence functions

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Results and Business Recommendation

The dashboard uncovered that:
- The top 5 products drive over **60% of revenue**.
- Sales peak on **weekends** and during certain seasonal periods.
- Average order values remain steady but vary slightly by product category.

**Recommendation:** Focus inventory and promotions on the top-selling products, align staffing with weekend and seasonal spikes, and experiment with cross-selling strategies to lift average order values.

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Project Files

The following are the files in this project.

- [Coffee Sales Export Data](data/CoffeeShopSales.xlsx)
- [Microsoft Power BI Report](CoffeeSalesReport.pbix)

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## How to Run

1. Clone or download the repo  
2. Open `CoffeeSalesReport.pbix` in Power BI Desktop  
3. Load the Excel file: `data/CoffeeShopSales.xlsx`  
4. Refresh the visuals and interact with filters  
5. Optional: View the published version [here](https://app.powerbi.com/view?r=eyJrIjoiN2QzNTc4ZmYtZTdlYy00NTcyLWJhYzUtNTRkNTg0OGJiYmMwIiwidCI6Ijk3ODIwYmJjLTE3ZjUtNGRmYy1iNjlkLTY5ZWJjOTRhYzZiZiJ9)

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---
## Next Steps  

With more time, I would:
- Incorporate **profit margin and cost data** to optimise for profitability, not just revenue.
- Add **customer segmentation** to understand repeat vs. new buyers.
- Expand to **multi-store analysis** for benchmarking across locations.
- Address data limitations (only ~1,000 transactions, no customer IDs) by collecting more granular data over a longer period.

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## License

MIT License

Copyright (c) [2025] [Prasanna Sriram]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)

---

## Author Info

- Github - [Github Profile](https://github.com/prasanna-sriram)
- LinkedIn - [Prasanna Sriram](https://www.linkedin.com/in/prasanna-sriram/)
- Tableau - [Tableau Public Profile](https://public.tableau.com/app/profile/prasanna.sriram.ps)

[Back to the Top](#coffee-sales-analysis-for-retail-performance-optimization)