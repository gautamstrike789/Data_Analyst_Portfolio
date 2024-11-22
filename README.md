# Data_Analyst_Portfolio

## About

I am a dedicated Data Analyst with a Master’s degree in Data Science from Berlin, Germany, and a Bachelor’s degree in IT. My journey began with a passion for technology and data, which led me to start my professional career as a Data Analyst at WhiteHat Jr immediately after graduation. Over two years, I gained hands-on experience in transforming raw data into meaningful insights, supporting data-driven decision-making across the organization.

Pursuing my Master’s degree allowed me to deepen my analytical expertise and broaden my understanding of advanced techniques, including predictive modeling and machine learning. Now, I excel at both descriptive and predictive analysis, utilizing tools like Python, Tableau, and Power BI to craft compelling visualizations and drive actionable strategies.

I’m now seeking a challenging Data Analyst role where I can contribute my technical skills and analytical mindset to deliver impactful solutions. My commitment to continuous learning and solving real-world problems drives me to create data narratives that empower businesses to achieve their goals.

### My CV in [pdf](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/AMAN_CV.pdf)

This repository serves as a platform to showcase my skills, share impactful projects, and track my growth in Data Analytics and Data Science. It highlights my expertise in data cleaning, visualization, and analysis, demonstrating my ability to solve real-world problems and deliver actionable insights.

## Table of Contents
- [About](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#Portfolio-Projects)
  - Python
    - [HSBC Bank Fraud Analysis](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#HSBC-Bank-Fraud-Analysis)
    - [Adidas Store Sales Analysis](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#Adidas-store-sales-analysis)
  - SQL
    - [Covid 19 Data Exploration](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#covid-19-data-exploration)
    - [Housing Data Cleaning](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#Housing-data-cleaning)
  - Tableau → [Go to Tableau](https://public.tableau.com/app/profile/aman.sharma1315/vizzes)
  - Power BI → [Go to Power BI](https://github.com/gautamstrike789/DataExplorationPortfolioProject/tree/main/PowerBI_Projects)
- [Education](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#education)
- [Certificates](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#certificates)
- [Contact](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#contacts)

## Portfolio Projects

This section highlights my data analytics projects, with concise descriptions of each and an overview of the technology stack utilized to deliver effective solutions.

### HSBC Bank Fraud Analysis
*Code:* [HSBC_Bank_Fraud_Detection.ipynb](https://github.com/gautamstrike789/DataAnalyst-PortfolioProject/blob/main/HSBC_Bank_Fraud_Detection.ipynb)

**Goal:**  
To build a machine learning pipeline for detecting fraudulent banking transactions at HSBC using Random Forest, SVM, and Decision Tree models.

**Description:**  
The project aimed to develop predictive models that can identify fraudulent transactions in real-time by analyzing historical banking data. The goal was to create accurate and efficient models to help HSBC prevent fraud and secure customer data.

**Skills:**  
Data cleaning, data analysis, data visualization, supervised machine learning, model evaluation, feature engineering, performance metrics analysis.

**Technology:**  
Python, Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn (Random Forest, SVM, Decision Tree).

**Results:**  
The Random Forest model achieved 99.52% accuracy, proving to be the most effective for detecting fraud, while SVM and Decision Tree models showed promising but less optimal results. The pipeline helps HSBC by identifying fraudulent transactions early, minimizing financial losses, and improving security measures for customer data.

### Adidas Store Sales Analysis
*Code:* [Adidas Store Sales Analysis.ipynb](https://github.com/gautamstrike789/DataExplorationPortfolioProject/blob/main/Adidas_Retail_Sales_Analysis.ipynb)

**Goal:**  
To perform exploratory data analysis (EDA) on the Adidas US retail dataset to evaluate sales performance, identify trends, and provide actionable insights for business decisions.

**Description:**  
This project utilizes the Adidas US sales dataset, which includes columns such as retailer information, sales data, product details, and regional distribution. The analysis encompasses data cleaning, preprocessing, and answering business-specific questions to uncover trends and opportunities. Key operations include exploring relationships between variables, calculating metrics like average operating margins, and visualizing trends across regions, retailers, and products.

**Skills:**  
Data cleaning, exploratory data analysis (EDA), data visualization, statistical analysis, and deriving business insights.

**Technology:**  
Python, Pandas, Numpy, Matplotlib, Seaborn.

**Results:**
- Identified total sales and operating profit trends across regions, highlighting the West region as a top performer.
- Analyzed the impact of sales methods, with in-store sales outperforming online channels.
- Determined the most popular products sold by each retailer, with "Men's Street Footwear" being the highest-selling category.
- Visualized average operating margins across all product categories, pinpointing the most profitable items.
- Explored the correlation between price per unit and total sales, revealing a positive relationship.
- Evaluated average price per unit across cities to identify price-sensitive markets.
- Ranked the top 10 retailers by total sales, offering insights into key partnerships and advertising strategies.

**Business Questions Addressed:**
- How sales methods impact total sales.
- The trend of sales and operating profit across regions.
- The most popular products for each retailer.
- Average operating margins for products sold across retailers.

### Housing Data Cleaning
*Code:* [Data Cleaning Project: Housing.sql](https://github.com/gautamstrike789/DataAnalyst-PortfolioProject/blob/main/Housing%20Data%20Cleaning.sql)

**Description:**  
This project analyzes a dataset of houses sold in Nashville from 2013 to 2019. It involves critical steps such as data loading, cleaning, and preprocessing to ensure data readiness for analysis.

**Skills:**  
Data Manipulation Language (DML), Data Query Language (DQL), Data Definition Language (DDL).

**Technology:**  
SQL Server

**Summary of Findings:**
- Property and owner addresses were split into separate components (Address, City, State) for improved granularity.
- Missing property addresses were populated using related records.
- Data Integrity Improvements: Standardized date formats, converted binary "Y/N" values to more intuitive "Yes/No" labels.
- Identified and removed duplicate records based on key attributes such as Parcel ID and Sale Price.
- Dropped unused columns (e.g., TaxDistrict, OwnerAddress) to streamline the dataset for analysis.

**Limitations:**
- Some records had missing addresses or inconsistent formats, requiring assumptions during imputation.
- Data preprocessing relied on parsing patterns, which might not account for edge cases.
- Dropped columns could limit further analysis if those fields are later deemed useful.

### Covid 19 Data Exploration
*Code:* [COVID Portfolio Project.sql](https://github.com/gautamstrike789/DataExplorationPortfolioProject/blob/main/Covid19_DataExploration.sql)

**Description:**  
The dataset contains records of Covid-19 cases, deaths, and vaccine records by country in 2020-2021. This project includes the following steps: data loading, data cleaning and preprocessing, and exploratory data analysis (EDA).

**Skills:**  
Joins, CTEs, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types.

**Technology:**  
SQL Server

**Summary of Findings:**
- Identified regions with the highest death counts per population, providing insights into pandemic severity.
- Analyzed countries with the highest infection rates and death counts.
- Explored vaccination rates by country, highlighting the global progress in vaccination campaigns.
- Calculated infection percentages for each country, giving a comparative view of infection rates globally.

**Limitations:**
- Some records included null or invalid values, which were excluded during analysis.
- Variations in reporting standards and testing rates among countries could introduce biases in the results.

## Education

**Gisma University of Applied Science, Berlin, Germany**  
Master of Science - MSc, Data Science  
Oct 2022 - Mar 2024  

**Vidyalankar Institute of Technology, Mumbai, India**  
Bachelor's degree, BSc.IT  
2017 - 2019  

**Diploma**  
Level 3 Diploma Course, Computer Technology  
2014 - 2017  

## Certificates

The best way to showcase skills is by doing and sharing your work, but sometimes certificates are also valuable. Here’s a list of my certificates (in reverse-chronological order, with the date of completion in brackets):
- [Foundation of Data Science](#) (Sep 2022) (Coursera - Google)
- [Tableau](https://www.coursera.org/account/ac
