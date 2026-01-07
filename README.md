# ontario-educational-equity-analysis
Investigating socioeconomic drivers of student achievement in Ontario using Python and OLS regression.
Predictive Analysis of Educational Equity: Socioeconomic Drivers of Student Achievement in Ontario 🇨🇦

📊 Executive Summary
This project investigates how socioeconomic factors influence Grade 6 reading achievement across 321 Ontario municipalities. by integrating 2021 Canada Census data with 2023-2024 provincial school performance datasets, I developed a reproducible data pipeline to identify the primary drivers of educational outcomes. my findings provide a data-driven framework for Ontario policymakers to optimize resource allocation for high-need areas.

🎯 Key Findings
- Strongest Predictors: Socioeconomic disadvantage (low-income rates) and parental education levels are the most significant drivers of student achievement.

- Quantifiable Impact: A 10% increase in low-income households correlates with a 4.2-point decrease in reading scores.

- Non-Factors: Population density has a negligible practical impact on achievement, suggesting that equity issues are systemic rather than geographic.

  🛠️ Technical Stack & Methodologies
Language: Python

Libraries: Pandas (Data Cleaning), Scikit-Learn (Modeling), Matplotlib/Seaborn (Visualization), Statsmodels (OLS Regression)

Models: Ordinary Least Squares (OLS) Multiple Linear Regression.

Data Sources: 2021 Statistics Canada Census & 2023-24 EQAO Preliminary results.

📂 Project Structure
data/: Contains raw and processed CSV files (Census & EQAO data).

notebooks/: Jupyter Notebook with full step-by-step EDA and modeling.

visualizations/: Key charts exported from the analysis (Regression plots, Histograms).

reports/: The final summary document detailing policy recommendations.


🚀 How to Reproduce
1. Clone the repo: git clone https://github.com/yourusername/ontario-education-equity.git

2. Install dependencies: pip install pandas scikit-learn seaborn statsmodels

3. Run the analysis: Open notebooks/Ontario_Achievement_Analysis.ipynb in Jupyter.
