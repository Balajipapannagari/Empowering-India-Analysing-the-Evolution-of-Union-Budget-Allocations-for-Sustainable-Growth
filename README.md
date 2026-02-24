# Empowering India: Union Budget Analysis (2021–2024)

## Project Overview
This project analyzes the Indian Union Budget allocations from FY 2021–22 to FY 2023–24 using Tableau. The objective is to study budget trends, ministry-wise distribution, category-wise allocation, and sector-specific funding patterns. The project also includes web integration using Flask.

## Problem Statement
India’s Union Budget plays a major role in shaping economic and development policies. Organizations in Renewable Energy, Electric Vehicles, and Healthcare sectors require structured insights into budget allocations. This project aims to analyze multi-year budget data, identify growth patterns, build interactive dashboards, present insights using storytelling, and integrate visualizations into a web application.

## Dataset Information
Source: Kaggle  
Dataset: Indian Union Budget FY 21-22 till 23-24

Key Columns:
- Category  
- Ministry/Department  
- Scheme  
- Actuals 2021–2022 (Revenue, Capital, Total)  
- Budget Estimates 2022–2023 (Revenue, Capital, Total)  
- Revised Estimates 2022–2023 (Revenue, Capital, Total)  
- Budget Estimates 2023–2024 (Revenue, Capital, Total)

## Tools and Technologies
- Tableau Desktop / Tableau Public  
- Python  
- Flask  
- HTML  
- GitHub

## Data Preparation
- Verified data types  
- Cleaned column formatting  
- Handled missing values  
- Created calculated fields: Total Investment, Growth Percentage, Revised vs Budget Difference (2022–23), Average Budget

## Visualizations
1. Top 5 Schemes (2021–22)  
2. Budget Trend (2021–2024)  
3. Category-wise Allocation (2023–24)  
4. Ministry vs Category Heatmap  
5. Total Investment KPI  
6. Growth Analysis

## Dashboard Features
- Interactive filters  
- Year-wise comparison  
- Responsive layout  
- Structured container design  
- Clear data storytelling

## Tableau Story
1. Introduction  
2. Budget Trends  
3. Top Schemes  
4. Category Analysis  
5. Ministry Analysis  
6. Conclusion

## Web Integration
The Tableau dashboard is embedded into a Flask-based web application.

Project Structure:
union_budget_web/
├── app.py
└── templates/
    └── index.html

## app.py
from flask import Flask, render_template

app = Flask(__name__)

@app.route("/")
def home():
    return render_template("index.html")

if __name__ == "__main__":
    app.run(debug=True) ```
    
**How to Run the Project**

Clone the repository
Install Flask
pip install flask

Run the application
python app.py

Open in browser
http://127.0.0.1:5000

##Live Dashboard

https://public.tableau.com/views/EmpoweringIndiaAnalysingtheEvolutionofUnionBudgetAllocationsforSustainableGrowth_17715150264970/UnionBudgetAnalysisDashboard20212024?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

##Key Insights:
Healthcare and infrastructure sectors received major funding
Budget allocations show steady growth from 2021 to 2024
Renewable energy and EV sectors are increasing in importance
Revised estimates reflect mid-year adjustments

##Business Impact:
Helps startups identify funding opportunities
Supports EV and manufacturing expansion
Guides healthcare investment strategies
Enables data-driven policy analysis

##Project Demonstration
Includes end-to-end video, documentation, dashboard link, and source code.

##Author:
P.Balji
B.Tech – Artificial Intelligence and Data Science

##Future Enhancements:
Real-time data updates
Predictive analytics
Cloud deployment
Advanced forecasting

##Conclusion
This project demonstrates how public financial data can be transformed into meaningful insights using Tableau and web technologies. It supports strategic decision-making and improves understanding of government budget priorities.
