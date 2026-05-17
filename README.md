# Bank Marketing Campaign Analysis

## 📋 Project Overview

This project analyzes the **Bank Marketing Campaign Dataset** from a Portuguese banking institution. The data contains information about direct marketing campaigns through phone calls conducted to sell **term deposits**
The main objective was to understand customer behavior and identify the key factors that influence whether a client will **subscribe** to a term deposit.
The analysis was performed primarily in **Microsoft Excel*, and an interactive **Power BI dashboard** was built for clear visualizations and business insights.

## 🎯 Project Objectives

- Explore and clean the dataset using Microsoft Excel.
- Identify the major drivers of term deposit subscription.
- Analyze the impact of age, job, marital status, education, campaign duration, previous outcomes, and economic indicators.
- Build interactive PivotTables in Excel.
- Create a professional interactive dashboard in Power BI.
- Provide actionable recommendations to improve future marketing campaign performance.

## 🛠️ Tools & Technologies Used

- **Microsoft Excel** – Data cleaning, transformation, and PivotTables
- **Power BI** – Interactive Dashboard Development
  

## 📊 Dataset Information

- **Dataset Name**: Bank Marketing (bank-additional-full)
- **Total Records**: 41,176 customers after removing 12 duplicates
- **Target Variable**: `y` (Subscription: "yes" / "no")
- **Total Subscriptions**: 4,639
- **Overall Subscription Rate**: **11.27%**

## 🧹 Data Preparation

- Loaded raw data and performed initial exploration.
- All data were in one column so separation of data was done to their specific columns
-Removed duplicate rows using Excel Remove duplicates feature where 12 duplicates were removed
- Standardized column names.
- Added new calculated column for better segmentation and analysis (call duration categories)
- Prepared the data for PivotTable analysis and Power BI import.

## 📈 Key Insights

The analysis revealed the following:

- **Overall Subscription Rate**: 11.27% (4,639 successful subscriptions out of 41,176 contacts). 
- **Call Duration** is the strongest predictor, longer calls have a significantly higher subscription rate.
- **Previous Campaign Outcome** matters greatly:
  - Customers with `success` in previous campaign had much low subscription rates compared to failure, and in the current campaign the non-existed customers are the one who subscribed more than others.
- **Contact Method**: Cellular contacts performed better than telephone.
- **Month of Contact**: May was the month which had higher number of attended customers and also it’s the month with higher subscription number unlike other months.
- **Pprevious**: Customers who were never contacted before showed and subscribed more than the one who were contacted before.
-**Housing and personal loan**: Customers with housing loan subscribed more unlike the ones with personal loans.
- **Economic Indicators** (euribor3m, employment variation rate) showed clear correlation with campaign success.

**Positive Findings:**
- The bank has been successful in converting customers who were contacted for longer call durations.
- Additional services and targeted follow-ups appear to be working well for certain customer segments.
- The bank was success to make new customers, who were never contacted to subscribe more.
-The bank was able to contact many customers in May and make them subscribe in high rate.

## 💡 Business Recommendations

Based on the insights, here are actionable recommendations for the bank:

1. **Optimize Call Strategy**  
   Train agents to engage customers longer during calls, as duration strongly correlates with success.

2. **Put more efforts in every month**  
   From the insight it shows may was the successful month because it was the first month of the campaign, this energy should be put to every other month to get more customers.

3. **Seasonal Campaign Planning**  
   Increase marketing efforts during high-performing months.

4. **Target High-Potential Segments**  
   Focus more on students, retired customers, and those with university degrees.

5. **Improve Contact Method**  
   Shift more campaigns toward cellular contacts where possible.

6. **Incentivize Longer-Term Engagement**  
   Develop follow-up strategies and offers for customers who show interest but don’t subscribe immediately.
   
7. **Another marketing strategy**
Finding another marketing scheme to get more customers, different from phone calls.

