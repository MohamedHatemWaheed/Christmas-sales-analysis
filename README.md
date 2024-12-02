# 🎄 Christmas Sales Analysis Dashboard 🎅

## Introduction
Welcome to the **Christmas Sales Analysis Dashboard**! This project showcases a comprehensive analysis of sales data during the Christmas season, focusing on trends, customer behaviors, and key performance indicators (KPIs). The goal was to clean and transform the data into actionable insights using powerful data visualization techniques. This analysis highlights patterns that can help in strategic decision-making, ensuring business growth during the holiday season. Dive into the details below to see how each step of the process, from data cleaning to visualization, contributes to uncovering valuable insights.

## 📊 Project Overview

This project consists of two main phases:

1. **Data Cleaning using Excel (Query)**: Preparing the dataset to ensure accuracy and consistency.
2. **Data Visualization using Power BI**: Generating visual insights for better understanding and decision-making.

### 📍 Data Cleaning:

1. **Date Format**: Corrected the date format to show only the date without the time component.

2. **Decimal Adjustment**: Adjusted decimal columns to display only two decimal points for better readability.

3. **Discount Column**: Converted the discount column to a percentage format for consistency.

4. **Handling Missing Data in Shipping Method Column**:
   - About 50% of the `Shipping Method` column was missing. After investigating, I found that these empty values corresponded to orders picked up offline (without shipping). Therefore, I replaced the nulls with "On-site" to accurately reflect customer behavior.
   - Similarly, the `Delivery Time` column had missing values for these offline orders. Since there was no shipping involved, I filled these with 0.

5. **New Column: Shipping Method Type**:
   - Created a new column called `Shipping Method Type` with two values:
     - **"Offline"**: For orders picked up at the store.
     - **"Online"**: For all other shipping methods.

### 📍 Data Visualization & Comprehensive Sales Report:

2. **Key Performance Indicators (KPIs)**:
   - **Total Sales**: Achieved M1.63.
   - **Top Product Returns**: Electronics had the highest return rate with 1,062 units returned. This indicates a need for a quality review to address return reasons.
   - **Top Payment Method**: Cash transactions led with 2,540 payments.
   - **Customer Satisfaction**: Average rating of 2.98 out of 5, indicating an opportunity for improvement.
   - **Total Transactions**: Online transactions reached 5,418, while offline transactions totaled 4,582.

3. **Sales Trends Over Time**:
   - Analyzed sales from 2018 to 2023 and noticed a significant sales boost in 2023. This indicates that improvements made after the 2022 Christmas season addressed customer concerns and drove more sales.

4. **Top-Selling Products**:
   - Toys led the sales, representing the highest-performing product category.

5. **Return Rates by Gender**:
   - Men returned products at a higher rate (34.37%) compared to women (32.31%).

### 🚀 Future Strategies:

1. **Product Quality Improvement**: Focus on enhancing the quality of electronic products to reduce return rates.
2. **Customer Satisfaction**: Improve customer service to address all client concerns, which should help boost overall satisfaction scores.

---

## Conclusion
This project has provided valuable insights into Christmas sales trends and customer behavior, highlighting areas for improvement in product quality and customer service. By acting on these insights, businesses can enhance customer experiences and drive future sales.

Feel free to check the code and visuals in this repository, and I'd love to hear your feedback or suggestions!


For any inquiries or collaboration opportunities, feel free to [click here](https://www.linkedin.com/in/mohamed-hatem-921936258) to connect with me on LinkedIn or send me on my Email: mohamedhatemwaheed@gmail.com
