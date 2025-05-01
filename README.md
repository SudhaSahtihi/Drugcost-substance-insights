# Drugcost-substance-insights
Analysis of FDA-regulated pharmaceutical metadata to uncover risk patterns in controlled substances.

Visualizations at : ![Dashboard]https://public.tableau.com/app/profile/sudha.sahithi.murikipudi/viz/Drugcostsubstanceabuseriskinsights/Dashboard1

# Project Overview:
This project investigates the landscape of DEA-scheduled drugs using real-world pharmaceutical data. By analyzing strength, pharmacological classifications, and marketing longevity, it offers insights into the accessibility and complexity of high-risk substances.

# Dataset:

Source: Pharma_data.csv

Contents: FDA metadata on drug names, strength, route, marketing dates, pharmacological class, and DEA schedule (CII–CV)

# Key KPIs & Insights

Percentage with Multiple Classifications - 93.0%	- Most DEA-controlled drugs act via multiple pharmacological pathways, increasing interaction and monitoring complexity

Marketed over 10 Years - 83.3%	- The majority of high-risk drugs have remained accessible for over a decade

Avg. Strength -	CIII (66.9), CV (62.3), CII (44.6), CIV (32.7)	- Potency is not limited to the most tightly regulated schedules

Total DEA-Scheduled Drugs	- 1,798	- Scope of analysis included all drugs marked CII–CV in the dataset

# Tools & Techniques Used:

Python (Pandas): Data cleaning, feature engineering, regex parsing

Tableau: KPI design, visual storytelling, interactivity

Excel: Final cleaned dataset for Tableau upload

# Business Impact:

This project simulates how analysts in pharma, healthcare compliance, or government agencies can:

Identify long-standing risk compounds in circulation

Flag high-potency drugs outside of Schedule II

Monitor pharmacological complexity in the supply chain
