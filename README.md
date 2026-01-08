# E-Commerce Sales Analysis Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📋 Table of Contents
- [Overview](#overview)
- [Dashboard Preview](#dashboard-preview)
- [Key Features](#key-features)
- [Key Insights](#key-insights)
- [Technical Stack](#technical-stack)
- [Data Analysis Process](#data-analysis-process)
- [Visualizations](#visualizations)
- [Business Impact](#business-impact)
- [Installation & Usage](#installation--usage)
- [Future Enhancements](#future-enhancements)
- [Contact](#contact)

## 🎯 Overview

This project presents a comprehensive **E-Commerce Sales Analysis Dashboard** developed using **Power BI** to analyze sales performance data from 2009-2010. The dashboard provides actionable insights into sales trends, customer demand patterns, and revenue distribution across products and geographical regions, enabling data-driven business decisions.

## 📊 Dashboard Preview

The interactive dashboard displays key metrics and visualizations including:
- **Total Revenue**: 10M
- **Total Quantity Sold**: 5M units
- **Total Orders**: 29K orders
- **Analysis Period**: January 2009 - January 2010

## ✨ Key Features

- **Interactive Filtering**: Dynamic slicers for country-wise analysis (Australia, Austria, Bahrain, Belgium, and more)
- **Real-time KPI Cards**: Instant view of critical business metrics
- **Trend Analysis**: Time-series visualization of sales performance
- **Product Performance Tracking**: Identification of top-selling products by revenue
- **Geographic Revenue Distribution**: Country-wise revenue contribution analysis
- **Responsive Design**: User-friendly interface with drill-down capabilities

## 🔍 Key Insights

### Sales Performance
- **Top-performing Products**: WHITE HANGING HEART, REGENCY CAKESTAND, and STRAWBERRY CHARLOTTE BAG lead in sales volume
- **Seasonal Trends**: Clear identification of peak sales periods throughout 2009-2010
- **Order Volume**: Successfully processed 29,000+ orders across the analysis period

### Geographic Analysis
- **United Kingdom**: Dominant market with 485.85K orders (92.46% of total revenue)
- **EIRE**: Secondary market contributing 9.67K orders (1.84%)
- **Emerging Markets**: Additional presence across 15+ countries including Germany, France, Netherlands, and Spain

### Product Insights
- Top 3 products generated significant revenue concentration
- Product catalog includes 19+ tracked items with varying performance levels
- Clear differentiation between high-performers and niche products

## 🛠 Technical Stack

- **Business Intelligence Tool**: Power BI Desktop
- **Data Processing**: Power Query Editor
- **Calculations**: DAX (Data Analysis Expressions)
- **Data Sources**: E-commerce transactional data (2009-2010)

## 📈 Data Analysis Process

### 1. Data Collection & Preparation
- Imported raw e-commerce sales data into Power BI
- Cleaned and transformed data using Power Query
- Handled missing values and data inconsistencies
- Standardized date formats and product descriptions

### 2. Data Modeling
- Created relationships between dimension and fact tables
- Designed star schema for optimal query performance
- Implemented calculated columns for derived metrics

### 3. DAX Measures Implementation
```dax
Total Revenue = SUM(Sales[Revenue])
Total Quantity = SUM(Sales[Quantity])
Total Orders = COUNTROWS(Sales)
Revenue % = DIVIDE([Total Revenue], CALCULATE([Total Revenue], ALL(Sales[Country])))
```

### 4. Visualization Development
- Designed intuitive dashboard layout
- Applied consistent color schemes and branding
- Implemented interactive cross-filtering
- Optimized visual performance

## 📊 Visualizations

| Visual Type | Purpose | Key Metric |
|------------|---------|------------|
| **KPI Cards** | Display summary metrics | Revenue, Quantity, Orders |
| **Bar Chart** | Product performance comparison | Count of Revenue by Description |
| **Line Chart** | Time-series trend analysis | Count of Revenue by Year |
| **Donut Chart** | Geographic revenue distribution | Count of Revenue by Country |
| **Slicer** | Interactive country filtering | Multi-select country filter |
| **Table** | Detailed Australia sales breakdown | Revenue by Country |

## 💼 Business Impact

This dashboard enables stakeholders to:

✅ **Identify Profitable Products**: Focus inventory and marketing on high-revenue items  
✅ **Optimize Inventory Management**: Align stock levels with demand patterns  
✅ **Strategic Market Expansion**: Understand geographic performance for targeted growth  
✅ **Seasonal Planning**: Prepare for peak sales periods with adequate resources  
✅ **Data-Driven Decisions**: Replace intuition with concrete performance metrics  

## 🚀 Installation & Usage

### Prerequisites
- Power BI Desktop (Latest Version)
- Windows 10 or later

### Steps to Use
1. Clone this repository
   ```bash
   git clone https://github.com/Sanjaymo/FUTURE_DS_01.git
   ```
2. Open the `.pbix` file in Power BI Desktop
3. Refresh data connections if needed
4. Explore the interactive dashboard
5. Customize filters and slicers as per requirements

### Publishing (Optional)
- Publish to Power BI Service for web access
- Configure automatic data refresh schedules
- Share with stakeholders via secure links

## 🔮 Future Enhancements

- [ ] Integration with real-time data sources
- [ ] Customer segmentation analysis using RFM modeling
- [ ] Predictive analytics for demand forecasting
- [ ] Product recommendation engine
- [ ] Mobile-optimized dashboard layout
- [ ] Advanced filtering with year-over-year comparisons
- [ ] Profitability analysis including cost metrics
- [ ] Customer lifetime value (CLV) calculations

## 📝 Learnings & Takeaways

- Mastered Power BI dashboard design principles
- Developed proficiency in DAX for complex calculations
- Gained experience in data cleaning and transformation
- Understood business metrics crucial for e-commerce analytics
- Learned to present data insights in an actionable format

## 📧 Contact

**Your Name**  
📧 Email: sanjaychoudhari288@gmail.com  
💼 LinkedIn: [Sanjay Choudhari](https://www.linkedin.com/in/sanjaychoudhari09/)  
🐙 GitHub: [Sanjaymo](https://github.com/Sanjaymo)

---

### 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### ⭐ Acknowledgments
- Internship Organization: [Future Interns](https://futureinterns.com/)
- Dataset Source: E-commerce transactional data (2009-2010)
- Power BI Community for continuous learning resources

---

**If you found this project helpful, please consider giving it a ⭐!**
