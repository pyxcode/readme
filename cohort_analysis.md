Cohort Analysis - User Retention

Context:
During my last internship (Spring 2025) - as an Engineering Product Manager at SELEGO (selego.co), I have work consequentially on multiple tech projects. 
A key part of my role was performing cohort analysis to identify which features should be optimized, improved, or removed.  

I combined:
Python - data cleaning, cohort/retention and visualisation
SQL - custom queries and dashboards
Metabase - for both native SQL and built-in BI tools

Objective of BasiX:

This project aims to showcase the basic methods I used to compare cohorts and measure their engagement over time.
The analysis focuses on:

1. user retention by cohorts per week 
2. Measuring how many users remain active after 1, 2, 3+ weeks 
3. visualisation of retention drop-offs through a heatmap

Results:

![Retention Heatmap](https://raw.githubusercontent.com/pyxcode/readme/main/images/user_retention.png)


The heatmap shows a strong drop after the first week, stabilizing at 5-10%. The results are consistent accross the weeks
and the pattern is typical for e-commerce from my knowing. However, since only October 2019 data is used we cannot infer purchasing trends with that limited data.

Extensions:
This notebook demonstrates the very basic of retention analysis, in practise we usually explore deeper by :
1. Comparing users who add to card but never buy
2. Differentiating high-value customers from casual browsers
3. Applying ML to identify early signals of disengagement

Dataset:
I have used the Kaggle E-commerce User Behavior dataset from a cosmetic shop https://www.kaggle.com/mkechinov/ecommerce-events-history-in-cosmetics-shop, which logs anonymized user actions like (view, cart, purchase etc). The analysis is limited to October 2019. 

