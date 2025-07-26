# Coffee Sales Analysis

---

### Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Data](#data)
- [Approach](#approach)
- [Tools And Technologies](#tools-and-technologies)
- [Project Files](#project-files)
- [Project Outcome](#project-outcome)
- [How To Run](#how-to-run)
- [Conclusion](#conclusion)
- [License](#license)
- [Author Info](#author-info)

[Back to the Top](#coffee-sales-analysis)

---

## Overview

This project analyzes point-of-sale data from a coffee shop chain using Power BI. The dashboard tracks sales performance across products, dates, and order types, helping stakeholders understand key revenue drivers and customer purchasing behavior.

[Back to the Top](#coffee-sales-analysis)

---

## Problem Statement  

Small businesses often lack visibility into granular sales patterns, such as top-performing items, seasonal peaks, or average order values. This dashboard addresses that gap by offering interactive insights into total sales, quantity sold, and order trends.

[Back to the Top](#coffee-sales-analysis)

---

## Data  

- **Source**: Internal point-of-sale export [data](data/CoffeeShopSales.xlsx)
- **Description**:
  - File: `CoffeeShopSales.xlsx`
  - Key fields: `Product`, `OrderDate`, `Sales`, `Quantity`, `TransactionID`, `Category`
  - Rows: ~1,000 transactions across multiple product categories and time periods

[Back to the Top](#coffee-sales-analysis)

---

## Approach

1. **Data Cleaning & Profiling**
   - Loaded Excel data into Power BI
   - Checked column quality, profile, and distribution using Power Query
2. **Data Modeling**
   - Created a custom Date table to enable time-based analysis
   - Established relationships and cleaned nulls/duplicates
3. **KPI Development**
   - Defined DAX measures for:
     - Total Sales
     - Total Orders
     - Total Quantity Sold
     - Average Sale per Order
4. **Visualization**
   - Built dynamic visuals (bar, line, card, pie) across 3 report sections:
     - Sales Overview
     - Product Breakdown
     - Time-Based Trends

[Back to the Top](#coffee-sales-analysis)

---

## Tools and Technologies

- Microsoft Power BI  
- Power Query  
- DAX for Measures  
- Power BI Service (for dashboard sharing)

[Back to the Top](#coffee-sales-analysis)

---

## Project Files

The following are the files in this project.

- [Coffee Sales Export Data](data/CoffeeShopSales.xlsx)
- [Microsoft Power BI Report](CoffeeSalesReport.pbix)

[Back to the Top](#coffee-sales-analysis)

---

## Project Outcome  

- Identified top 5 selling products and categories contributing to over 60% of revenue
- Highlighted sales peaks during weekends and seasonal spikes
- Delivered a self-serve dashboard used by business owners for daily sales tracking
- Enabled slice-and-dice filtering by date, product, and order type

[Back to the Top](#coffee-sales-analysis)

---

## How to Run

1. Clone or download the repo  
2. Open `CoffeeSalesReport.pbix` in Power BI Desktop  
3. Load the Excel file: `data/CoffeeShopSales.xlsx`  
4. Refresh the visuals and interact with filters  
5. Optional: View the published version [here](https://app.powerbi.com/view?r=eyJrIjoiN2QzNTc4ZmYtZTdlYy00NTcyLWJhYzUtNTRkNTg0OGJiYmMwIiwidCI6Ijk3ODIwYmJjLTE3ZjUtNGRmYy1iNjlkLTY5ZWJjOTRhYzZiZiJ9)

[Back to the Top](#coffee-sales-analysis)

---
## Conclusion  

The dashboard empowers coffee shop managers to make data-driven decisions about inventory, staffing, and promotions. It showcases the value of BI tools in small business operations. Future upgrades could include customer segmentation or cost analysis.

[Back to the Top](#coffee-sales-analysis)

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

[Back to the Top](#coffee-sales-analysis)

---

## Author Info

- Github - [Github Profile](https://github.com/prasanna-sriram)
- LinkedIn - [Prasanna Sriram](https://www.linkedin.com/in/prasanna-sriram/)
- Tableau - [Tableau Public Profile](https://public.tableau.com/app/profile/prasanna.sriram.ps)

[Back to the Top](#coffee-sales-analysis)