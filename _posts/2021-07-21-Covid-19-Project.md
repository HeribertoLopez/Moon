---
layout: post
title:  "Covid-19 and Vaccinations"
date:   2021-07-20
excerpt: " A data visualization project."
feature: https://images.moneycontrol.com/static-mcnews/2021/04/shutterstock_1624415920-770x433.jpg
comments: true
--- 

# Introduction 

COVID-19 is a type of coronavirus that possesses high rates of transmissibility among the human population.
For this research project, we investigated how COVID-19 cases change at varying degrees of vaccination rates from a global, country, and state-level perspective.
Our purpose was to identify the percentage of people vaccinated needed to begin to see a drop in cases.
A variant of the virus,  *Delta*, has recently been reported as having a higher rate of transmissibility among vaccinated and non-vaccinated individuals alike.
Previous research has shown that receiving two doses of the Pfizer mrna vaccine is highly effective across age groups greater than 16 years of age and in preventing symptomatic and asymptomatic SARS-CoV-2 infections. 
Moreover, the findings suggest that COVID-19 vaccination can help to control the pandemic. 
After gathering data for new covid cases, we analyzed how these cases respond to vaccination rates and drew conclusions from our findings.  

# Guiding Questions: 

- At what percentage of vaccinations do we begin to see a drop in cases? 
- How many weeks should we see a decline for the drop in cases to be attributed to vaccinations? 

# Data and Methods  

For this project, we used data from the our world in data database on github.  [Data on Covid-19 by *Our World in Data*](https://github.com/owid/covid-19-data/tree/master/public/data). As well as, data from the [*New York Times*](https://github.com/nytimes/covid-19-data). From the the *Our World in Data* dataset, we choose to use the following variables: location, population, date, new_cases, new_deaths, people_fully_vaccinated, and people_vaccinated. The dataset from the *New York Times* was used mainly to look at states in the United States. From the *New York Times* dataset, we choose the following variables:  date, cases, cases_avg_per_100k, deaths, deaths_avg_per_100k, people_fully_vaccinated, people_fully_vaccinated_per_hundred, people_vaccinated, people_vaccinated_per_hundred). Note that in both datasets, people_vaccinated refers to those that have received only one dose, and people_fully vaccinated refers to those that have received both doses or a single shot of a single dose vaccine. For our analysis of the data, we decided to create plots using shiny in R and estimate categorized cases and vaccinations by week, plotted change in weekly cases over amd weekly vaccinations over time and searched for trends and patterns within our plots. Additonally, we plotted new weekly cases vs. weekly vaccinations. 







# 

