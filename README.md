**Power BI Report: Superstore Sales Analysis**

**Problem Statement**

The objective of this report is to analyse sales patterns in a superstore and derive insights into customer preferences, shipping modes, and profit trends. By visualizing key metrics and filtering data by region and other dimensions, this report identifies high-performing segments, profitable categories, and seasonal trends to aid in strategic decision-making.

**Report Overview**

This Power BI report provides a comprehensive dashboard for analysing superstore sales data across various dimensions such as category, region, and time. It leverages interactive visuals and filters to help stakeholders gain insights into sales trends, customer behaviour, and profit distribution.



![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Dashboard.png)

**Data Source**

- **Superstore Sales Data (provided dataset)**

**Key Visuals and Features**

1. **Map Visualization**
    - Purpose: Displays Sum of Sales and Sum of Profit by State, allowing quick geographic insights into top-performing regions.

![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Screenshot%20(109).png)

1. **Clustered Bar Charts**
    - **Sales by Ship Mode:**
        - Shows the popularity of different shipping methods. Standard Class was the most used (0.33 million users), followed by Second Class (0.11 million), First Class (0.08 million), and Same Day (0.03 million).
    - **Sales by Category:**
        - Indicates sales distribution across product categories. Office Supplies had the highest sales (0.64 million), followed by Technology (0.47 million) and Furniture (0.45 million).
    - **Sales by Subcategories:**
        - Highlights top-selling items with Phones (0.2 million), Chairs (0.18 million), and Binders (0.17 million) leading in subcategory sales.

![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Sales%20by%20ship%20mode.png)
![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Sales%20by%20Category.png)
![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Sales%20by%20Subcategory.png)

2. **Slicers**
    - Regions (West, North, South, East): Filters data visuals by region, providing region-specific insights.

![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Slicer.png)

3. **Pie Charts**
    - **Sales by Segment:**
        - Consumer purchases account for 48% of sales, Corporate for 33%, and Home Office for 19%.
    - **Payment Methods:**
        - COD was the most popular payment method (43%), followed by Online (35%) and Card (22%).

![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Sales%20By%20segment.png)
![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Sales%20by%20Payment%20mode.png)

4. **Line Charts**
    - **Monthly Sales by Year (2019 and 2020):**
        - Sales peaked in December due to festive season demand, with 2020 sales nearly doubling compared to 2019.
    - **Monthly Profit:**
        - Profit increased significantly in 2020, with March, October, and December being the most profitable months, while April and November saw the least profit.

![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/MOnthly%20Profit%20by%20year.png)
![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Month%20sales%20by%20Year%20.png)

5. **Summary Cards**
    - Total Sales, Total Profit, and Average Shipping Days: Displays overall metrics at a glance, with an average shipping time of 4 days.

![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Cards.png)

6. **Sales by State**
    - A bar chart showing that California led in sales, followed by New York, highlighting high-revenue states.

![](https://github.com/mayurkini/Super-Store-Sales-Analysis/blob/main/Sales%20by%20state.png)

7. **DAX Calculations and Filters**
    - Utilized DAX and various filters to streamline data manipulation and enhance insights, making the report interactive and easy to explore.

**Key Insights**

- **Shipping Mode Trends:** Standard Class is the preferred shipping mode, emphasizing the importance of cost-effective shipping.
- **Product Category Performance:** Office Supplies is the top-selling category, followed by Technology and Furniture.
- **Regional Sales Insights:** California and New York are the top revenue-generating states, suggesting potential for targeted marketing efforts.
- **Segment and Payment Preferences:** Consumers represent the largest segment, with COD being the most popular payment method.
- **Seasonal Sales Patterns**: Sales and profits peak in December, demonstrating a correlation with the festive season.
- **Year-Over-Year Growth:** 2020 sales nearly doubled those of 2019, indicating possible strategic improvements or external factors.

**Technical Specifications**

- **Power BI Version: Compatible with Power BI Desktop and Service.**
- **Data Refresh Frequency: Manual**
- **Modelling: Implemented DAX for calculated metrics and used custom filters for targeted analysis.**

**Future Enhancements**

- **Automated Data Refresh: Integrate scheduled refresh for updated insights.**
- **Detailed Profit Analysis: Provide a deeper breakdown of profit by subcategory to identify high-margin products.**
- **Enhanced Forecasting: Add predictive models to forecast future sales and profit trends.**
