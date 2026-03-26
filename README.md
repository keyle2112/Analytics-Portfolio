# Analytics-Portfolio

## About 
I’m Keynes (pronounced Key-eans), a UC Berkeley graduate in Economics with minors in Data Science and Journalism, focused on using data to understand human behavior and communicate insights through clear, structured storytelling. My work spans machine learning, econometric analysis, and data-driven projects, with an emphasis on turning analysis into actionable insight rather than just prediction.

Alongside my academic work, I’ve gained experience in live and culture-driven environments, including supporting production for the Super Bowl LX Halftime Show and contributing to music and entertainment initiatives centered on audience engagement. These experiences have shaped how I approach analytics, viewing it not just as numbers but as part of larger systems where timing, coordination, and decision-making matter. I’m particularly interested in applying data analysis within the music and entertainment industry, exploring how audience insights, trends, and behavior can inform strategy and creative direction. 

This repository highlights my work across Python, SQL, and data analysis projects, with a growing focus on music and entertainment applications.

## Table of Contents
* About
* Projects
  * Python
     * Email Spam Classification System
     * Cook Couunty Housing Price Prediction
     * Climate Change & Civil Conflict
     * Economic Impact Analysis: Mariel Boatlift
     * Reguional GDP Analysis
     * Ants: Data-Driven Tower Defense Game
     * CATS: Typing Autocorrect System
     * Classifying Movies (K-Nearest Neighbors)
     * Climate Change; Temperatures and Precipitation
     * World Population and Poverty 
  * R
     * NBA Salary
     * Climate Change & Civil Conflict
     * Minimum Wage Policy & Foreign Investment
     * Econometrics Analysis of MLB Salary Disparities
     * Predicting Baseball Wins 
  * SQL
  * Excel/Google Sheets
  * Tableau
  * Power BI
  * APIs
* Education
*  Contact

## Projects 
*insert summary sentence when all projects are added* <br>

### Email Spam Classification System 

Code: <br> 

Goal: To build a text-based classification model that distinguishes spam from legitimate emails while minimizing false positives. <br>

Description: This project involved constructing a supervised machine learning pipeline for email classification using a dataset comprising over 5,000 messages. The workflow included text preprocessing, feature engineering, model training, and evaluation. Key features were derived using regex-based pattern extraction, word frequency metrics, and text statistics, including email length, punctuation counts, and capitalization patterns. <br>

Skills: Feature engineering, text preprocessing, classification modeling, cross-validation, model evaluation (precision-recall, ROC analysis). <br>

Technology: Python, Pandas, scikit-learn, NumPy, regex <br> 

Results: The model achieved an accuracy of over 90%, with performance optimized through multiple iterations of hyperparameter tuning. Evaluation using precision-recall curves helped balance spam detection with the risk of false positives, highlighting trade-offs relevant to real-world deployment. <br> 

Impact: Demonstrates how classification systems must balance accuracy with real-world risks, such as filtering legitimate communication. <br> 

### NBA Salary Determinants 

Code: <br> 

Description: I applied econometric regression techniques to analyze salary determinants for 269 NBA players from the 1994–95 season. I used log-transformed salary data to address skewness and incorporated performance metrics, experience, position, and race as explanatory variables. I evaluated how on-court productivity translated into wages using both simple and multivariate OLS models. <br> 

Skills: Econometric modeling, OLS regression, data transformation, statistical analysis, hypothesis testing <br>

Technology: R, tidyverse, regression modeling, data visualization <br>

Results: The analysis found that scoring and experience were the strongest predictors of salary, while race and position were not statistically significant after controlling for performance. Results suggest that observable productivity explains much of wage variation, though unobserved factors may still influence compensation. <br>

Impact: Highlights the role of econometric analysis in revealing key drivers of compensation and providing an evidence-based approach to assessing pay equity in professional sports. <br> 

### Cook County Housing Price Prediction 

Code: 

Description: Built a machine learning model to predict housing prices using 500k+ records, applying feature engineering techniques such as text mining, log transformations, and one-hot encoding. Developed a full pipeline including preprocessing, training, and evaluation using scikit-learn. Incorporated fairness analysis to assess model bias across socioeconomic groups. <br>

Skills: Machine learning, feature engineering, model evaluation, data cleaning, fairness analysis <br>

Technology: Python, pandas, scikit-learn, NumPy, matplotlib <br>

Results: Achieved strong predictive performance through K-fold cross-validation and metric comparison (RMSE vs. MAPE). Identified a 15–20% overestimation bias in lower-priced neighborhoods. <br>

Impact: Highlights how predictive models can introduce bias and the importance of evaluating fairness in real-world applications. <br>

### Climate Change & Civil Conflict

Code: 

Description: Constructed a panel dataset integrating climate, agricultural, and conflict data to analyze how environmental shocks influence civil conflict risk. Applied fixed effects regression to isolate temperature and precipitation effects while controlling for country and time factors. Replicated a foundational climate-conflict economics study. <br> 

Skills: Panel data analysis, fixed effects modeling, data merging, econometrics, statistical interpretation <br>

Technology: Python, R, pandas, statsmodels <br> 

Results: Found significant relationships between climate anomalies and increased conflict risk in certain contexts. Results aligned with established academic findings. <br> 

Impact: Demonstrates how data can inform policy discussions on climate vulnerability and conflict risk. <br>

### Minimum Wage Policy & Foreign Investment 

Code: 

Description: Conducted panel econometric analysis to examine how minimum wage policies and labor availability influence FDI inflows in Southeast Asia. Integrated datasets from ILOSTAT and the World Bank, controlling for macroeconomic variables. Applied fixed effects models to isolate labor policy impacts. <br> 

Skills: Econometrics, panel data analysis, data cleaning, policy analysis, regression modeling <br>

Technology: R, tidyverse, regression modeling <br>

Results: Found that labor availability is a stronger driver of FDI than low wages. Rising minimum wages did not significantly deter investment when supported by strong labor participation. <br> 

Impact: Provides insight into labor policy design for emerging economies competing in global manufacturing. <br> 

### Economic Impact Analysis Mariel Boatlift 

Code: 

Description: Replicated a Nobel Prize-winning natural experiment analyzing the labor market impact of immigration using 26,000+ survey records. Conducted comparative trend analysis across metropolitan areas and applied OLS regression with engineered variables. Focused on identifying causal effects from labor supply shocks. <br>

Skills: Causal inference, OLS regression, data analysis, feature engineering, data visualization <br>

Technology: Python, pandas, NumPy, matplotlib <br>

Results: Found no statistically significant negative impact on wages despite a 7% labor force increase. Results supported conclusions from the original study. <br> 

Impact: Demonstrates how empirical analysis can challenge common assumptions about immigration and labor markets. <br>

### Regional GDP Analysis 

Code: 

Description: Analyzed U.S. county-level GDP data (2001–2021) to evaluate regional economic trends and recovery patterns. Processed and reshaped large datasets (47k+ records to 718k rows) for analysis. Developed geospatial visualizations to identify growth disparities across regions. <br> 

Skills: Data cleaning, time-series analysis, data transformation, geospatial analysis, data visualization <br>

Technology: Python, pandas, matplotlib, geopandas <br>

Results: Identified stronger post-2008 recovery in coastal regions compared to the Midwest. Revealed concentrated growth in urban and tech-driven areas. <br> 

Impact: Provides a data-driven view of regional inequality and economic concentration in the U.S. <br> 

### MLB Salary Disparities Analysis 

Code: 

Description: Analyzed MLB salary determinants using regression models to evaluate the impact of race, city demographics, and performance metrics. Applied econometric techniques to control for confounding variables. Explored potential bias and omitted variable effects. <br>

Skills: Econometrics, regression analysis, bias analysis, statistical modeling, data interpretation <br> 

Technology: R, regression modeling <br> 

Results: Found performance metrics to be the strongest predictors of salary, with limited influence from demographic variables. Highlighted potential omitted variable bias. <br>

Impact: Demonstrates application of econometrics in evaluating fairness and compensation structures. <br> 

### Ants: Data-Driven Tower Defense Game 

### CATS: Typing Autocorrect System

### Movie Genre Classification K-NN 

### Climate Change: Temperature & Precipitation Analysis 

### Predicting Baseball Wins: Least Squares Regression

### World Population & Poverty Analysis 








                                                                                                          






## Education
University of California, Berkeley, College of Letters and Science - Bachelor of Arts, Economics, Minors in Data Science and Journalism <br>
(January 2024 - December 2025) 

Pasadena City College — Associate of Arts, Business, Economics UC Transfer Pathway <br>
(August 2021 – May 2023)


## Contact 
* LinkedIn: [@keynesle](https://www.linkedin.com/in/keynesle/)
* Email: [key_2112@berkeley.edu](mailto:key_2112@berkeley.edu)
