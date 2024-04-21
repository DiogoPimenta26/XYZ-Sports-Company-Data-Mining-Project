# XYZ Sports Company Customer Segmentation Project

## Introduction

XYZ Sports Company is a well-established fitness facility committed to gaining insight into its user base to optimize marketing efforts, personalize services, and enhance overall customer satisfaction. Customer segmentation is a vital strategy to achieve these goals, involving dividing the customer base into distinct groups based on various criteria. This project focuses on developing customer segmentation using RFM analysis and the K-means clustering algorithm.

## Exploratory Data Analysis (EDA)

The dataset provided by XYZ Sports Company contains 14942 records with 30 features associated with customer profiles. Initial data preprocessing involved handling missing values, addressing data incoherencies, removing duplicates, and performing feature engineering to extract relevant insights.

### Data Incoherence

Several inconsistencies were addressed during preprocessing, including individuals under 16 years old reporting income, zero lifetime values, inconsistent references, and enrollment start/finish dates. These discrepancies were rectified to ensure data integrity.

### Handling Missing Values

Missing values were treated across different variables such as income, activities, number of frequencies, and references, employing various strategies tailored to each variable to preserve the accuracy of the analysis.

## Customer Segmentation

### RFM Analysis

RFM analysis segments customers based on recency, frequency, and monetary value of their transactions. By assigning scores to each variable and deriving an overall RFM score, customers were categorized into "High Value," "Medium Value," and "Low Value" groups. Insights from this analysis revealed historical targeting strategies and demographic trends within customer segments.

### Clustering Analysis

#### Demographic Perspective

Clustering based on demographic characteristics such as age, gender, and income revealed distinct customer groups. The elbow method was utilized to determine the optimal number of clusters, resulting in three distinct segments with unique characteristics.

#### Purchase Behavior Perspective

Clustering customers based on RFM scores provided insights into similar purchasing behaviors. Through K-means clustering and evaluation using the elbow method and silhouette score, three distinct clusters were identified, each representing customers with varying levels of engagement and spending behavior.

#### Value-Based Perspective

Integrating RFM scores with demographic characteristics, clustering identified customers based on their potential profitability to the business. Insights from these clusters led to recommendations for targeted marketing strategies and service offerings tailored to different customer segments.

## Conclusion

By merging insights from demographic analysis and RFM segmentation, recommendations were provided for XYZ Sports Company's strategic plan. These recommendations include optimizing activity offerings, implementing tailored subscription plans, and focusing on customer segments with the highest potential for profitability. This comprehensive approach ensures a targeted and effective strategy for sustained growth and customer retention in the fitness industry.
