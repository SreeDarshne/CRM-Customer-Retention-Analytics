# CRM Customer Retention Analytics

## Overview

This repository contains a Customer Relationship Management (CRM) analytics project focused on:

**“Analyzing Modern CRM Practices and Their Impact on Customer Retention: A Case Study of Ford Motor Company.”** :contentReference[oaicite:0]{index=0}

The project combines a business-oriented CRM case study with a quantitative analytics workflow using a **synthetic CRM dataset of 120,000 customer records**. The analysis focuses on customer churn, segmentation, customer lifetime value, marketing campaign performance, and predictive modeling. :contentReference[oaicite:1]{index=1}

---

## Team

- Sujana S
- Daphni Michelle B
- Sree Darshne J
- Haripriya T N

Course: Customer Relationship Management  
Program: Integrated M.Tech CSE - Business Analytics  
VIT Chennai

---

## Project Objectives

The project aims to:

- Understand modern CRM practices
- Analyze customer retention and loyalty
- Identify factors influencing customer churn
- Segment customers based on behavioral and demographic attributes
- Estimate customer lifetime patterns using survival analysis
- Compare marketing campaign performance
- Build machine learning models for churn prediction
- Translate analytical findings into CRM strategy recommendations

---

## CRM Concepts Covered

The academic report discusses several core CRM concepts:

- Customer Retention
- Customer Loyalty
- Customer Equity
- Relationship Marketing
- Customer Lifetime Value (CLV)
- Omni-channel Engagement
- Personalized Customer Experience
- Predictive Analytics
- Customer-Centric Strategy

The report emphasizes the role of CRM in supporting long-term customer relationships rather than only short-term transactions. :contentReference[oaicite:2]{index=2}

---

## Ford CRM Case Study

The project examines Ford Motor Company as a CRM case study.

The report discusses Ford's use of:

- FordPass ecosystem
- Connected vehicle technologies
- Customer data analytics
- Personalized communication
- Dealer network integration
- Customer feedback systems
- Predictive analytics
- Digital engagement
- Loyalty programs
- Omni-channel customer interaction

Ford's CRM strategy is presented as part of its broader shift toward connected, digital, and customer-centric mobility services. :contentReference[oaicite:3]{index=3}

---

# Dataset

The quantitative part of the project uses a:

```text
Synthetic CRM Dataset
```

with:

```text
120,000 customer records
```

The dataset includes customer-related variables covering areas such as:

- Age
- Income
- Purchase behavior
- Purchase frequency
- Average order value
- Loyalty indicators
- Engagement metrics
- Customer location
- Marketing campaign exposure
- Churn status

The presentation reports an overall churn rate of approximately:

```text
30%
```

and explores demographic and behavioral relationships within the synthetic data. :contentReference[oaicite:4]{index=4}

---

# Analytical Workflow

The project follows a multi-stage analytics pipeline:

```text
Synthetic CRM Dataset
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Churn Prediction
        ↓
Customer Segmentation
        ↓
Survival Analysis
        ↓
Marketing Campaign Analysis
        ↓
Random Forest / Decision Tree Analysis
        ↓
Business Interpretation
```

---

# Exploratory Data Analysis

EDA is used to understand customer distributions and relationships between variables.

The analysis includes:

- Customer demographic distributions
- Churn distribution
- Purchase patterns
- Income-related behavior
- Correlation analysis
- Engagement analysis
- Customer location analysis

The project presentation reports that higher purchase frequency is associated with lower churn probability and highlights relationships between income, purchase behavior, and loyalty. :contentReference[oaicite:5]{index=5}

---

# Churn Prediction

## Logistic Regression

Logistic Regression is used as one of the primary models for customer churn prediction.

The presentation reports an accuracy of approximately:

```text
68%
```

for the Logistic Regression churn model. :contentReference[oaicite:6]{index=6}

Important churn-related factors identified in the project include:

- Purchase frequency
- Income level
- Loyalty score
- Customer engagement
- Age segment

The analysis indicates that frequent customer interaction is associated with lower churn risk. :contentReference[oaicite:7]{index=7}

---

# Customer Segmentation

Customer segmentation is performed using:

```text
K-Means Clustering
```

The objective is to identify groups of customers with similar:

- Spending patterns
- Engagement behavior
- Demographic characteristics
- Loyalty characteristics

The analysis supports targeted CRM strategies by separating customers into distinct behavioral segments.

---

# Customer Lifetime Analysis

The project uses survival analysis to study customer retention over time.

## Kaplan-Meier Analysis

Kaplan-Meier survival curves are used to examine how customer retention differs between groups.

The analysis includes survival comparisons based on:

- Customer groups
- Demographic attributes
- Location

The final report includes a survival curve by customer location as part of the retention analysis. :contentReference[oaicite:8]{index=8}

---

# Marketing Campaign Analysis

The project evaluates differences in customer purchase behavior across marketing campaigns.

The report compares:

```text
Purchase Amount by Marketing Campaign
```

and notes that campaign groups show slight variations in average purchase value. :contentReference[oaicite:9]{index=9}

This analysis is used to support recommendations for:

- Targeted marketing
- Campaign personalization
- Customer-specific promotions
- CRM campaign optimization

---

# Statistical Analysis

The project also applies statistical testing to compare campaign or customer groups.

Techniques include:

```text
ANOVA
```

which is used to assess whether differences between group means are statistically meaningful.

---

# Random Forest Analysis

Random Forest is used for churn prediction and feature importance analysis.

The project reports that important churn predictors include:

- Income
- Purchase amount
- Engagement-related variables

The feature importance analysis helps identify which attributes contribute most strongly to churn prediction. :contentReference[oaicite:10]{index=10}

---

# Decision Tree Analysis

A Decision Tree is also used to analyze churn behavior.

According to the final report, the tree structure highlights:

```text
Purchase Frequency
```

as an important factor influencing customer churn. :contentReference[oaicite:11]{index=11}

Decision trees also make the model easier to interpret because they provide a visual representation of decision rules.

---

# Model Comparison

The project compares multiple approaches to churn analysis:

| Technique | Purpose |
|---|---|
| Logistic Regression | Churn prediction and coefficient interpretation |
| K-Means | Customer segmentation |
| Kaplan-Meier | Customer retention and survival analysis |
| ANOVA | Marketing campaign comparison |
| Random Forest | Churn prediction and feature importance |
| Decision Tree | Interpretable churn classification |

The goal is not only prediction accuracy, but also obtaining interpretable customer insights that can support CRM decision-making.

---

# Business Insights

The project identifies several practical CRM insights.

### Purchase Frequency

Frequent buyers show stronger customer retention and lower churn risk.

### Income

Income is associated with differences in purchase behavior and churn characteristics.

### Loyalty

Higher loyalty scores are associated with stronger long-term customer engagement.

### Engagement

Low-engagement customers represent an important target group for proactive CRM intervention.

### Marketing

Marketing campaigns show differences in purchase values, suggesting opportunities for better campaign personalization.

### Retention

Survival analysis helps identify how long different customer groups remain active.

---

# Technologies Used

## Programming

- Python
- Jupyter Notebook

## Data Analysis

- Pandas
- NumPy

## Machine Learning

- Scikit-learn
- Logistic Regression
- K-Means Clustering
- Random Forest
- Decision Tree

## Statistical Analysis

- ANOVA
- Survival Analysis
- Kaplan-Meier Estimator

## Survival Analysis

- Lifelines

## Visualization

- Matplotlib
- Seaborn

---

# Outputs

The `Outputs/` folder contains the visual results generated during the analysis.

These include:

- Customer distributions
- Churn distribution plots
- Correlation heatmap
- Logistic Regression outputs
- Customer segmentation visualizations
- K-Means clustering plots
- Survival curves
- Campaign comparison plots
- Feature importance visualizations
- Random Forest confusion matrix
- Decision Tree results
- Additional CRM analytics figures

---

# Repository Structure

```text
CRM-Customer-Retention-Analytics/
│
├── CRM_Final.ipynb
│   └── Main CRM analytics and machine learning notebook
│
├── CRM_report .docx
│   └── CRM project report
│
├── FORD_CRM_FINAL.pdf
│   └── Final formatted project report
│
├── Applications of CRM Techniques at Ford Motor Company.pptx
│   └── Final project presentation
│
├── Introduction-to-CRM-at-Ford.pptx
│   └── Supporting CRM presentation
│
├── Outputs/
│   └── Generated analysis plots and model outputs
│
├── .gitignore
│
└── README.md
```

---

# Key Findings

The project reports several key observations:

- The synthetic dataset contains **120,000 customer records**. :contentReference[oaicite:12]{index=12}
- Overall churn is approximately **30%** in the analyzed synthetic dataset. :contentReference[oaicite:13]{index=13}
- Logistic Regression achieved approximately **68% accuracy** for churn prediction. :contentReference[oaicite:14]{index=14}
- Purchase frequency is identified as an important churn-related factor.
- Income, purchase amount, and engagement-related features appear prominently in feature importance analysis. :contentReference[oaicite:15]{index=15}
- Survival analysis is used to compare retention behavior across customer groups and locations.
- Marketing campaigns show differences in purchase amounts, supporting the need for targeted CRM strategies. :contentReference[oaicite:16]{index=16}
- The Decision Tree analysis highlights purchase frequency as an important factor in churn behavior. :contentReference[oaicite:17]{index=17}

---

# Limitations

## Synthetic Dataset

The quantitative analysis uses synthetic CRM data rather than confidential Ford customer records.

Therefore, the machine learning results should be interpreted as an academic simulation rather than as measured performance on Ford's internal customer database.

---

## Churn Prediction Performance

The reported Logistic Regression accuracy is approximately 68%, indicating that customer churn remains a difficult prediction problem in this synthetic setup.

The project therefore emphasizes both predictive modeling and interpretability rather than claiming near-perfect churn prediction.

---

## Company Case Study vs Dataset

The Ford discussion is used as the CRM business context.

The synthetic analytics dataset is not presented as actual proprietary Ford customer data.

---

## Customer Behavior Complexity

Customer churn may depend on factors that are not represented in the synthetic dataset, including:

- Competitor activity
- Customer service interactions
- Product quality
- Vehicle ownership history
- Macroeconomic conditions
- Brand perception
- Regional differences

---

# Future Improvements

Possible extensions include:

- XGBoost or LightGBM churn modeling
- Hyperparameter optimization
- SMOTE for class imbalance
- ROC-AUC comparison across classifiers
- Customer Lifetime Value regression
- RFM segmentation
- Churn probability scoring
- Personalized campaign recommendation
- Time-series customer engagement analysis
- SHAP-based model explainability
- Customer journey modeling
- Real-world anonymized CRM datasets
- Dashboard development using Power BI or Tableau
- Streamlit-based CRM analytics interface

---

# Academic Purpose

This project was developed for academic study of:

```text
Customer Relationship Management
+
Business Analytics
+
Machine Learning
```

It demonstrates how CRM concepts can be combined with data analytics to support customer retention, segmentation, marketing analysis, and data-driven decision-making.

---

# Disclaimer

This repository is an academic project.

The quantitative analysis is based on a **synthetic CRM dataset** and should not be interpreted as an analysis of Ford Motor Company's proprietary customer records.

Any discussion of Ford Motor Company is used as part of the academic CRM case study and business context.
