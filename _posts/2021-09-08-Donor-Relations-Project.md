---
layout: post
title:  "Constituent Behavior Associated with College Giving"
date:   2021-05-02
category: Data Science 
excerpt: " A Data Science Exploration Project on decision making and behavior of donors. " 
feature: https://cdn.mos.cms.futurecdn.net/MCTaifsDFHvU7pJ9uKmjzY.jpg 
---  

# Introduction 

Many Colleges acrooss the U.S. are concerned about donors. However, while donor acquisition efforts are important, donor retention efforts have the ability to greatly increase
the amount of giving to an organization (Sargeant). The frequency of communication with constituents has shown the potential to affect a donors' decision to continue giving  to an organization (Deitz and Kellet).


For this project, we used data from a small liberal arts college and were interested in understanding the behavior of the donors for a particular college, specifically how
constituent' giving is affected by email communications. After an increase in email communications due to the COVID-19 pandemic, a leading question was how much email communication is too much? In our research, we used data from St. Olaf College Advancement's gift database and email database to examine donor engagement and behavior. We narrowed our data to focus just on alumni donations. The data used for the project was from St. Olaf's fiscal year 2020 (June 2019 - May 2020). 

# Data 

<figure>
    <a href="/assets/img/Donor_Poster_1.png"><img src="/assets/img/Donor_Poster_1.png"></a>
    <figcaption> </figcaption>
</figure>

Before begining, we filtered out all constituents who were not alumni of the college as the focus of our research was on the engagement of alumni. Afterwards, we noticed the donation amount distribution was heavily right-skewed (Figure 1), so we filtered out gifts above the 99th percentile ($5000). Finally, we filtered out reocurring gifts (such as monthly $5 donations). The table below lists the definitions of the different segments analyzed. 


<figure>
    <a href="/assets/img/Donor_Poster_1.png"><img src="/assets/img/Donor_Poster_2.png"></a>
     <figcaption> Table 1. Description of the variables that were used. </figcaption>
</figure>


