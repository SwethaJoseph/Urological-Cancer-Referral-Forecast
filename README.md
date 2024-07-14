# Urological-Cancer-Referral-Forecast-Model
This project addresses the backlog in urological cancer treatment referrals within NHS Scotland, exacerbated by the COVID-19 pandemic. Utilizing business intelligence techniques, the project forecasts referral treatment rates and evaluates various health boards to improve NHS management. Key methods include time series forecasting, linear programming, and data visualization.

# Forecasting and Evaluation
* Developed case studies to understand influencing factors.
* Utilized various operational indicators and external data for performance enhancement.
* Employed Excel for exploratory and causal data analysis.
* Ensured model accuracy through rigorous evaluation.

# Data Access, Cleaning, and Preparation
Data for this project was sourced from the 'Scottish Health and Social Care Open Data' platform. The dataset includes 441 rows and 7 columns, covering urological cancer referrals from 2012 to 2022 across 11 health boards. Data cleaning involved filtering, sorting, and handling missing values.

# Time Series Forecasting
Forecasting analysis was performed for four health boards: NHS Highland, NHS Lothian, NHS Fife, and NHS Lanarkshire.

## NHS Highland
* Identified seasonality with trend as the best forecasting method (MSE=156.8616).
* Excluding 2020 and 2021 improved MSE to 76.3941.
## NHS Lothian
* Seasonality with trend identified as the best method (MSE=41.5750).
* Minimal change when excluding 2020 and 2021 (MSE=42.6439).
## NHS Fife
* Seasonality with trend identified as the best method (MSE=74.0528).
* Minimal change when excluding 2020 and 2021 (MSE=63.9749).
## NHS Lanarkshire
* Exponential smoothing with damping factor 0.5 identified as the best method (MSE=43.4252).
* Seasonality with trend was the best method when excluding 2020 and 2021 (MSE=23.2784).

# Linear Programming/Optimization
Linear programming was used to optimize staff allocation for bed management in Tayside Health Board, aiming to minimize the number of staff required per shift.

# Tableau Prep and Dashboard
Data was prepared using Tableau Prep Builder for analysis and visualization. The dashboard includes:

* Time series charts
* Geographic maps
* Treemaps
* Highlight tables

# Ethical Issues in Business Intelligence
Addressed privacy, ethical, and legal concerns in implementing business intelligence in healthcare, emphasizing patient data protection and ethical decision-making.

# Conclusion
The analysis highlights the consistent decrease in the percentage of urological cancer referrals treated over the years, with minimal impact from excluding 2020 and 2021. Recommendations include improving data collection for better forecasting models.

