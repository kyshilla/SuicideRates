# Suicide Rates by Socioeconomic Factors
## Introduction
A case study on the suicide rates based on dataset in Kaggle entitled "Suicide Rates & Socioeconomic Factors" in csv format. This case study will emphasize on the suicide rates based on socioeconomic factors over a period of 11 years which are from 2012- 2022. The suicide rates are studied based on genders, regions, death rate per 100k suicides, employment ratio, GDP and Gross National Income. Both data cleaning and analysing was done based on R programming language on RStudio.

## Data Cleaning
Data cleaning was done using R programming language. A total of 118,560 records were recorded with 18 different variables. 
Data was loaded from the kaggle CSV file saved on a folder and filtered to include only records from years 2012 to 2022 and to exlude columns that showed generation and inflation rate.
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/87f2005a-42ab-4213-8a1a-2ed79ccbad75)
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/eb374314-b030-4b89-a533-bd4b8b23b85d)
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/8026593d-7f9f-4e4d-9ddf-6d3100707e7c)
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/afc51f17-c5db-449a-b8c7-0c123f7f6043)

The following were the 18 different variables of the dataset :
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/80d70025-e15f-44c0-a6bd-da0253202f73)

The data was cleaned to remove any records with the Suicide Counts that were 0.
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/b3df3765-8ad7-4c18-b538-1712b5d6622b)

In total, there were more than 2 million recorded suicide counts from 2012- 2022.
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/0001f868-6cf5-4e20-9005-befdaf669598)



## Data Analyzing and Visualization
Data was analysed using "dpylr" package and visualised using the "ggplot2" package in RStudio using R.

Data was grouped to show the sum of all suicide counts based on years. 
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/6f7cc0dd-cef7-4c88-99df-d7b8f5c6f68f)

Data visualization for the total suicides against year is as follow:
![image](https://github.com/kyshilla/SuicideRates/assets/145910359/c105b7ce-b678-41e9-afb1-e1ce7b89b506)

Based on the graph shown, suicides per year have been above 200k from year 2012 to 2019 but there is a gradual fall in cases from 2020 to 2022, with year 2019 reporting the highest amount of cases which is 239,013 cases.





