# Blinkit Grocery Sales Dashboard — Power BI

An interactive Power BI dashboard that analyzes Blinkit grocery sales data to understand which products, outlets and locations bring in the most sales.

![Dashboard](dashboard.png)

## About the Project

Blinkit is an Indian quick-commerce grocery app. In this project I took 8,500+ rows of Blinkit sales data, cleaned it, and built a one-page dashboard. It shows sales performance by product type, fat content, outlet size, outlet type, city tier and outlet opening year.

## Tools Used

- **Excel** – raw data
- **Power BI** – dashboard and charts
- **Power Query** – data cleaning
- **DAX** – measures for KPIs

## Dataset

| Detail | Value |
|---|---|
| Rows | 8,523 |
| Products | 1,559 |
| Item categories | 16 |
| Outlets | 10 |

Main columns: Item Type, Item Fat Content, Outlet Size, Outlet Location Type, Outlet Type, Outlet Establishment Year, Sales, Rating.

## Data Cleaning

- Fixed inconsistent fat-content labels (for example "LF" and "low fat" → **Low Fat**, "reg" → **Regular**).
- Checked column data types and removed formatting issues.

## KPIs

| KPI | Value |
|---|---|
| Total Sales | $1.20M |
| Average Sales | $141 |
| Number of Items | 8,523 |
| Average Rating | 3.9 |

## Dashboard Features

- KPI cards for Total Sales, Average Sales, Number of Items and Average Rating
- Sales by Fat Content (donut chart)
- Sales by Item Type (bar chart)
- Fat Content by Outlet Tier (clustered bar chart)
- Sales by Outlet Size (donut chart)
- Sales by Outlet Location (funnel chart)
- Sales trend by Outlet Establishment Year (line chart)
- Outlet Type summary table (matrix)
- Filter panel for Outlet Location Type, Outlet Size and Item Type
- Buttons to switch the charts between Total Sales, Avg Sales, No. of Items and Avg Rating

## Key Insights

1. **Tier 3 cities bring the most sales** – about 39% of total sales.
2. **Supermarket Type1 outlets lead** – about 65% of total sales.
3. **Fruits & Vegetables and Snack Foods** are the top-selling categories.
4. **Low Fat products** make up about 65% of sales.
5. **Medium-size outlets** bring the most sales (about 42%).
6. Outlets opened in **2018** have the highest sales.
7. Customer ratings are almost the same across all outlet types (around 4.0).

## Files in this Repository

| File | Description |
|---|---|
| `Blinkit_Dashboard.pbix` | Power BI dashboard file |
| `BlinkIT_Grocery_Data.xlsx` | Raw dataset |
| `dashboard.png` | Dashboard screenshot |

## How to Open

1. Download or clone this repository.
2. Install **Power BI Desktop** (free) from Microsoft.
3. Open `Blinkit_Dashboard.pbix`.

## Author

**Pawan Jangid** – MCA (Cyber Security), JECRC University
[LinkedIn](https://www.linkedin.com/in/pawanjangid7799/) · [GitHub](https://github.com/Pawanjangid4424)# Blinkit-Sales-Dashboard-PowerBI
