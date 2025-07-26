# Sales Trend Analysis Using Spreadsheets

## 📊 Overview 

This comprehensive analysis addresses a key stakeholder question: **What is the sales trend by month and how does it depend on the sales method, reason, country, and sellers?**

Spreadsheets was utilized as the primary data analytical tool to provide data-driven insights and actionable recommendations.

## 🎯 Research Questions

To provide a complete answer, the analysis was structured around six key questions:

1. **What kind of monthly sales volume trend exists?**
2. **What is the monthly sales trend by sales method (online vs. offline)?**
3. **In which countries is sales volume higher?**
4. **What is the main reason driving sales?**
5. **Is there a relationship between delivery time and sales volume?**
6. **Which sellers occupy leading positions in sales and sales volume?**

## 🔍 Key Findings

The analysis revealed the following insights about monthly sales trends:

### Sales Growth Pattern
- **Steady growth** observed from 2001 to 2003
- Orders are primarily made **online**, but **offline orders generate higher profits** in the second half of the year

### Geographic Distribution
- **United States** leads in order volume

### Customer Behavior
- Primary purchase drivers: **price and promotions**

### Delivery Performance
- Consistent **7-day delivery** from order placement
- **5-day average** between shipping and delivery
- This performance has been maintained throughout the observed period

### Top Performers
- **Leading seller**: the seller with an ID-277 (US market)

## 💡 Strategic Recommendations

Based on the analysis findings, we recommend:

### 1. Investigate Online vs. Offline Profit Disparity
**Issue**: Online sales generate less profit despite higher volume

**Potential causes**:
- Lower pricing strategy for online products
- Product type differences (large/expensive items sold offline vs. small/cheaper items online)

**Action**: Analyze product categories by sales channel to identify pricing optimization opportunities

### 2. Explore European Market Potential
**Issue**: Lower sales volume in Europe compared to other regions

**Investigation areas**:
- Regional staffing levels comparison
- Market-specific factors affecting sales performance
- Localization opportunities

## 🛠️ Methodology

### Data Processing
The analysis utilized a database containing **4 related tables**. A comprehensive merge table was created using advanced Google Sheets formulas:

- `ARRAYFORMULA` - for bulk operations
- `DAYDIFF` - for delivery time calculations  
- `VLOOKUP` - for data matching across tables
- `IF` - for conditional logic

### Analysis Approach
Following data preparation, **pivot tables** were employed for:
- Descriptive statistical analysis
- Data visualization and chart creation
- Trend identification

## 📈 Results & Visualizations

### 1. Monthly Sales Volume Trend

![alt text](<Monthly Sales Performance.png>)
*Overall monthly sales performance showing growth trajectory*

![alt text](<SUM of TotalDue .png>)
*Total revenue trends over the analysis period*

### 2. Sales Method Analysis (Online vs. Offline)

![alt text](<Monthly Sales Performance_ Online and Offline Orders .png>)
*Comparison of order volumes by sales channel*

![alt text](<Sum of Total Due_ Online and Offline Orders.png>)
*Revenue comparison between online and offline channels*

### 3. Geographic Sales Distribution

![alt text](<Proportions of Number of Orders According to Countries.png>)
*Market share distribution across countries*

![alt text](<Proportions of Number of Orders during the Months According to Countries.png>)
*Seasonal patterns by geographic region*

![alt text](<Proportion of Number of Orders in Different Countries According to Type of Order.png>)
*Sales channel preferences by country*

### 4. Sales Reason Analysis

![alt text](<Proportion of Number of Orders During the Months According to Type of Reason Sale.png>)
*Primary drivers of customer purchases by month*

### 5. Delivery Performance
**Key Metrics:**
- ⏱️ **Average delivery time**: 7 days from order
- 🚚 **Shipping to delivery**: 5 days average
- 📊 **Consistency**: Maintained throughout analysis period

### 6. Sales Team Performance
![alt text](<Proportion of Number of Orders According to Salesperson ID.png>)
*Individual salesperson contribution to total orders*

## 📋 Next Steps

1. **Conduct product category analysis** by sales channel
2. **Benchmark European market** against high-performing regions  
3. **Implement pricing optimization** strategies for online channels
4. **Monitor delivery performance** metrics continuously

---

*Analysis conducted using Spreadsheets | Data period: 2001-2003*
