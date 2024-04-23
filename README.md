# Hacktiv8 Final Project
   ![Pikrlogo](https://github.com/FTDS-assignment-bay/p2-final-project-ftds-028-rmt-group-001/blob/main/logoPickr.png)

## 🚨Group Members🚨:
- Destriana Ramadani, enrolled as Data Engineer
- Elia Oktaviani, enrolled as Data Analyst 
- Gita Pramoedya Sastri, enrolled as Data Scientist
- Wilona Natalie, enrolled as Data Scientist

## 📢 Project Overview

## ✏️ Background

### Problem Statement
When it comes to the beauty industry, there is a vast array of products available to address different skin types, concerns, and preferences. However, the abundance of options can be overwhelming for customers. To assist users in finding the right products, a beauty product recommendation system can be developed. This system provides personalized recommendations based on the user's specific needs and preferences. 

### Objectives
- Create machine learning models that enhance customer disscovery experience to predict product with certain characteristic.
- Analyze 'Detail' column through word cloud visualization to identify and labeling the stopword and unnecessary character to be eliminated form data.
- Arrange Automation data preprocessing using airflow tools to store and clean raw data

### Dataset
The dataset used in this project is obtained from Kaggle from this [link](https://www.kaggle.com/datasets/raghadalharbi/all-products-available-on-sephora-website).

## 🗓️ Project Structure
### Workflow
The workflow is split into 3, separated by roles:

#### Data Engineering
- Data Collection: Store raw data on PostgreSQL
- Data Cleaning: Set up Apache Airflow DAG to automation fetch and clean raw data
- Data Storage: Store the cleaned data back into the PostgreSQL
#### Data Science
- Model Development: Created a recomenndation model to make product prediction based on similiarity and filter using cleaned data.
- Model Optimization: Tune and optimalize text preprocessing by make miss input correction etc.
#### Data Analysis
- Visualization: Created visual representations to simplify complex information, making it more accessible.
- Reporting: Create a comprehensive report using your collected findings and insights.

## 🎁 Results
Furthermore, all of our visualisations are also available on [Project Visualization](https://public.tableau.com/views/FinalProject_17119788212420/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link.) and [Exploratory Data Analysis](https://public.tableau.com/app/profile/elia.oktaviani/viz/FinalProjectEDA_17121230420550/Dashboard2?publish=yes)


And our deployment can be accessed on [streamlit](https://pickrapp.streamlit.app/)

 
![streamlit](https://github.com/FTDS-assignment-bay/p2-final-project-ftds-028-rmt-group-001/blob/main/barcode.png)



