Title:Trends in COVID-19 deaths with age and educational attainment in counties in Florida 

Introduction

There have been a number of trends observed bewteen demographic data such as age, race and the number of COVID-19 deaths. It has been well established that there is a direct relationship between age and the number of deaths. The older the individual, the more susceptible they may be to COVID infection and death and perhaps the less likely they are to be receptive to COVID mitigating protocols.Infection and death rates may also depend on risk of exposure and vaccination. Remote work was intended to reduce an individual's exposure to COVID-19, however, remote work may not have been possible for everyone in the different labor sectors, especially in occupations deemed 'low-skill'. It is thought that people with higher levels of education may have had more freedom to work remotely, with the exception of higher educated frontline workers, which would reduce their risk of exposure. They may also be more adherent to vaccination and COVID protocols. Given this information, it is predicted that areas with older populations and lower educaation levels would have higher deaths. Therefore, in this project, the aim is to determine whether there is a relationship between the number of covid deaths and the age and education level of the population in the counties in Florida. 

Methodology 

  Data collection 
  The cumulative COVID-19 deaths for counties in Florida for 2022 were obtained from NY Times. Florida county age for 2019 and educational attainment for 2020 were both obtained from the United States Census Bureau. 
  
From the data collected, the counties with the highest and lowest deaths were obtained. The education level for the population age 25 and older and the county population age were compared by U test to determine whether there was a difference between the two counties with regard to educational level and population age. 
It was assumed that the education data and age data for the general population do not follow normal distributions. This is supported by the plot of education level for Florida (Figure 1) and age distributions for the US (not shown). 

![plot](https://github.com/traceymoyston/Che2410_Project1/blob/4cbc502ec6fac418695732354571e3e4c033d6a5/Screen%20Shot%202022-10-25%20at%2013.08.44.png)
Figure 1: Distribution of Educational attainment for Florida in 2020 for the population 25 years and older 

The education level and population age were compared as fractions of the total county population to allow for a more accurate comparison. 

The relationship between the population age, educational attainment and COVID deaths in Florida was determined using linear regressions and accounting for interaction effects. The median age for each county and percent of the county population with a Bacelor's degree or higher were used to determine this relationship. Here, counties with older populations were defined as having a median age>50. This age was chosen based on COVID death data showing that people age 50+ were more likely to die of COVID than those younger. Percents greater than 30.5% for percent of county population with a Bachelor's degree or higher were deemed as having higher level of education since these percentages would be above the average percentage for the entire state of Florida. 


Results
By the U statistic it was determined that the educational level for Miami Dade County, the county with the highest deaths, and that of Monroe county were likely from different distributions, where the likelihood of being from the same distribution produced a p-value of 0.90. The same was determined for the population ages of the two counties, where the likelihood of them being from the same distribution produced a p-value of 0.93. 

Figures 2-5 show the plots for both counties for educational level distribution and age distribution 

![plot](https://github.com/traceymoyston/Che2410_Project1/blob/43b40908ad590c20aba9fe580b57258bda38bdbd/MiamiDade_educ.png)

Figure 2: Education level distribution as a fraction of the total poulation for Miami Dade County in 2020 for the population 25 years and older 

![plot](https://github.com/traceymoyston/Che2410_Project1/blob/43b40908ad590c20aba9fe580b57258bda38bdbd/Monroe_educ.png)

Figure 3: Education level distribution as a fraction of the total poulation for Monroe County in 2020 for the population 25 years and older

![plot](https://github.com/traceymoyston/Che2410_Project1/blob/43b40908ad590c20aba9fe580b57258bda38bdbd/Miamidade_age.png)

Figure 4: Age distribution as a fraction of the total poulation for Miami-Dade County in 2019 

![plot](https://github.com/traceymoyston/Che2410_Project1/blob/43b40908ad590c20aba9fe580b57258bda38bdbd/Monroe_age.png)

Figure 5: Age distribution as a fraction of the total poulation for Monroe County in 2019 


Linear regression analysis showed an inverse relationship between population age and COVID deaths (slope: -630) and a direct relationship between educational level and COVID-19 deaths (slope: 1155) with an inverse interactive effect (slope: -1359)

Discussion and Conclusion 
Analysis of the data showed the inverse of what was expected. This could be due to a number of reasons, it could be possible that the older population were less exposed to the virus and more adherent to mitigating protocols. Additionally, it is possible that the higher educated population may have consisted of a large amount of essential workers who were not able to work remotely. There were also limitations in the analysis in that the data collected were from different years and the COVID data does not account for vaccination rate and adherence to protocols. Also there was not complete data for all the counties in Florida and the statistical power of the analyses may have been reduced due to small sample numbers per county. Further investigations may take these factors into account to determine the relationship betweeen age, education and COVID deaths for nonessential workers. 



