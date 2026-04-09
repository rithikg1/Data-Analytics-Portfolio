<div align="center">

# Rithik Ganesan

### Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rithik-ganesan-b3982318b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rithikg1)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rithikg121@gmail.com)

---

</div>

## About Me

I'm a data analyst with hands-on experience in statistical modeling, machine learning, data visualization, and business intelligence. My work spans health analytics, environmental science, global sales strategy, and technology trend analysis. I'm proficient in Python, R, SQL, PowerBI, and Tableau and I enjoy tackling real-world problems where data can drive better decisions.

---

## Technical Skills

| Category | Tools & Technologies |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Data Science & ML** | scikit-learn, statsmodels, Random Forest, KNN, Linear & Logistic Regression, Cross-Validation |
| **Data Wrangling** | pandas, NumPy, dplyr, tidyverse |
| **Visualization** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) Matplotlib, Seaborn, ggplot2 |
| **Other** | Web Scraping, Jupyter Notebooks, RMarkdown |

---

## Projects

### Sleep Health & Digital Screen Exposure Analysis

> Investigating the factors that most influence sleep duration and quality using health and lifestyle data from 10,000+ individuals.

| | |
|---|---|
| **Objective** | Identify which lifestyle and health factors have the greatest impact on sleep duration and quality, and build predictive models for both. |
| **Dataset** | [Sleep Health and Digital Screen Exposure (Kaggle)](https://www.kaggle.com/datasets/arifmia/sleep-health-and-digital-screen-exposure-dataset/data) |
| **Methods** | Data cleaning & wrangling, exploratory data analysis, multiple linear regression (OLS), Random Forest regression, feature importance ranking |
| **Key Findings** | Linear regression identified heart rate as the only statistically significant predictor of sleep duration (p < 0.05). Random Forest models achieved low MSE (~0.43 hrs for duration, ~0.29 for quality on a 1-5 scale) and ranked physical activity, weight, height, heart rate, daily steps, and stress level as the most important predictors. |
| **Tools** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) pandas, scikit-learn, statsmodels, Seaborn, ggplot2, randomForest |

| Language | Code | Report |
|---|---|---|
| Python | [SleepHealthFactorsAnalysisPython.ipynb](SleepHealthFactorsAnalysisPython.ipynb) | [PDF Report](SleepHealthFactorsAnalysisPython.pdf) |
| R | [SleepHealthFactorsAnalysisR.Rmd](SleepHealthFactorsAnalysisR.Rmd) | [PDF Report](SleepHealthFactorsAnalysisR.pdf) |

---

### Air Quality Classification: Industrial vs. Residential

> Building classification models to determine whether a city is industrial or residential based on air quality readings.

| | |
|---|---|
| **Objective** | Create a classification model that correctly categorizes cities as industrial or residential using environmental air quality measurements (CO, NO2, PM10, PM2.5, SO2, etc.). |
| **Dataset** | [Industrial/Residential Air Quality Classification (Kaggle)](https://www.kaggle.com/datasets/youssefelebiary/industrial-residential-air-quality-classification/data) |
| **Methods** | K-Nearest Neighbors with hyperparameter tuning (k = 1-20), 10-fold cross-validation, logistic regression, confusion matrix evaluation |
| **Key Findings** | All three models achieved high classification accuracy. The cross-validated KNN model is recommended for its generalizability and reduced variance, despite slightly lower raw accuracy than the base KNN model. Industrial cities showed consistently elevated CO, NO2, PM10, PM2.5, and SO2 levels. |
| **Tools** | ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) caret, class, ggplot2, dplyr, tidyverse |

| Resource | Link |
|---|---|
| Notebook | [AirQualityClassification.Rmd](AirQualityClassification.Rmd) |
| Report | [PDF Report](Air_Quality_Classification.pdf) |

---

### Northwind Traders: Global Sales Analysis & RFP

> A comprehensive analysis of Northwind Traders' global sales data to identify key revenue drivers, growth opportunities, and strategic recommendations for an international food & beverage distributor.

| | |
|---|---|
| **Objective** | Analyze global sales data across 21 countries and 8 product categories to identify high-performing markets, revenue trends, and actionable growth strategies for the Senior Leadership Team. |
| **Dataset** | Northwind Traders internal sales database |
| **Methods** | Revenue and growth classification (quadrant analysis), geographic distribution mapping, company-level revenue analysis, product category treemaps, quarterly trend analysis |
| **Key Findings** | Europe and the USA account for 80%+ of total revenue. Beverages and Dairy Products drive over 33% of revenue. Seasonal volatility in Beverages suggests inventory optimization opportunities. No presence in Asia, Africa, or Oceania represents untapped markets. |
| **Deliverables** | Executive analysis with 5 deep-dive areas, filled geographic maps, bubble charts, treemaps, trend lines, and a formal Request for Proposal (RFP) document. |
| **Tools** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) Excel, Google Docs |
| **Team** | Rithik Ganesan, Michael Gant, Brinton Nelson, Humberto Noriega, Chloe Sanborn |

| Resource | Link |
|---|---|
| Full Report & RFP | [Northwind Traders Final Analysis and RFP.pdf](Northwind_Traders_Final_Analysis_and_RFP.pdf) |

---

### Software Technology Trends Analysis (IBM Capstone)

> Analyzing Stack Overflow developer survey data (~19,000 respondents) to identify dominant technologies, emerging trends, and declining tools across languages, databases, cloud platforms, and frameworks.

| | |
|---|---|
| **Objective** | Surface emerging technology trends and provide data-driven guidance for hiring managers and engineering leaders making stack investment decisions. |
| **Dataset** | Stack Overflow Developer Survey (sourced via Coursera / IBM Data Analytics Professional Certificate) |
| **Methods** | Web scraping for data collection, data cleaning and normalization, current vs. desired usage gap analysis, demographic segmentation, dashboard development |
| **Key Findings** | JavaScript, PostgreSQL, AWS, and React are entrenched industry standards. TypeScript, Go, and Rust are rapidly gaining desired adoption. PostgreSQL is the only technology where desired usage exceeds current usage. Developer experience and modern tooling are now decisive factors in adoption. Survey demographics skew toward 25-44 year-old developers in North America and Europe. |
| **Tools** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) Web Scraping, IBM Cognos Analytics, Excel |

| Resource | Link |
|---|---|
| Presentation | [IBM Capstone Project.pptx](IBM_Capstone_Project.pptx) |

---

## Education

**Arizona State University**
*Bachelor's Degree* | Data Analytics

---

<div align="center">

*Thank you for visiting my portfolio. Feel free to reach out for collaboration or questions!*

[![Email](https://img.shields.io/badge/rithikg121@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rithikg121@gmail.com)

</div>
