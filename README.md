# **ANALYSIS OF COVID-19 IN SOUTH AMERICA**

![covid-19 red cell image](https://img.freepik.com/free-vector/covid19-coronavirus-red-virus-cell-spread-background-concept_1017-24697.jpg?w=2000)

The aim of this project is to find out how SARS-CoV-2 (Covid-19) affected the south american region of the world, showcasing some techniques of data cleaning, data preparation, and data visualization.

Some of the essential questions for developing this project are related to the number of cases on every country of the region, the number of deceased, the number of people vaccinated, etc.

The data used for the analysis has been aqcuired from the covid-dateset csv pointed at https://github.com/owid/covid-19-data/tree/master/public/data. It contains a collection of the COVID-19 data maintained by Our World in Data, from February 2020 up to September 2022, and collects information from 218 countries from around the world. The information outside the scope of this project was despised.

The tools used to handle the data were the Python packages Numpy and Pandas, and for visualization, the packages used were Matplotlib and Seaborn.



## **TABLE OF CONTENTS**
**1. Imports and reading dataset.**
In this step the packages used for the analysis are imported, and the dataset is loaded for further analysis.

**2. Data preparation: Wrangling**
Data wrangling, sometimes referred to as data munging, is the process of transforming and mapping data from one "raw" data form into another format with the intent of making it more appropriate and valuable for a variety of downstream purposes such as analytics. The goal of data wrangling is to assure quality and useful data. In this step problems like missing, invalid, and inconsistent values have been addressed.

**3. Exploratory Data Analysis (EDA) and Visualization.**
In this step the dataset is analyzed to perform initial investigations to discover patterns, spot anomalies, to test hypotesis and to check assumptions with the help of summary statistics and graphical representations. The distribution, correlation, relationship, composition and comparison of the data is addressed in this step.

  **- Quantitive and qualitative analysis: Asking and Answering Questions.**
    - Did countries with more smokers had a bigger rate of death between the infected?
    - Is the rate of death higher in countries with a big share of the population older than 65 years old?
    - Which countries were the first to start applying vaccines against Covid-19? Are these countries the more developed?
    - Is human development index related to the number of infections? In other words, are countries less developed more affected by the virus?
  
**4. Presentation of findings: Conclusions.**
In this step the most significants insights are presented.
