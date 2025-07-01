# KHABOM SOLUTIONS - Sales Analysis & Business Growth Report

> Transforming Pharmaceutical Data into Actionable Insights for Strategic Growth

---

![image](https://github.com/user-attachments/assets/f8ef7855-b653-4c30-abc7-f8e22ad26a04)


---

## PROJECT OVERVIEW

Khabom Solutions is a premier pharmaceutical distributor committed to delivering essential medicines and healthcare products to hospitals, pharmacies, and individual customers across North America. Despite its strong market presence, the company faced significant operational challenges in 2023 that adversely affected its revenue growth and overall profitability. Key issues included frequent stockouts, suboptimal inventory management practices, and a lack of actionable insights into customer purchasing behaviors and product performance.

To address these challenges, this Power BI project was initiated to develop a comprehensive, end-to-end sales analysis solution designed to transform complex and disparate raw data into a cohesive and dynamic business intelligence ecosystem. Leveraging advanced data modeling techniques, key performance indicator (KPI) development, and intuitive visual analytics, the solution empowers Khabom Solutions with real-time, data-driven visibility into critical business metrics.

Specifically, the project enables detailed analysis of product sales trends, customer segmentation and buying patterns, regional market performance, and emerging strategic opportunities. By delivering clear, actionable insights, this initiative supports informed decision-making, enhances inventory optimization, reduces stockouts, and drives improved revenue and profitability for the organization.

---

## PROJECT OBJECTIVES

- Analyze top and bottom-performing drugs by revenue, units sold, and margin  
- Perform a comprehensive sales analysis using historical transaction data
- Identify high and low-performing pharmaceutical products by profit, revenue, and demand
- Analyze customer segments across age, gender, status, and buyer type
- Understand seasonal trends and detect anomalies like stockouts and underperformance
- Visualize business-critical KPIs with Power BI dashboards for real-time decision-making
- Translate insights into strategic recommendations for NovaMed’s executive leadership

---

## SKILLS & CONCEPTS DEMONSTRATED

| Category               | Techniques / Concepts Applied |
|------------------------|-------------------------------|
| Business Intelligence  | Power BI dashboards, KPI tracking, customer segmentation |
| Data Modeling          | Star schema, ERD design, normalization |
| Analytical Thinking    | Profitability, margin analysis, revenue forecasting |
| Power BI Development   | DAX measures, drill-through, bookmarks, tooltips |
| Data Cleaning          | Power Query transformations, field renaming, datatype handling |
| Strategic Reporting    | Executive-ready insights and business recommendations |

---

## BUSINESS CHALLENGES IDENTIFIED

- Lack of predictive inventory planning tools leading to frequent **stockouts**
- Underperforming seller channel accounting for just **12.4%** of revenue
- Inefficient marketing segmentation resulting in untapped opportunities
- Poor visibility into **low-margin** drugs eroding profitability
- Incomplete **customer demographic classification**, especially gender
- Regional concentration in North America — minimal reach in Europe

---

## POWER BI TECHNIQUES

- **Data Transformation** using Power Query for data cleaning and integration  
- **Dynamic Visuals**: Slicers, drill-throughs, and tooltips to navigate insights  
- **Custom Measures**: DAX-based KPIs for total revenue, profit, margin, and per-customer metrics  
- **Segmentation Filters**: Customer types (Preferred, Frequent, New), Drug tiers (Top 5, Bottom 5)  
- **Time-Series Analysis**: Monthly trend lines to identify seasonal patterns  
- **Geo Analysis**: Regional performance with map visuals for USA, Canada, Mexico  

| Technique             | Purpose                                               |
|----------------------|--------------------------------------------------------|
| Power Query Editor    | Data shaping, filtering, and cleansing                |
| DAX Measures          | Creating KPIs like Profit Margin, Revenue per Buyer   |
| Drill-Through Pages   | Deep dives into customer or drug-level insights       |
| Dynamic Slicers       | User-controlled views by year, region, or category    |
| Tooltips & Bookmarks  | Enriched, intuitive dashboard navigation              |
| Custom Themes         | Aligned report visuals to pharmaceutical brand style  |

---

## DATA MODELLING: ENTITY-RELATIONSHIP DIAGRAM (ERD)

The data model follows a **star schema**, optimized for slicing performance in Power BI.

- `SalesFact`: Central transactional table with measures for units sold, revenue, COGS, and profit  
- `Drugs`: Drug-level metadata including category, cost, and region availability  
- `Customers`: Buyer demographics (gender, age group, type, frequency)  
- `Date`: Linked to time-based analysis  
- `Regions`: Regional dimension for country and city-level analysis

---
![image](https://github.com/user-attachments/assets/44a043c9-76ca-45c1-a8cf-29a891421fcf)


![image](https://github.com/user-attachments/assets/e2616a05-660a-470e-9b65-e8bb16c4eb5c)


## POWER BI DASHBOARDS & INSIGHTS

The solution includes multiple interactive dashboards focused on performance management, customer behavior, and product analysis.

### Top vs. Bottom Drug Performance
- **Top 5 drugs** accounted for **22.4%** (~$9.03M) of total revenue with high profit margins and widespread adoption
- **Bottom 5 drugs** yielded minimal to negative profit due to poor demand, high cost, and weak marketing
- Insights used to prioritize product portfolio optimization

---

![SCREEN 1](https://github.com/user-attachments/assets/2074de99-bc32-4d1a-8ee6-d1a907a63449)

---

### Regional Performance Breakdown
- **USA**: 43% of revenue  
- **Canada**: 31%  
- **Mexico**: 26%  
- Minimal revenue from France, UK, and Germany indicates potential for expansion
- Dashboards track revenue trends by geography to support market-entry decisions

---

### Monthly Sales Trends
- **Q2 Growth Spike**: Driven by high-volume orders from healthcare institutions
- **August Drop**: Caused by **understocking** of top drugs due to inaccurate forecasting
- **November Margin Peak**: Achieved through targeted pricing and cost control campaigns

---

### Customer Segmentation Analysis
- Revenue drivers:
  - **Preferred customers** and **New customers** equally contributed to revenue, highlighting a strong acquisition/retention balance
  - Age groups **31–45** and **18–30** were the most profitable
- Gender segmentation incomplete — a large portion marked as “Other”
- Repeat customers showed signs of churn, especially in Q4

---

## DATA MODELING & ENTITY RELATIONSHIP DIAGRAM (ERD)

A structured star schema was designed for analytical efficiency. This supports fast slicing, dicing, and aggregation in Power BI.

![image](https://github.com/user-attachments/assets/2286f771-9b82-48c6-b4bc-a6e97ffaddd8)


### Data Entities

- **SalesFact**: Central table with transactional data (units, revenue, COGS, profit)
- **Drugs**: Drug name, type, manufacturing cost, classification
- **Customers**: Demographics including age, gender, customer type, region
- **Date**: Date table for time intelligence
- **Region**: Country and location metadata

![SCREEN 2](https://github.com/user-attachments/assets/3c614061-6d56-4581-9a81-af0ce0cfcd3a)

---

## KEY PERFORMANCE INDICATORS (KPIs)

| Metric                      | Value       | Strategic Insight |
|----------------------------|-------------|-------------------|
| Total Revenue              | $40.3M      | High demand captured in sales |
| Total Profit               | $33.1M      | Strong margin generation |
| COGS                       | $7.2M       | Lean cost structure |
| Profit Margin              | 82.06%      | Outstanding efficiency |
| Avg. Revenue per Customer  | $202K       | Indicates high-value base |
| Customer Count             | 200         | Emphasizes need for retention focus |

---

## STRATEGIC RECOMMENDATIONS

### 1. **Scale Top Performing Drugs**
- Ensure 100% availability across high-demand months
- Renegotiate supplier contracts for cost savings
- Monitor high-margin SKUs weekly

*Expected Impact: +10% increase in high-season revenue*


### 2. **Customer Loyalty & Personalization**
- Introduce tiered loyalty programs for preferred and frequent buyers
- Use purchase history and age data for personalized product recommendations

*Expected Impact: 15% increase in repeat purchase frequency*


### 3. **Demographic-Driven Campaigns**
- Launch campaigns targeting 18–45 age groups using age-appropriate health messages
- Segment marketing lists by buyer type and customer tenure

*Expected Impact: Improved engagement, reduced acquisition cost*


### 4. **Revamp Inventory Planning**
- Implement predictive analytics for demand forecasting
- Introduce buffer stock rules for top SKUs
- Automate reorder triggers with supplier SLAs

*Expected Impact: 12% reduction in lost sales due to stockouts*


### 5. **Seller Channel Development**
- Relaunch onboarding programs and offer co-branded campaigns
- Align incentives with product margin performance

*Expected Impact: +20% seller channel contribution to revenue*


### 6. **Regional Expansion Strategy**
- Focus on France, UK, and Germany as pilot markets
- Use performance data from North America to tailor entry strategy

*Expected Impact: New revenue streams within 12–18 months*

---

## CONCLUSION

This project exemplifies how data, when modeled, analyzed, and visualized correctly, can transform decision-making in healthcare and pharmaceuticals. NovaMed Solutions can now move forward with clear insight into customer behavior, product success, and operational blind spots  positioning the business for sustainable, data-informed growth.

With integrated Power BI dashboards, stakeholders can now:
- Detect real-time changes in sales and product behavior  
- Strategically allocate marketing and inventory investments  
- Optimize procurement and expand into new markets confidently

---

> ⚠️ **Disclaimer**  
Disclaimer⚠️: The datasets, analyses, and reports presented in this portfolio are synthetic and created solely for demonstration purposes. They do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. These examples are designed to showcase my technical skills in data science and data analysis while adhering to ethical guidelines and respecting data privacy.
