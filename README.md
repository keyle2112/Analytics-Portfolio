# Keynes' Data Analytics Portfolio

## About 
I’m Keynes (pronounced Key-eans), a UC Berkeley graduate in Economics with minors in Data Science and Journalism, focused on using data to understand human behavior and communicate insights through clear, structured storytelling. My work spans machine learning, econometric analysis, and data-driven projects, with an emphasis on turning analysis into actionable insight rather than just prediction.

Alongside my academic work, I’ve gained experience in live and culture-driven environments, including supporting production for the Super Bowl LX Halftime Show and contributing to music and entertainment initiatives centered on audience engagement. These experiences have shaped how I approach analytics, viewing it not just as numbers but as part of larger systems where timing, coordination, and decision-making matter. I’m particularly interested in applying data analysis within the music and entertainment industry, exploring how audience insights, trends, and behavior can inform strategy and creative direction. 

This repository highlights my work across Python, SQL, and data analysis projects, with a growing focus on music and entertainment applications.

For a broader view of my work across culture, live production, and creative projects, visit my [personal website](https://keynesle.com).

## Table of Contents
* [About](#about)
* [Projects](#projects)
  * Python
     * [Email Spam Classification System](#email-spam-classification-system)
     * [Cook County Housing Price Prediction](#cook-county-housing-price-prediction)
     * [Climate Change & Civil Conflict](#climate-change--civil-conflict)
     * [Economic Impact Analysis: Mariel Boatlift](#economic-impact-analysis-mariel-boatlift)
     * [Regional GDP Analysis](#regional-gdp-analysis)
     * [Ants: Data-Driven Tower Defense Game](#ants-data-driven-tower-defense-game)
     * [CATS: Typing Autocorrect System](#cats-typing-autocorrect-system)
     * [Classifying Movies (K-Nearest Neighbors)](#classifying-movies-k-nn)
     * [Climate Change: Temperatures and Precipitation](#climate-change-temperature--precipitation-analysis)
     * [World Population and Poverty](#world-population--poverty-analysis)
  * R
     * [NBA Salary](#nba-salary-determinants)
     * [Climate Change & Civil Conflict](#climate-change--civil-conflict)
     * [Minimum Wage Policy & Foreign Investment](#minimum-wage-policy--foreign-investment)
     * [Econometrics Analysis of MLB Salary Disparities](#econometrics-analysis-of-mlb-salary-disparities-analysis)
     * [Predicting Baseball Wins](#predicting-baseball-wins-least-squares-regression)
  * SQL
  * Excel/Google Sheets
  * Tableau
  * Power BI
  * APIs
* [Education](#education)
* [Contact](#contact)

## Projects 
*insert summary sentence when all projects are added* <br>

### Email Spam Classification System

November 2025 - December 2025 <br>

[Part 1 Notebook](projects/projB1.ipynb) | [Part 1 PDF](projects/projB1.pdf) | [Part 2 Notebook](projects/projB2.ipynb) | [Part 2 PDF](projects/projB2.pdf) <br>

Goal: To build a text-based classification model that distinguishes spam from legitimate emails while minimizing false positives. <br>

Description: This project involved constructing a supervised machine learning pipeline for email classification using a dataset comprising over 5,000 messages. The workflow included text preprocessing, feature engineering, model training, and evaluation. Key features were derived using regex-based pattern extraction, word frequency metrics, and text statistics, including email length, punctuation counts, and capitalization patterns. <br>

Skills: Feature engineering, text preprocessing, classification modeling, cross-validation, model evaluation (precision-recall, ROC analysis). <br>

Technology: Python, Pandas, scikit-learn, NumPy, regex <br> 

Results: The model achieved an accuracy of over 90%, with performance optimized through multiple iterations of hyperparameter tuning. Evaluation using precision-recall curves helped balance spam detection with the risk of false positives, highlighting trade-offs relevant to real-world deployment. <br> 

Impact: Demonstrates how classification systems must balance accuracy with real-world risks, such as filtering legitimate communication. <br> 

### NBA Salary Determinants

September 2025 - December 2025 <br>

[PDF](projects/Labor%20Economics%20NBA%20Salary%20Determinants%20Project.pdf) <br>

Description: I applied econometric regression techniques to analyze salary determinants for 269 NBA players from the 1994–95 season. I used log-transformed salary data to address skewness and incorporated performance metrics, experience, position, and race as explanatory variables. I evaluated how on-court productivity translated into wages using both simple and multivariate OLS models. <br> 

Skills: Econometric modeling, OLS regression, data transformation, statistical analysis, hypothesis testing <br>

Technology: R, tidyverse, regression modeling, data visualization <br>

Results: The analysis found that scoring and experience were the strongest predictors of salary, while race and position were not statistically significant after controlling for performance. Results suggest that observable productivity explains much of wage variation, though unobserved factors may still influence compensation. <br>

Impact: Highlights the role of econometric analysis in revealing key drivers of compensation and providing an evidence-based approach to assessing pay equity in professional sports. <br> 

### Cook County Housing Price Prediction

October 2025 <br>

[Part 1 Notebook](projects/projA1.ipynb) | [Part 1 PDF](projects/projA1.pdf) | [Part 2 Notebook](projects/projA2.ipynb) | [Part 2 PDF](projects/projA2.pdf) <br>

Description: Built a machine learning model to predict housing prices using 500k+ records, applying feature engineering techniques such as text mining, log transformations, and one-hot encoding. Developed a full pipeline including preprocessing, training, and evaluation using scikit-learn. Incorporated fairness analysis to assess model bias across socioeconomic groups. <br>

Skills: Machine learning, feature engineering, model evaluation, data cleaning, fairness analysis <br>

Technology: Python, pandas, scikit-learn, NumPy, matplotlib <br>

Results: Achieved strong predictive performance through K-fold cross-validation and metric comparison (RMSE vs. MAPE). Identified a 15–20% overestimation bias in lower-priced neighborhoods. <br>

Impact: Highlights how predictive models can introduce bias and the importance of evaluating fairness in real-world applications. <br>

### Climate Change & Civil Conflict

April 2025 - May 2025 <br>

[PDF](projects/Econ%20148%20Climate%20Change%20%26%20Civil%20Conflict.pdf) <br>

Description: Constructed a panel dataset integrating climate, agricultural, and conflict data to analyze how environmental shocks influence civil conflict risk. Applied fixed effects regression to isolate temperature and precipitation effects while controlling for country and time factors. Replicated a foundational climate-conflict economics study. <br> 

Skills: Panel data analysis, fixed effects modeling, data merging, econometrics, statistical interpretation <br>

Technology: Python, R, pandas, statsmodels <br> 

Results: Found significant relationships between climate anomalies and increased conflict risk in certain contexts. Results aligned with established academic findings. <br> 

Impact: Demonstrates how data can inform policy discussions on climate vulnerability and conflict risk. <br>

### Minimum Wage Policy & Foreign Investment

January 2025 - May 2025 <br>

[PDF](projects/Minimum%20Wage%20Policy%20%26%20Foreign%20Investment.pdf) <br>

Description: Conducted panel econometric analysis to examine how minimum wage policies and labor availability influence FDI inflows in Southeast Asia. Integrated datasets from ILOSTAT and the World Bank, controlling for macroeconomic variables. Applied fixed effects models to isolate labor policy impacts. <br> 

Skills: Econometrics, panel data analysis, data cleaning, policy analysis, regression modeling <br>

Technology: R, tidyverse, regression modeling <br>

Results: Found that labor availability is a stronger driver of FDI than low wages. Rising minimum wages did not significantly deter investment when supported by strong labor participation. <br> 

Impact: Provides insight into labor policy design for emerging economies competing in global manufacturing. <br> 

### Economic Impact Analysis Mariel Boatlift

February 2025 - March 2025 <br>

[Project Files](projects/Econ%20148%20Economic%20Impact%20Analysis.zip) <br>

Description: Replicated a Nobel Prize-winning natural experiment analyzing the labor market impact of immigration using 26,000+ survey records. Conducted comparative trend analysis across metropolitan areas and applied OLS regression with engineered variables. Focused on identifying causal effects from labor supply shocks. <br>

Skills: Causal inference, OLS regression, data analysis, feature engineering, data visualization <br>

Technology: Python, pandas, NumPy, matplotlib <br>

Results: Found no statistically significant negative impact on wages despite a 7% labor force increase. Results supported conclusions from the original study. <br> 

Impact: Demonstrates how empirical analysis can challenge common assumptions about immigration and labor markets. <br>

### Regional GDP Analysis

February 2025 <br>

[Project Files](projects/Econ%20148%20Regional%20GDP%20Analysis.zip) <br>

Description: Analyzed U.S. county-level GDP data (2001–2021) to evaluate regional economic trends and recovery patterns. Processed and reshaped large datasets (47k+ records to 718k rows) for analysis. Developed geospatial visualizations to identify growth disparities across regions. <br> 

Skills: Data cleaning, time-series analysis, data transformation, geospatial analysis, data visualization <br>

Technology: Python, pandas, matplotlib, geopandas <br>

Results: Identified stronger post-2008 recovery in coastal regions compared to the Midwest. Revealed concentrated growth in urban and tech-driven areas. <br> 

Impact: Provides a data-driven view of regional inequality and economic concentration in the U.S. <br> 

### Econometrics Analysis of MLB Salary Disparities Analysis

November 2024 - December 2024 <br>

[PDF](projects/Econometrics%20Analysis%20of%20MLB%20Salary%20Disparities.pdf) <br>

Description: Analyzed MLB salary determinants using regression models to evaluate the impact of race, city demographics, and performance metrics. Applied econometric techniques to control for confounding variables. Explored potential bias and omitted variable effects. <br>

Skills: Econometrics, regression analysis, bias analysis, statistical modeling, data interpretation <br> 

Technology: R, regression modeling <br> 

Results: Found performance metrics to be the strongest predictors of salary, with limited influence from demographic variables. Highlighted potential omitted variable bias. <br>

Impact: Demonstrates application of econometrics in evaluating fairness and compensation structures. <br> 

### Ants: Data-Driven Tower Defense Game

November 2024 <br>

[Project Files](projects/Data%20C88C%20Ants.zip) <br>

Description: Developed a tower defense game using object-oriented programming concepts, including classes, inheritance, and method design. Implemented gameplay mechanics such as pathfinding, attack systems, and resource management. Focused on modular design and extensibility.

Skills: Object-oriented programming, algorithm design, problem-solving, software development, debugging

Technology: Python

Results: Successfully built a fully functional game with dynamic interactions and scalable design. Demonstrated strong understanding of OOP principles.

Impact: Shows ability to apply programming concepts to build complex, interactive systems.

### CATS: Typing Autocorrect System

October 2024 - November 2024 <br>

[Project Files](projects/Data%20C88C%20Cats.zip) <br>

Description: Designed a typing software system to measure speed and accuracy while implementing autocorrect functionality. Used recursive algorithms and dynamic programming for string comparison. Included multiplayer and real-time feedback features.

Skills: Algorithms, recursion, dynamic programming, string processing, software development

Technology: Python

Results: Developed efficient autocorrect and accuracy algorithms with real-time performance tracking. Improved typing feedback accuracy and responsiveness.

Impact: Demonstrates ability to build optimized algorithms for user-facing applications.

### Classifying Movies K-NN

April 2024 <br>

[Project Files](projects/Data%208%20Project%203%20Classification.zip) <br>

Description: Built a k-nearest neighbors classifier to predict movie genres based on keyword frequency in scripts. Engineered custom features and applied Euclidean distance for classification. Evaluated model performance across different feature sets.

Skills: Machine learning, feature engineering, classification, data analysis, model evaluation

Technology: Python, scikit-learn, pandas

Results: Improved classification accuracy through feature selection and distance tuning. Identified key word associations driving genre prediction.

Impact: Illustrates how text-based features can be used to model content classification.

### Climate Change: Temperature & Precipitation Analysis

March 2024 - April 2024 <br>

[Project Files](projects/Data%208%20Project%202%20Climate%20Change%20Temperatures%20and%20Precipitation.zip) <br>

Description: Analyzed temperature and precipitation trends across 210 U.S. cities to study long-term climate patterns. Applied hypothesis testing and confidence intervals to evaluate changes. Conducted A/B testing on drought conditions.

Skills: Statistical analysis, hypothesis testing, data visualization, data analysis, inference

Technology: Python, pandas, matplotlib 

Results: Identified statistically significant warming trends across cities. Found measurable differences in precipitation patterns during drought periods.

Impact: Demonstrates use of statistical methods to analyze environmental trends.

### Predicting Baseball Wins: Least Squares Regression

March 2024 - April 2024 <br>

[PDF](projects/Predicting%20Baseball%20Wins%20Project.pdf) <br>

Description: Developed regression models to predict MLB team wins using performance metrics such as runs scored and allowed. Applied simple and multiple regression techniques. Incorporated transformations to improve model fit. 

Skills: Regression analysis, statistical modeling, data analysis, model evaluation, sports analytics 

Technology: R 

Results: Improved model accuracy using additional variables and transformations. Found strong relationships between run differential and team success. 

Impact: Shows application of regression modeling in sports performance analysis. 

### World Population & Poverty Analysis

February 2024 <br>

[Project Files](projects/Data%208%20Project%201%20World%20Population%20and%20Poverty.zip) <br>

Description: Analyzed global population and poverty trends across 145 countries using statistical visualization techniques. Explored relationships between life expectancy, fertility, and economic conditions. Included case study analysis of demographic changes.

Skills: Data visualization, statistical analysis, exploratory data analysis, data interpretation, global analysis

Technology: Python, pandas, matplotlib

Results: Identified strong relationships between development indicators and population dynamics. Highlighted patterns in global poverty reduction.

Impact: Provides insights into global inequality and demographic change using data analysis.

## Education
University of California, Berkeley, College of Letters and Science - Bachelor of Arts, Economics, Minors in Data Science and Journalism <br>
(January 2024 - December 2025) 

Pasadena City College — Associate of Arts, Business, Economics UC Transfer Pathway <br>
(August 2021 – May 2023)


## Contact 
* LinkedIn: [@keynesle](https://www.linkedin.com/in/keynesle/)
* Email: [key_2112@berkeley.edu](mailto:key_2112@berkeley.edu)
