# Covid Project

## covid_analysis.ipynb 

### Covid Data 1 Intstructions

#### 1- Find the relationship between age group and Covid-19 deaths
#### 2- Ignore gender and add the total Covid-19 deaths for all three years. Seperating them by age group. Make a dataframe showing age group and Covid-19 Deaths. Save the new dataframe into a .csv.
#### 3- Make a bar graph, x-axis is the different age groups, y-axis is the total deaths. Save the graph as a .png.
#### 4- Perform Chi-Sqaured test for age group and Covid-19 deaths to test significance of the data. 


### Covid Data 2 Instructions

#### 1- Find the relationship between underlying conditions and Covid-19 deaths.
#### 2- Import data into a dataframe and clean the dataframe to show total Covid-19 deaths for each underlying condition for all three years. Save the new dataframe into a .csv.
#### 3- Make a bar graph, x-axis is the different underlying conditions, y-axis is the total deaths. Save the graph as a .png.
Questions that you found interesting and what motivated you to answer them
How the pandemic affected our normal lives and how to prepare for potential future pandemic spread?
Fact: In the first two years of the pandemic, COVID-19 was identified as the third leading cause of death in the United States, trailing only heart disease and cancer.

Where and how you found the data you used to answer these questions
CDC website
Downloaded raw CSV and Excel files from the CDC website 
![image](https://user-images.githubusercontent.com/120353392/219238440-650d0ef7-6f01-4564-8168-61121d5c5cce.png)

1- What has been the weekly COVID-19 hospitalization?
The highest weekly hospitalization was during 1/19/22 (5.6M cases), Omicron started on late 11/19/21. Total cumulative hospitalization as of 2/8/23 is 102M, with current hospitalization of 23K  (Slide# 4 (page #)- Plot)

2- What has been the COVID weekly deaths? 
Highest number of death was on the week of 1/31/21 (7.04 per 100K population)
Total # of death 1.1M in the U.S.A (total cases worldwide were 673M and deaths were 6.58M, that is 1% deaths) (Slide# 5 (page#)- Plot)

3 and 4- What has been the weekly COVID-19 vaccination administered? 
Vaccination in the U.S. started on 12/9/20
Highest vaccination per week happened on 4/14/21 at 23.3M doses
Total cumulative vaccination administered in the U.S.A are 670.3M (Slide# 6 and 7 (page#)-Plot)

5- What have been the relationship between age group and COVID-19 deaths?
Due to Pearson’s Correlation--r value is about 0.2 which is less than 0.3.  Therefore, the correlation between weekly deaths and weekly administered doses are very weak or none 
89% of COVID deaths were among people aged 55 years and older (Slide# 8 (page#)-Plot)


6- What does the Chi Square Test Reveal for the Number of COVID Deaths by Age?
With the Chi Square Test, Critical Value of 18.31 shows that the statistics are very significant. Null hypothesis is rejected and your statistical is significantly different.  We expected the total deaths would be the same across all age groups (100,176). However, the test shows that our expectation was far from reality  (Total deaths: 1.1M, Expected COVID-19 Deaths: 100,176.55 (Slide# 9 (page#)-Plot)

4 of the top 5 underlying conditions associated with respiratory condition 
The top two conditions have much larger associated deaths. About 35% of COVID-19 deaths with underlying conditions were Influenza/Pneumonia and Respiratory failure
About 45% of the COVID-19 deaths with underlying conditions were respiratory diseases, 4 of the top 5 underlying conditions were respiratory![image](https://user-images.githubusercontent.com/120353392/219239393-91836358-758b-4349-868d-33058a777e2e.png)
