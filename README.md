# Understanding Shopping Patterns and Optimizing Customer Experience

## Title: E-commerce Customer Behaviour Analysis for the ECs Core Unit

## Table of Contents

- [Overview](#overview)
- [Data Source](#data-source)
- [Problem Statement](#problem-statement)
- [Tools and Methodology](#tools-and-methodology)
- [Dashboard](#dashboard)
- [Key Analysis Findings](#key-analysis-findings)
- [Limitations](#limitations)
- [Recommendations](#recommendations)
- [Conclusion ](#conclusion)
- [Links](#links)


## Overview
The analysis reveals insightful patterns in customer behavior across different demographics, devices, and touchpoints in the ecommerce journey. The goal was to uncover how customers engage with the platform, where they drop off, and what influences their purchasing decisions. The findings point to targeted opportunities for boosting engagement and conversion rates.

## Data Source
The dataset was provided by the ECs Core Unit Team. It contains 500 rows and 9 columns.

## Problem Statement
There's a need to understand how our e-commerce customers behave on our platform to identify opportunities for improving sales performance and customer engagement, but we currently lack insights into the relationships between customer characteristics, browsing patterns, and actual purchasing decisions.

Specific Business Problems Being Addressed:

- Understanding the distribution and characteristics of customer demographics (e.g., age, gender, location).
- Exploring how different types of devices are used by customers and their impact on behavior.
- Investigating the relationship between browsing time, pages viewed, items added to the cart, and actual purchases.
- Segmenting customers based on their behavior and identifying distinct customer groups.
- Analyzing the customer journey and identifying potential areas for improvement in the conversion funnel.
- Assessing the impact of customer behavior on revenue generation and identifying opportunities for increasing sales and customer engagement.

Success Criteria for Solving This Problem:

The analysis aims to provide actionable insights that will:
- Increase overall conversion rates
- Improve customer engagement and satisfaction
- Optimize marketing spend and website investment priorities
- Enable personalized customer experiences
- Identify the highest-value customer segments for focused attention


## Tools and Methodology:

*Tools:* 

Power BI: Dashboard creation and visualization.

DAX: Wrote DAX codes to calculate measures for key metrics.

Power Query: Data cleaning and preliminary analysis.

*Methodology:*

Data Cleaning: This process involved inspecting data for inconsistencies, creating new columns (eg, Age group and Customer Segments), ensuring accurate data format, and validation to facilitate regularity and accuracy.

Data Processing: Used Power BI's DAX functionality  and field parameters to calculate custom measures to fully uncover granular insights within the dataset.
Eg: creating customer segments from shopping behaviour

NB: Explore other DAX measures in the Pbix file below.

Data Visualization: Built a 2-page interactive dashboard in Power BI that efficiently displays key metrics and trends to improve customer conversion and revenue generation.

## Dashboard

## Overview Page

<img width="561" height="343" alt="ESales Overview" src="https://github.com/user-attachments/assets/eed33c63-23f8-4a2a-bca9-5fb2c1be5d0d" />


## Customer Journey

<img width="559" height="343" alt="Esales CJ Learnable" src="https://github.com/user-attachments/assets/0e4d94a0-ab1a-4ff2-ad4b-2d468063d4dd" />


## Key Analysis Findings

*Overview*

What is the behavioural impact of device choice, gender, and location on e-commerce browsing habits and final purchases?

The data reveals a total distinct count of 500 customers, 52.2% Male, 47.8% Female and  an average age of 26 years. It also shows that while mobile users dominate in traffic (35.6%), tablet users exhibit the highest engagement in browsing time and conversion efficiency. Additionally, Delhi and the age group 18-22 leads in purchases. Below are the key insights: 

Mobile accounts for the largest share of users (35.6%) but has the lowest conversion rate (44.8%) from cart to purchase. Tablet users, though fewer (32.6%), show higher engagement with a 32-minute browsing time on average and the best Cart-to-Purchase Conversion of 48.4% (400 purchases / 827 cart additions). Lastly, Desktop users (31.8%) have the lowest engagement but still maintain a 51.4% conversion rate (381 purchases / 741 cart additions).

Women across most age groups have the highest browsing time on average, page views, and items added to cart, men show a significant gap in the total purchase leading across all age groups, especially age group 18-22, leading in total purchase for both men and women.

Location-wise, Delhi leads in total purchase of 191, and Kolkata follows closely at 190. Areas like Pune underperform in total purchase, and Chennai with the least number of customers, suggesting a need for targeted campaigns.

*Customer journey*

What is the customer journey like?

The customer journey reveals a healthy but optimizable conversion pattern:

15,370 customers engaged with products, 13,591 total pages viewed (88.43% retention), 2,575 items added to cart (18.95% of viewers), 1,232 completed transactions (47.84% cart conversion).  This shows that cart conversion drops significantly between added to cart and an actual purchase revealing 52.2% abandonment rate.

The relationship between browsing time and purchases shows longer browsing time (especially on Mobile) correlated with higher purchases. However, some Desktop and Tablet users had moderate browsing time with lower purchases.

Behavioural Segmentation Insights:
High-Value Buyers (67.2% of customers) are the dominant segment, demonstrating strong purchasing behaviour and represent the core revenue-generating group.
Cart Abandoners (19%) are a significant segment that adds items but doesn't complete purchases, representing immediate conversion optimization opportunities. Window Shoppers (13.8%) are browsers who don't add items to the cart, indicating potential for better product positioning or personalization.

The analysis reveals interesting age-related on average behaviours:
18-22 age group: Shows high page views but moderate cart additions
23-27 and 28-32 age group: Demonstrates balanced browsing and purchasing behaviour
Ages 33-35: Shows efficient shopping with the highest viewing patterns.

## Limitations
Behavioral Analysis Gaps

No Purchase Value Data: While we know the number of purchases (1,232), the data didn’t have revenue amounts, average order values, or product pricing information. This makes it impossible to assess the true business impact of different customer segments.

Missing Temporal Patterns: Lack of seasonal information (time of day, day of week, seasonal trends), limits our ability to optimize timing for interventions like cart abandonment emails.

## Recommendations
1. Improve Cart-to-Purchase Conversion
Why it matters: Nearly half of shoppers abandon their cart without buying.
What to do:

Offer small discounts to close the sale.

Simplify checkout steps and add customer reviews near the cart.

2. Optimize the Shopping Experience
Why it matters: Mobile is the most-used shopping device.
What to do:

Make visuals mobile-friendly and send exclusive deals.

3. Tailor Strategies by Location
Why it matters: Cities like Pune, Mumbai and Hyderabad show high browsing but low purchase activity.
What to do:

Run location-based promotions and free delivery offers.

Increase visibility in other regions through digital marketing and strategic partnerships across other regions.

Collaborate with local influencers.

4. Incorporate personalized shopping experience for customers 
Why it matters: Different age groups shop for different reasons.
What to do:

Show student discounts and trendy items for young users.

Highlight work-life balance products .

Focus on quality and family items.

Use dynamic product suggestions based on age.

## Limitation
Due to restricted access to actual ride-hailing operational data, publicly available reviews, ride price samples, and simulated datasets were used.
Assumptions were validated using comparable services and market research reports.

## Conclusion
The customer journey reveals strong engagement but considerable drop-offs between interest and purchase. By addressing gaps in cart conversion and tailoring experiences by device, age, and location, the e-commerce platform can significantly increase revenue and deepen customer relationships.

## Links
[Power BI Viz](https://app.powerbi.com/view?r=eyJrIjoiMDZkOTUxZDEtNjM2Yi00YjQwLWExNGQtMGNlOGMzYzg0NDUyIiwidCI6IjhkNzA3ZDY0LTgwNWYtNDM3OS1hOWQxLWU1M2VlNjE3YzBkYiJ9)
