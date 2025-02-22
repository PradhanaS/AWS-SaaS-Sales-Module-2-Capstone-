# AWS SaaS Sales Analysis

This project analyzes AWS SaaS transaction data from 2020 to 2023, focusing on revenue, profit, product performance, and customer behavior.

---

## Table of Contents
- [Introduction](#introduction)
- [Business Problem](#business-problem)
- [Goals](#goals)
- [Dataset Overview](#dataset-overview)
- [Steps](#steps)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [Visualization](#visualization)
- [License](#license)

---

## Introduction

AWS SaaS (Amazon Web Services Software-as-a-Service) is a delivery model enabling businesses to provide software to customers in a service-centric manner. This analysis investigates SaaS sales trends, customer patterns, and product performance to drive growth and optimize operations.

> **Source**: [AWS SaaS](https://aws.amazon.com/saas/)

---

## Business Problem

The company seeks to answer key business questions:
1. How much revenue did AWS SaaS generate annually?
2. What factors contribute to losses?
3. How are products performing in terms of sales and profit?
4. What are the purchasing patterns of retained customers?

---

## Goals

1. Determine revenue trends (2020–2023).
2. Identify revenue loss factors and mitigate them.
3. Assess product performance to highlight strengths and weaknesses.
4. Understand purchasing patterns to enhance customer retention.

---

## Dataset Overview

The dataset contains transaction data from a fictitious SaaS company selling B2B sales and marketing software. Each row represents a product in a transaction, with columns including:

- **Order Details**: `Order ID`, `Order Date`, `Date Key`
- **Customer Information**: `Contact Name`, `Country`, `City`, `Region`, `Industry`, `Customer ID`
- **Transaction Metrics**: `Sales`, `Profit`, `Discount`, `Quantity`
- **Product Information**: `Product`, `License`

### Example Data
| Row ID | Order ID          | Order Date | Contact Name  | Country       | Product           | Sales   | Profit |
|--------|-------------------|------------|---------------|---------------|-------------------|---------|--------|
| 1      | EMEA-2022-152156  | 11/9/2022  | Nathan Bell   | Ireland       | Marketing Suite   | 261.96  | 41.91  |
| 2      | AMER-2022-138688  | 6/13/2022  | Deirdre Bailey| United States | FinanceHub        | 14.62   | 6.87   |

---

## Steps

1. **Data Preparation**: Ensure data consistency (type conversions, cleaning).
2. **Exploratory Data Analysis (EDA)**: Explore trends, losses, and product performance.
3. **Insights and Visualizations**: Use plots and charts for analysis.
4. **Conclusions and Recommendations**: Summarize findings.

---

## Technologies Used

- **Python Libraries**:
  - `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualizations
  - `scipy` and `statsmodels` for statistical tests
- **Tools**: Jupyter Notebook

---

## Visualization

Visualization

For better visualization of the this analysis project are also available on [Tableau](https://public.tableau.com/app/profile/pradhana.satria/viz/AWSSaaSSales_M2-Tableau/AWSSaaSSalesMain).


## How to Use

1. Clone this repository:
   ```bash
   https://github.com/Bodong1107/AWS-SaaS-Sales-Analysis_Capstone-Module-2
