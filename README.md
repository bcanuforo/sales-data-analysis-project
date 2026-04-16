# Sales Data Analysis Project

## Business Objective
Analyze 200 sales transactions to identify top-performing products and regions, uncover sales trends, and provide actionable recommendations to increase revenue.

## Tools Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab

## Dataset
- **Rows**: 200  
- **Columns**: 7  
- **Columns**: `OrderID`, `Date`, `Product`, `Region`, `Quantity`, `UnitPrice`, `Revenue`

---

## Project Overview
This project analyzes sales data from 2025 to understand product and regional performance. The goal is to deliver clear, data-driven insights and practical recommendations that can help optimize inventory, marketing efforts, and regional strategies to drive revenue growth.

## Key Insights

1. **Product Performance**
   - **Clothes** is the top revenue generator with **₦140,476** (27.9% of total revenue).
   - **Shoes** follows with **₦103,048**.
   - **Laptops** performed the weakest with **₦77,550**.

2. **Regional Performance**
   - **West** region leads with **₦156,565** (31.1% of total revenue).
   - **East** is the second strongest region with **₦124,625**.
   - North and South regions show relatively lower performance.

3. **Overall Metrics**
   - Total Revenue: **₦503,060**
   - Average Order Value (AOV): **₦2,515**
   - Average Quantity per Order: **4.87 units**

4. **Monthly Trend**
   - Sales showed fluctuations throughout 2025 with no strong seasonal pattern visible in this dataset.

## Business Recommendations

- **Focus on Clothes** — Allocate more marketing budget and stock variety for this category, especially in the **West** region.
- **Expand in West Region** — Strongest performing region. Consider increasing distribution points or running targeted promotions here.
- **Improve Laptops Performance** — Investigate reasons for low sales and introduce bundle offers (e.g., Laptop + Accessories).
- **Monitor Trends** — With additional historical data, implement demand forecasting to better plan inventory.
- **Expected Impact** — A focused strategy on top product and top region could potentially increase revenue by **15–25%** in the next quarter.

## Visualizations Included
- Revenue by Product (`revenue_by_product.png`)
- Revenue by Region (`revenue_by_region.png`)
- Monthly Revenue Trend (`monthly_revenue_trend.png`)

*(Screenshots of these charts are available in the repository)*

## How to Run the Project

1. Open the notebook in Google Colab:  
   [`Sales_data_Analysis.ipynb`](Sales_data_Analysis.ipynb)

2. Run the first cell to upload `sales_data.csv`.

3. Execute the remaining cells to reproduce the analysis and generate visualizations.

## Future Improvements
- Add customer segmentation (RFM analysis)
- Build an interactive dashboard using Streamlit or Power BI
- Perform statistical significance tests between regions
- Integrate SQL version of the analysis

## Author
**Anuforo Boniface**  
Location: Owerri, Imo, Nigeria  
