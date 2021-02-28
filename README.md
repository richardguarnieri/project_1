# Patterns in Worldwide Suicide Rates
ITESM Data Analytics Boot Camp

## The Outline
Death by suicide is an extremely complex issue that causes pain to hundreds of thousands of people each year around the world. Our project is to uncover patterns in worldwide suicide rates. We will examine the relationships between number of suicides across multiple countries, years, genders, ages and several demographic and socioeconomic factors in order to understand if there are underlying factors influencing suicide rates across the world. 


## Main Questions
The questions we will be asking of the data are the following:
1. How do socioeconomic variables affect the suicide rate by country?
2. In which countries are there more suicides and how is the standard of living in them?
3. In what age range are there more suicides?
4. What gender is more likely to commit suicide?

## Datasets
We decided to use two different datasets from **Kaggle**. 

Demographic and Socio-economic (UNESCO) 
Demographic: fertility rate, life expectancy, motality rate, population growth, etc… 
Socio-economic: GDP growth, GDP per capita, government total expenditure, etc… 

Source: https://www.kaggle.com/krukmat/demographic-and-socioeconomic-unesco

Suicide Rates Overwiew 1985 to 2016
Variables: year, country, number of suicides by year, population by year, etc… 
“This compiled dataset pulled from four other datasets linked by time and place. It was built to find signals correlated to increased suicide rates among different cohorts globally, across the socio-economic spectrum”. 

Source: https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016

## Sample Images
![Number of Suicides per Year (1985 - 2015)](https://github.com/richardguarnieri/project_1/blob/main/Images/suicides_per_year.png?raw=true)
*Number of Suicides per Year (1985 - 2015)*

![Total Number of Suicides per Country (1985 - 2015)](https://github.com/richardguarnieri/project_1/blob/main/Images/suicides_per_country.png?raw=true)
*Total Number of Suicides per Country (1985 - 2015)*

## Conclusion
* Men commit a lot more suicides than women - not only in general - divided by country, and age group, men can commit up to 5 times more suicides.
* With the age group bins 5-14, 15-24, 25-34, 35-54, 55-74, 75+, there is a tendency where the older you are, the higher the suicide rates - older age groups have higher suicides per 100k population than younger age groups.
* From all the demographic indicators we analyzed, we weren't able to find any correlation with suicides per 100k population - with more significant data such as household income, poverty areas, etc. we assume we would be able to find some correlations.
* The suicides per 100k population started growing significantly in 1989 and peaked at 1995 - there has been a slight decline in suicide rates ever since.
* Our regression models did not offer significant insight on any possible correlation.