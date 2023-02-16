# COVID-19 Project

## Introduction question and what we found interesting
### How the pandemic affected our normal lives and how to prepare for potential future pandemic spread?
### In the first two years of the pandemic, COVID-19 was identified as the third leading cause of death in the United States, trailing only heart disease and cancer.

## Data was obtained through excel files from the CDC official website.
### Some of the main factors we looked for were COVID-19 deaths and hospitalizations, age groups, and administered vaccine doses

## Questions Answered
### Question 1- What has been the weekly COVID-19 hospitalization?
#### The highest weekly hospitalization was during 1/19/22 (5.6M cases), Omicron started on late 11/19/21. Total cumulative hospitalization as of 2/8/23 is 102M, with current hospitalization of 23K.

### Question 2- What has been the COVID-19 weekly deaths? 
#### Highest number of death was on the week of 1/31/21 (7.04 per 100K population)
#### Total # of death 1.1M in the U.S.A (total cases worldwide were 673M and deaths were 6.58M, that is 1% deaths) 

### Question 3- What has been the weekly COVID-19 vaccination administered? 
#### Vaccination in the U.S. started on 12/9/20
#### Highest vaccination per week happened on 4/14/21 at 23.3M doses
#### Total cumulative vaccination administered in the U.S.A are 670.3M 
![image](https://user-images.githubusercontent.com/120426753/219247986-d63b2348-46a1-4a2a-bbac-2d4dfbb35a79.png)

### Questions 4- What have been the relationship between age group and COVID-19 deaths?
#### Due to Pearson’s Correlation--r value is about 0.2 which is less than 0.3.  Therefore, the correlation between weekly deaths and weekly administered doses are very weak or none 
#### 89% of COVID-19 deaths were among people aged 55 years and older.
![image](https://user-images.githubusercontent.com/120426753/219248101-535a65b3-388f-4d10-bc85-6634f728f73c.png)

### Question 5- What does the Chi Square Test Reveal for the Number of COVID-19 Deaths by Age?
#### With the Chi Square Test, Critical Value of 18.31 shows that the statistics are very significant. Null hypothesis is rejected and your statistical is significantly different.  We expected the total deaths would be the same across all age groups (100,176). However, the test shows that our expectation was far from reality  (Total deaths: 1.1M, Expected COVID-19 Deaths: 100,176.55.

### Additionial Findings
#### 4 of the top 5 underlying conditions associated with respiratory condition .
#### The top two conditions have much larger associated deaths. About 35% of COVID-19 deaths with underlying conditions were Influenza/Pneumonia and Respiratory failure.
#### About 45% of the COVID-19 deaths with underlying conditions were respiratory diseases, 4 of the top 5 underlying conditions were respiratory.


## Covid_analysis.ipynb Process

### Covid-19 Data 1 Steps

#### 1- Find the relationship between age group and COVID-19 deaths
#### 2- Ignore gender and add the total COVID-19 deaths for all three years. Seperating them by age group. Make a dataframe showing age group and COVID-19 Deaths. Save the new dataframe into a .csv.
#### 3- Make a bar graph, x-axis is the different age groups, y-axis is the total deaths. Save the graph as a .png.
#### 4- Perform Chi-Sqaured test for age group and COVID-19 deaths to test significance of the data. 

### COVID Data 2 Steps

#### 1- Find the relationship between underlying conditions and COVID-19 deaths.
#### 2- Import data into a dataframe and clean the dataframe to show total COVID-19 deaths for each underlying condition for all three years. Save the new dataframe into a .csv.
#### 3- Make a bar graph, x-axis is the different underlying conditions, y-axis is the total deaths. Save the graph as a .png.

