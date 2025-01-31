# README

## Table of Contents
1. [Data Collection](#data-collection)
2. [Hypotheses](#hypotheses)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Statistical Analysis](#statistical-analysis)
6. [Machine Learning](#machine-learning)

---

## Data Collection
- **Overview**: Data is about the food inspection of restuarents and other food inspections of Chicago
- **Data Sources**: Data is collected from the well known open source USA websites data.gov
- **Data Collection Methods**: Collected data was secondary in the csv format

---

## Hypotheses/Research Questions
Research Question 1: What are the top ten restaurants paying more attention to food safety? are chain restaurants better choice for food safety?
Research Question 2: Is there any relation between risk and establishment location? how to visualize it from the interactive map of Chicago?
Research Question 3: What are seasonal patterns? Are there any specific type of the violation occur during certain months?
Research Question 4: Is it possible to predict the likelihood of the restaurant passing or failing certain inspection type on various factors such as location, facility type and the inspection history? In this case we try linear regression and logistic regression or any other machine learning algorithms. 


---

## Data Cleaning
- **Data Preprocessing and Preparation**: This include, data loading and initial examination
- **Handling Missing Data**:  Wherever 'AKA Name' was empty, 'DBA Name' values were filled in order to facilitate completion of the row. Remove null values, replace with mean and mode in some cases 
- **Data Transformation**: Converted the column InspectionDate into datetime, extracted month and year. Also convert the Risk levels to categorical values. Furthermore In some cases, when the original geospatial location data was empty, a backfill method was employed to fill in those blanks and ensure that geographic analysis could proceed without major gaps in the data

---
## Exploratory Data Analysis (EDA)
1. Comparison of Pass rates Independant vs chain Restaurant
2. Top 10 restaurants by Food safety
3. Food establishment risk mapping across Chicago
4. Comparative Risk Analysis Across Zip Codes
5. 

---

## Statistical Analysis
1. Summary of zip codes and risks

---

## Machine Learning
1. Logistic Regression Model
2. Time Series Analysis 

---


 
