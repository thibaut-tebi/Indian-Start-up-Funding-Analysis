


# Indian-Start-up-Funding-Analysis

This This repositiory presents an analysis of funding received by Indian startups from 2018 to 2021 using Exploratory Data Analysis (EDA) techniques. The objective of this analysis was to gain insights into the Indian startup ecosystem, provide valuable information for decision-makers considering entry into the market, and understand the funding and growth patterns of newly launched startups. 

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) plays a vital role in understanding and extracting insights from datasets. It allows us to uncover patterns, relationships, and key characteristics of the data. The main objective of this project is to utilize the CRISP-DM framework as a guiding framework for conducting exploratory data analysis (EDA) and extracting valuable insights. The CRoss Industry Standard Process for Data Mining (CRISP-DM) is a process model that serves as the base for data processing. CRISP-DM involves stages that enable a systematic and structured approach to the analysis process. 

## Introduction

The analysis was performed using the Python programming language and popular libraries such as Pandas, Numpy, and Matplotlib. These libraries facilitated various analysis tasks, including examining individual variables, exploring relationships between variables, analyzing correlations, and handling duplicate and missing data. 

The analysis was conducted in a Jupyter Notebook environment, which allowed for an interactive and organized workflow. The notebook provided a seamless platform to execute code, visualize data, and document the analysis process.Standard EDA procedures were followed, including assessing data quality, performing descriptive statistics, and creating visualizations. 

The dataset was explored to understand its structure, check for missing or duplicated data, and convert variables to appropriate formats when necessary. Descriptive statistics provided a summary of the data, allowing for an understanding of the central tendencies, variations, and distributions of the funding received by Indian startups. Visualizations, such as histograms, scatter plots, and correlation matrices, were created to identify patterns, trends, and relationships between variables.The analysis also involved examining the relationship between funding and the growth of startups, enabling the identification of potential factors influencing success and providing insights for decision-making.

## 1. Import libraries 
To begin our analysis, we import the necessary libraries and packages that will be used throughout the process. These libraries include:

1. 	Pandas: A powerful tool for data manipulation and analysis, allowing us to handle and manipulate datasets efficiently. It is imported using the statement "import pandas as pd"
2. 	Numpy: A fundamental library for scientific computing in Python, providing a range of mathematical functions and support for multi-dimensional arrays. It enables efficient numerical operations on data and is imported as "import numpy as np".
3. 	Matplotlib: A widely used plotting library that offers various customization options for creating charts, graphs, and plots. It allows us to visualize and communicate our findings effectively. It is imported as "import matplotlib.pyplot as plt".

## 2. To Gain Data Insights

1. df.shape(): This function provides the total number of rows and columns in the dataset. In our case, the 2018 dataset has 526 rows and 6 columns.
2. df.head(): This function displays the first five rows of the dataset, giving us a glimpse of the data. Similarly, df.tail() shows the last five rows of the dataset.
3. df.info(): By using this function, we can obtain information about the dataset, including the column names and their data types. In our 2018 dataset, all columns have the 'object' data type. It also informs us about the number of non-null values in each column.

By applying these methods to our dataset, we gain a comprehensive understanding of its structure and content. This allows us to identify any initial issues and establish the purpose of our analysis. It helps us define specific problems to be addressed and derive insights for solving them

## 3. Hypothesis 
During the analysis process, a null hypothesis is formulated to guide the investigation. Various questions are posed and analyzed to gain insights from the data. Ultimately, the null hypothesis is either accepted or rejected based on the findings derived from the data analysis.

1. NULL : Technological industries do not have a higher success rate of being funded. 
2. ALTERNATE : Technological industries have a higher success rate of being funded


## Questions
The following questions were asked to assist in the data analysis process

1. Which company received the most funding?
2. Which company received the lowest amount of funding?
3. Which Sector received the highest amount of funding?
4. Which Sector received the lowest amount of funding?
5. Which HeadQuarters recorded the highest amount of funding received?
6. What is the total amount funding received each year?
7. what is the average amount received in 2019, 2020 and 2021
8. At what stage do startups receive the most funding?
9. Does the location affect the funding received?.
10. Which Sector received the highest funding in 2018?

## Issues with The Data

After looking carefully at the data, the following issues were identified

1. The 2018 Dataset had different and fewer columns
2. There are missing values
3. Some values are in the wrong columns
4. The datatypes of some of the columns need to be changed
5. One column is unnamed

## Handling issues with the data
The following steps were taken to handle the issues with the datasets

1. Analyse the 2018 data separately from the rest
2. Replace missing data with either N/A or the mode of that column depending on the column data
3. Move values in the wrong columns to their appropriate columns
4. Change the datatype of columns to appropriate datatypes
5. Checked the summary statistics to identify any inconsistencies or outliers in the data.
6. Removed any duplicate records to ensure a high level of data accuracy.
7. Adding new columns to the dataset to capture additional information and insights.
8. Performed advanced techniques such as data imputation, outlier detection and handling, and data normalization to further improve the quality of the data.
9. Rename columns





## Answering the questions. 


The answers to some of the relevants questions above are virsualized using the dashbooard below. 
![image](https://github.com/thibaut-tebi/Indian-Start-up-Funding-Analysis/assets/113062383/57bce112-bdc7-4de4-9184-fa43caa6e993)


Analysis Report:

Upon analyzing the datasets for the years 2018, 2019, 2020, and 2021, it became evident that the features and trends in 2018 differed from the subsequent years. Therefore, a separate analysis was conducted for the 2018 dataset. The analysis revealed several key insights.

Firstly, the Technology sector emerged as the most funded sector, receiving a substantial sum of $179.342 billion. This sector demonstrated its dominance in attracting investments. Additionally, it was observed that the headquarters located in Mumbai received the highest funding among all the regions.

Secondly, the average funding received across various sectors during this period amounted to $151 million, indicating a significant level of investment activity. On the other hand, the Construction sector received the least funding, totaling $3.3 million, highlighting its relatively lower appeal to investors.

The analysis of 2018 data reinforced the finding that the Technology sector consistently received the highest funding throughout the entire period from 2018 to 2021. This demonstrates the sustained investment interest in the technology industry over the years.








  
  
  
  
  
  
  
  
  
  
  
  ## FINDINGS, RECOMMENDATIONS AND CONCLUSIONS


