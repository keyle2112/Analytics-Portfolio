# Keynes' Data Analytics Portfolio

## Table of Contents

* [About](#about)
* [Skills](#skills)
* [Projects](#projects)
  * [NBA Salary Determinants](#nba-salary-determinants)
  * [Email Spam Classification System](#email-spam-classification-system)
  * [Cook County Housing Price Prediction](#cook-county-housing-price-prediction)
  * [Minimum Wage Policy & Foreign Investment](#minimum-wage-policy--foreign-investment)
  * [Climate Change & Civil Conflict](#climate-change--civil-conflict)
  * [Economic Impact Analysis: Mariel Boatlift](#economic-impact-analysis-mariel-boatlift)
  * [Regional GDP Analysis](#regional-gdp-analysis)
  * [Econometric Analysis of MLB Salary Disparities](#econometric-analysis-of-mlb-salary-disparities)
  * [Classifying Movies (K-Nearest Neighbors)](#classifying-movies-k-nearest-neighbors)
  * [Climate Change: Temperature & Precipitation Analysis](#climate-change-temperature--precipitation-analysis)
  * [Predicting Baseball Wins](#predicting-baseball-wins)
  * [World Population & Poverty Analysis](#world-population--poverty-analysis)
* [Education](#education)
* [Contact & Links](#contact--links)

## About 
I'm Keynes (pronounced Key-eans), a UC Berkeley graduate in Economics with minors in Data Science and Journalism, focused on using data to understand human behavior and communicate insights through clear, structured storytelling. My work spans machine learning, econometric analysis, and data-driven projects, with an emphasis on turning analysis into actionable insight rather than just prediction.

Alongside my academic work, I've gained experience in live and culture-driven environments, including supporting production for the Super Bowl LX Halftime Show and contributing to music and entertainment initiatives centered on audience engagement. These experiences have shaped how I approach analytics, viewing it not just as numbers but as part of larger systems where timing, coordination, and decision-making matter. I'm particularly interested in applying data analysis within the music and entertainment industry, exploring how audience insights, trends, and behavior can inform strategy and creative direction.

This repository highlights my work across Python and R projects in econometrics, machine learning, and audience research, with a growing focus on music and entertainment analytics.

For a broader view of my work across culture, live production, and creative projects, visit my [personal website](https://keynesle.com).

## Skills 
* Languages: Python (pandas, scikit-learn, NumPy, matplotlib, geopandas, statsmodels), R (tidyverse)
* Methods: Econometric modeling, causal inference, panel data and fixed effects, regression analysis, hypothesis testing, machine learning, feature engineering, fairness analysis, geospatial analysis
* Currently learning: SQL, Tableau, music and entertainment data platforms

## Projects 

### NBA Salary Determinants

September 2025 - December 2025 <br>

[PDF](projects/Labor%20Economics%20NBA%20Salary%20Determinants%20Project.pdf) <br>

Description: Applied econometric regression techniques to analyze salary determinants for 269 NBA players from the 1994-95 season. Used log-transformed salary data to address skewness and incorporated performance metrics, experience, position, and race as explanatory variables. Evaluated how on-court productivity translated into wages using both simple and multivariate OLS models. <br> 

Skills: Econometric modeling, OLS regression, data transformation, statistical analysis, hypothesis testing <br>

Technology: R, tidyverse, regression modeling, data visualization <br>

Results: Scoring and experience were the strongest predictors of salary, while race and position lost statistical significance once performance was controlled for. Observable productivity explains much of wage variation, though unobserved factors may still influence compensation. <br>

Impact: Shows how econometric controls separate real drivers of talent compensation from surface-level correlations, an approach directly applicable to evaluating pay structures in sports and entertainment. <br> 

### Email Spam Classification System

November 2025 - December 2025 <br>

Description: Built a supervised machine learning pipeline for email classification using a dataset of over 5,000 messages. The workflow included text preprocessing, feature engineering, model training, and evaluation. Key features were derived using regex-based pattern extraction, word frequency metrics, and text statistics including email length, punctuation counts, and capitalization patterns. <br>

Skills: Feature engineering, text preprocessing, classification modeling, cross-validation, model evaluation (precision-recall, ROC analysis) <br>

Technology: Python, pandas, scikit-learn, NumPy, regex <br> 

Results: The model achieved over 90% accuracy, optimized through multiple iterations of hyperparameter tuning. Precision-recall analysis was used to balance spam detection against the risk of blocking legitimate mail. <br> 

Impact: Illustrates why headline accuracy is an insufficient success metric when the two error types carry unequal real-world cost. <br> 

### Cook County Housing Price Prediction

October 2025 <br>

Description: Built a machine learning model to predict housing prices using 500k+ property records, applying feature engineering techniques including text mining, log transformations, and one-hot encoding. Developed a full pipeline covering preprocessing, training, and evaluation in scikit-learn, then incorporated fairness analysis to assess model bias across socioeconomic groups. <br>

Skills: Machine learning, feature engineering, model evaluation, data cleaning, fairness analysis <br>

Technology: Python, pandas, scikit-learn, NumPy, matplotlib <br>

Results: Achieved strong predictive performance through K-fold cross-validation and metric comparison (RMSE vs. MAPE). Identified a 15-20% overestimation bias in lower-priced neighborhoods that aggregate accuracy alone concealed. <br>

Impact: Demonstrates that a model can perform well overall while failing systematically for a specific group, and that comparing metrics is what surfaces the difference. <br>

### Minimum Wage Policy & Foreign Investment

January 2025 - May 2025 <br>

[PDF](projects/Minimum%20Wage%20Policy%20%26%20Foreign%20Investment.pdf) <br>

Description: Conducted panel econometric analysis examining how minimum wage policies and labor availability influence FDI inflows in Southeast Asia. Integrated datasets from ILOSTAT and the World Bank, controlling for macroeconomic variables, and applied fixed effects models to isolate labor policy impacts. <br> 

Skills: Econometrics, panel data analysis, data cleaning, policy analysis, regression modeling <br>

Technology: R, tidyverse, regression modeling <br>

Results: Labor availability proved a stronger driver of FDI than low wages. Rising minimum wages did not significantly deter investment when supported by strong labor participation. <br> 

Impact: Challenges the assumption that low wages are the primary competitive lever for emerging economies attracting foreign investment. <br> 

### Climate Change & Civil Conflict

April 2025 - May 2025 <br>

[PDF](projects/Econ%20148%20Climate%20Change%20%26%20Civil%20Conflict.pdf) <br>

Description: Constructed a panel dataset integrating climate, agricultural, and conflict data to analyze how environmental shocks influence civil conflict risk. Applied fixed effects regression to isolate temperature and precipitation effects while controlling for country and time factors, replicating a foundational climate-conflict economics study. <br> 

Skills: Panel data analysis, fixed effects modeling, data merging, econometrics, statistical interpretation <br>

Technology: Python, R, pandas, statsmodels <br> 

Results: Found significant relationships between climate anomalies and increased conflict risk in specific contexts, aligning with established academic findings. <br> 

Impact: Building the dataset independently makes the replication a real test of whether the published result holds, not a restatement of it. <br>

### Economic Impact Analysis: Mariel Boatlift

February 2025 - March 2025 <br>

[Project Files](projects/Econ%20148%20Economic%20Impact%20Analysis.zip) <br>

Description: Replicated a Nobel Prize-winning natural experiment analyzing the labor market impact of immigration using 26,000+ survey records. Conducted comparative trend analysis across metropolitan areas and applied OLS regression with engineered variables, focused on identifying causal effects from labor supply shocks. <br>

Skills: Causal inference, OLS regression, data analysis, feature engineering, data visualization <br>

Technology: Python, pandas, NumPy, matplotlib <br>

Results: Found no statistically significant negative impact on wages despite a 7% labor force increase, supporting the conclusions of the original study. <br> 

Impact: A worked example of using a natural experiment to establish causation where correlation would mislead. <br>

### Regional GDP Analysis

February 2025 <br>

[Project Files](projects/Econ%20148%20Regional%20GDP%20Analysis.zip) <br>

Description: Analyzed U.S. county-level GDP data from 2001 to 2021 to evaluate regional economic trends and recovery patterns. Processed and reshaped large datasets, expanding 47k+ records into 718k rows for analysis, and developed geospatial visualizations to identify growth disparities across regions. <br> 

Skills: Data cleaning, time-series analysis, data transformation, geospatial analysis, data visualization <br>

Technology: Python, pandas, matplotlib, geopandas <br>

Results: Identified stronger post-2008 recovery in coastal regions than in the Midwest, with growth concentrated in urban and tech-driven areas. <br> 

Impact: Shows how restructuring a dataset into the right shape is often the step that makes a pattern visible at all. <br> 

### Econometric Analysis of MLB Salary Disparities

November 2024 - December 2024 <br>

[PDF](projects/Econometrics%20Analysis%20of%20MLB%20Salary%20Disparities.pdf) <br>

Description: Analyzed MLB salary determinants using regression models to evaluate the impact of race, city demographics, and performance metrics. Applied econometric techniques to control for confounding variables and explored potential bias and omitted variable effects. <br>

Skills: Econometrics, regression analysis, bias analysis, statistical modeling, data interpretation <br> 

Technology: R, regression modeling <br> 

Results: Performance metrics were the strongest predictors of salary, with limited influence from demographic variables. Identified potential omitted variable bias in the specification. <br>

Impact: Naming what the model cannot observe matters as much as reporting what it found. <br> 

### Classifying Movies (K-Nearest Neighbors)

April 2024 <br>

[Project Files](projects/Data%208%20Project%203%20Classification.zip) <br>

Description: Built a k-nearest neighbors classifier to predict movie genres from keyword frequency in scripts. Engineered custom features and applied Euclidean distance for classification, evaluating performance across different feature sets.

Skills: Machine learning, feature engineering, classification, data analysis, model evaluation

Technology: Python, scikit-learn, pandas

Results: Improved classification accuracy through feature selection and distance tuning, identifying the word associations driving genre prediction.

Impact: An early look at classifying entertainment content by its text, the same problem shape as tagging or categorizing music by lyrical and metadata features.

### Climate Change: Temperature & Precipitation Analysis

March 2024 - April 2024 <br>

[Project Files](projects/Data%208%20Project%202%20Climate%20Change%20Temperatures%20and%20Precipitation.zip) <br>

Description: Analyzed temperature and precipitation trends across 210 U.S. cities, applying hypothesis testing and confidence intervals to evaluate change over time, with A/B testing on drought conditions.

Skills: Statistical analysis, hypothesis testing, data visualization, inference

Technology: Python, pandas, matplotlib 

Results: Identified statistically significant warming trends across cities and measurable differences in precipitation during drought periods.

Impact: An applied exercise in separating a real trend from year-to-year noise using confidence intervals, rather than reading a direction off a chart.

### Predicting Baseball Wins: Least Squares Regression

March 2024 - April 2024 <br>

[PDF](projects/Predicting%20Baseball%20Wins%20Project.pdf) <br>

Description: Developed least squares regression models to predict MLB team wins from performance metrics such as runs scored and allowed, applying simple and multiple regression with transformations to improve model fit.

Skills: Regression analysis, statistical modeling, model evaluation, sports analytics

Technology: R 

Results: Found run differential to be strongly related to team success, with accuracy improving through added variables and transformations.

Impact: Run differential outperforms raw scoring totals as a predictor, a straightforward case of the constructed variable carrying more signal than the one that comes in the dataset.

### World Population & Poverty Analysis

February 2024 <br>

[Project Files](projects/Data%208%20Project%201%20World%20Population%20and%20Poverty.zip) <br>

Description: Analyzed global population and poverty trends across 145 countries using statistical visualization techniques, exploring relationships between life expectancy, fertility, and economic conditions.

Skills: Data visualization, statistical analysis, exploratory data analysis

Technology: Python, pandas, matplotlib

Results: Identified strong relationships between development indicators and population dynamics, with clear patterns in global poverty reduction.

Impact: Early practice in using visualization to find which relationships across 145 countries were worth modeling formally, before committing to a specification.

## Education
University of California, Berkeley, College of Letters and Science - Bachelor of Arts, Economics, Minors in Data Science and Journalism <br>
(January 2024 - December 2025) 

Pasadena City College - Associate of Arts, Business, Economics UC Transfer Pathway <br>
(August 2021 - May 2023)


## Contact & Links 
* **Email:** [lekeynes1@gmail.com](mailto:lekeynes1@gmail.com)
* **LinkedIn:** [linkedin.com/in/keynesle/](https://www.linkedin.com/in/keynesle/)
* **Website:** [keynesle.com](https://keynesle.com/)
