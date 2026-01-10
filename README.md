📊 ontario-educational-equity-analysis
Investigating socioeconomic drivers of student achievement in Ontario using Python and OLS regression.

📊 Executive Summary
This project investigates how socioeconomic factors influence Grade 6 reading achievement across 321 Ontario municipalities. By integrating 2021 Canada Census data with 2023-2024 provincial school performance datasets (EQAO), I developed a reproducible data pipeline to identify the primary drivers of educational outcomes.

Building on the initial exploratory analysis, this second phase introduces predictive modeling and geospatial intelligence to quantify systemic achievement gaps. My findings provide a data-driven framework for Ontario policymakers to optimize resource allocation for high-need areas.

🎯 Key Findings
Strongest Predictors: Socioeconomic disadvantage (low-income rates) and parental education levels (populations with no degree) are the most significant drivers of student success.

Quantifiable Impact: OLS modeling confirms that a 10% increase in low-income households correlates with a 4.2-point decrease in reading achievement scores.

Systemic Consistency: Distribution of Grade 6 Reading achievement is approximately normal with a mean of 83.2 across 6,500+ records.

Non-Factors: Population density has a negligible practical impact on achievement, suggesting that equity issues are systemic rather than geographic.

🛠️ Technical Stack & Methodologies
Language: Python 3.9

Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Statsmodels, and Folium.

Advanced Features:

Robust Error Handling: Integrated try-except blocks and assertions to ensure pipeline resilience.

Data Validation: Custom functions to verify that all scores fall within valid ranges (0-100).

Models: Ordinary Least Squares (OLS) Multiple Linear Regression.

Data Sources: 2021 Statistics Canada Census & 2023-24 EQAO Preliminary results.

📂 Project Structure
data/: Contains raw and processed CSV files (Census & EQAO data).

processed_analysis_data.csv: Cleaned dataset containing merged Census and EQAO data.

EDA_AND_PREDICTIVE.ipynb: Full Jupyter Notebook containing EDA, Predictive Modeling, and technical documentation.

ontario_reading_scores_map.html: Interactive Folium map visualizing performance trends by municipality.

requirements.txt: Environment configuration for reproducibility.

notebooks/: Jupyter Notebook with full step-by-step EDA and modeling.

visualizations/: Key charts exported from the analysis (Regression plots, Histograms).

reports/: The final summary document detailing policy recommendations.


🚀 How to Reproduce
1. Clone the repo: git clone https://github.com/yourusername/ontario-education-equity.git

2. Install dependencies: pip install pandas scikit-learn seaborn statsmodels

3. Run the analysis: Open notebooks/Ontario_Achievement_Analysis.ipynb in Jupyter.
