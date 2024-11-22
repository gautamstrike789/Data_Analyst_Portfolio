# Data_Analyst_Portfolio

## About

I am a dedicated Data Analyst with a Master’s degree in Data Science from Berlin, Germany, and a Bachelor’s degree in IT. My journey began with a passion for technology and data, which led me to start my professional career as a Data Analyst at WhiteHat Jr immediately after graduation. Over two years, I gained hands-on experience in transforming raw data into meaningful insights, supporting data-driven decision-making across the organization.

Pursuing my Master’s degree allowed me to deepen my analytical expertise and broaden my understanding of advanced techniques, including predictive modeling and machine learning. Now, I excel at both descriptive and predictive analysis, utilizing tools like Python, Tableau, and Power BI to craft compelling visualizations and drive actionable strategies.

I’m now seeking a challenging Data Analyst role where I can contribute my technical skills and analytical mindset to deliver impactful solutions. My commitment to continuous learning and solving real-world problems drives me to create data narratives that empower businesses to achieve their goals.


### My CV in [pdf]()

This repository serves as a platform to showcase my skills, share impactful projects, and track my growth in Data Analytics and Data Science. It highlights my expertise in data cleaning, visualization, and analysis, demonstrating my ability to solve real-world problems and deliver actionable insights.

## Table of Contents
https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md
- [About](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#Portfolio-Projects)
  - Python
    - [Analyzing the Factors Contributing to the Success of a Movie](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#analyzing-the-factors-contributing-to-the-success-of-a-movie)
    - [Tech Store Sales Analysis](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#tech-store-sales-analysis)
    - [Object Detection in Satellite Imagery using Yolo]()
    - [Classification of X-Ray Images for  Pneumonia Diagnosis]()
  - SQL
    - [Covid 19 Data Exploration](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#covid-19-data-exploration)
    - [Housing Data Cleaning](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#nashville-housing-data-cleaning)
    - [Data Field Jobs Survey Analysis](https://github.com/gautamstrike789/Data_Analyst_Portfolio/blob/main/README.md#Data-Field-Jobs-Survey-Analysis)
  - Excel / Google Sheets
  - Tableau---> [go to Tableau..](https://public.tableau.com/app/profile/aman.sharma1315/vizzes)
  - Power BI
  


- [Education](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#education)  
- [Certificates](https://github.com/Kanchan-Bansode/Data-Analyst-Portfolio/blob/main/README.md#certificates)
- [Contact](https://github.com/Kanchan-Bansode/Data-Analysis-Portfolio/blob/main/README.md#contacts)
## Portfolio Projects
This section highlights my data analytics projects, with concise descriptions of each and an overview of the technology stack utilized to deliver effective solutions.

### Analyzing the Factors Contributing to the Success of a Movie
*Code:* [Analyzing the Factors Contributing to the Success of a Movie.ipynb](https://github.com/tiannaparris/PortfolioProjects/blob/main/Analyzing%20the%20Factors%20Contributing%20to%20the%20Success%20of%20a%20Movie.ipynb)

*Goal:* To determine what factors contribute the most to a movie's success.

*Description:* The project focused on analyzing a dataset of movies released between 1980 and 2022. The dataset included movie titles, ratings, genres, release dates, budgets, gross earnings, and other relevant information. The project involved loading the data, cleaning and preprocessing it, performing exploratory data analysis (EDA), analyzing the correlation between budget and gross earnings, and implemented Pearson’s correlation statistical analysis.

*Skills:* data cleaning, data analysis, correlation matrices, hypothesis testing, data visualization.

*Technology:* Python, Pandas, Numpy, Seaborn, Matplotlib, SciPy.

*Results:* Using Python functions the analysis revealed that votes and budget have the highest correlation with gross earnings, while the company has no significant correlation.

### Tech Store Sales Analysis

*Goal:* To examine the sales history of the store and extract insights on its performance, as well as to identify potential improvements that can be implemented.

*Code:* [Tech Store Sales Analysis.ipynb](https://github.com/Kanchan-Bansode/Portfolio_Projects/blob/main/Tech%20Store%20Sales%20Analysis.ipynb)

*Description:* The dataset contains a list of sales records.  The records include the products for sale and order information(order id, order date, price, quantity ordered and purchase address). The project includes the following steps: data loading, data cleaning and preprocessing, EDA (exploratory data analysis), analyzing sales data and hypothesis testing.

*Skills:* data cleaning, data analysis, hypothesis testing, data visualization.

*Technology:* Python, Pandas, Matplotlib.

*Results:* Python functions that calculated and visually presented the sales data by month, city, and the most commonly sold items. Additionally, the reasons for the high frequency of these items being sold were analyzed and provided as insights.



### Housing Data Cleaning
*Code:* [Data Cleaning Project Queries: Nashville Housing.sql](https://github.com/Kanchan-Bansode/Portfolio_Projects/blob/main/Housing%20Data%20Cleaning.sql)

**Description:**  
This project analyzes a dataset of houses sold in Nashville from 2013 to 2019. It involves critical steps such as data loading, cleaning, and preprocessing to ensure data readiness for analysis.  

**Skills:**  
Data Manipulation Language (DML), Data Query Language (DQL), Data Definition Language (DDL).  

**Technology:**  
SQL Server  

**Summary of Findings:-**

- Property and owner addresses were split into separate components (Address, City, State) for improved granularity.
Missing property addresses were populated using related records.
Data Integrity Improvements:

- Standardized date formats to maintain consistency in transaction timestamps.
Converted binary "Y/N" values in the "Sold as Vacant" field to more intuitive "Yes/No" labels.
Deduplication:

- Identified and removed duplicate records based on key attributes such as Parcel ID, Property Address, Sale Price, and Legal Reference.
Table Optimization:

- Dropped unused columns (e.g., TaxDistrict, OwnerAddress) to streamline the dataset for analysis.
  
**Limitations:-**

- Some records had missing addresses or inconsistent formats, requiring assumptions during imputation.
Data preprocessing relied on parsing patterns, which might not account for edge cases or non-standard formats.
Scope of Cleaning:

- While structural enhancements were made, no exploratory data analysis (EDA) was conducted to identify deeper trends.
Column Simplification:

- Dropping columns may limit further analysis if those fields are later deemed useful.

### Covid 19 Data Exploration
*Code:* [COVID Portfolio Project.sql](https://github.com/gautamstrike789/DataExplorationPortfolioProject/blob/main/Covid19_DataExploration.sql)

**Description:** The dataset contains records of Covid-19 cases, deaths and vaccine records by country in 2020-2021. This project includes the following steps: data loading, data cleaning and preprocessing and EDA (exploratory data analysis).

**Skills:** Joins, CTE's, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types

**Technology:** SQL Server

**Summary of Findings:-**

- The global death percentage (total deaths relative to total cases) indicates a critical mortality rate among infected populations.
Continents with the highest death counts per population are identified, providing insights into regional pandemic severity.
Country-Level Analysis:

- Countries with the highest infection rates relative to their population were identified, as well as those with the highest death counts.
India, among other countries, showed significant trends in the death percentage over time.
Vaccination Insights:

- The analysis determined the percentage of the population vaccinated in each country, highlighting the global progress in vaccination efforts.
Rolling totals of vaccinated individuals over time provided insights into the pace of vaccination campaigns.

- Calculations showed what percentage of a country’s population was infected with Covid-19, giving a comparative view of infection rates globally.

**Limitations:-**

- Some records included null or invalid values (e.g., negative ages or future termination dates). These were excluded during the analysis.
- Some vaccination records lacked complete date alignment with case/death data, which may affect trend consistency.
- The dataset does not cover all countries equally; some have incomplete records for cases, deaths, or vaccinations.
- Variations in reporting standards and testing rates among countries could introduce biases in the results.

## Education
Gisma University of Applied Science, Berlin, Germany: 
Master of Science - MSc, Data Science,
Oct 2022 - mar 2024 

Vidyalankar Institue of Technology, Mumbai, India:
Bachelor's degree, Bsc.IT,
2017 - 2019

Diploma:
Level 3 Diploma Course, Computer Technology,
2014 - 2017

## Certificates
The best way to showcase skills is by doing and sharing your job done but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have (in reverse-chronological order, with the date of completion in brackets):
- [Foundation of Data Science]() (Sep 2022) (Coursera - Google)
- [Tableau](https://www.coursera.org/account/accomplishments/verify/62LME4DV8CUV) (Oct 2022) (Coursera - University of California, Davis)
- [Python for Data Science](https://coursera.org/share/a16ecd3de61dd794199c452586cba90c) (Feb 2023) (Coursera - University of Colorado Boulder)
- [Microsoft Office Specialist: Excel Associate (Office 2019)]() (Jan 2024)

## Contacts
- LinkedIn: [@AmanSharma](www.linkedin.com/in/as-aman-sharma)
- Email: amansharmagerm@gmail.com
