# Real-Estate-Price-Analysis
Data-driven analysis of housing prices to support decision-making.
# Real Estate Price Analysis & Decision Support

## Problem
Real estate stakeholders need to understand what drives property prices in order to make
better pricing, valuation, and investment decisions.  
This project analyzes housing data to identify the most influential price drivers and
translate analytical findings into clear, decision-ready insights.

---

## Data Overview
The dataset contains property-level information such as:
- Location
- Property size (area)
- Number of rooms
- Additional property characteristics

The data was cleaned and prepared to ensure accuracy and consistency prior to analysis.

---

## Analytical Approach
The project follows a structured, consulting-style approach:

1. Exploratory data analysis to understand distributions and relationships  
2. Feature analysis to identify the strongest drivers of house prices  
3. Predictive modeling to support price estimation and insight generation  
4. Visualization of findings using Power BI dashboards for stakeholder communication  

The focus is on **analysis, interpretation, and decision support**, rather than model
complexity or optimization.

---

## Key Insights
- Location and property size are the strongest determinants of house prices  
- Certain features exhibit diminishing returns beyond specific thresholds  
- Some commonly assumed factors have limited impact on pricing  

These insights help stakeholders focus on what truly matters when valuing properties.

---

## Power BI Dashboard Preview
The dashboards below present the analysis results in a clear, stakeholder-friendly format.

### Housing Price Drivers
![Housing Price Drivers](images/price_drivers_dashboard.png)

### Market Trends & Comparisons
![Market Trends](images/market_trends_dashboard.png)

*(The Power BI `.pbix` file used to create these dashboards is included in the `/powerbi`
folder for reference.)*

---

## Business Implications
- Supports data-driven pricing and valuation decisions  
- Helps investors and planners prioritize high-impact property features  
- Reduces reliance on intuition by grounding decisions in analytical evidence  
- Enables clearer communication of insights to non-technical stakeholders  

---

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Power BI  

---

## Repository Structure
Real-Estate-Price-Analysis/
│
├── notebooks/
│ └── housing_price_analysis.ipynb
│
├── data/
│ └── housing_data_sample.csv
│
├── images/
│ ├── price_drivers_dashboard.png
│ └── market_trends_dashboard.png
│
├── powerbi/
│ └── HousePriceDashboard.pbix
│
└── README.md


## Next Steps
- Incorporate additional regional or market data  
- Compare pricing drivers across different locations  
- Extend the dashboards with scenario-based analysis  
