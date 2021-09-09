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

Before begining, we filtered out all constituents who were not alumni of the college as the focus of our research was on the engagement of alumni. Afterwards, we noticed the donation amount distribution was heavily right-skewed (Figure 1.), so we filtered out gifts above the 99th percentile ($5000). Finally, we filtered out reocurring gifts (such as monthly $5 donations). The table below lists the definitions of the different segments analyzed. 


<figure>
    <a href="/assets/img/Donor_Poster_1.png"><img src="/assets/img/Donor_Poster_2.png"></a>
     <figcaption> Table 1. Description of the variables that were used. </figcaption>
</figure>

# Methods 

To explore our data we used the Kruskal-Wallis and the Wilcoxon-Mann-Whitney tests to determine whether there were significant differences in the median donation amounts among the different segments within the affiliation, leadership, and loyalty groupings. Additionally, we split the number of email messages received by constituents into brackets of 20 messages and used the Kruskal-Wallis test to determine whether there was a significant  difference in median donation amounts among the different message brackets. Because the donation amount was not normally distributed (Figure 1.), testing for a difference in medians was more appropriate than testing for a difference in means.

Logistic regression was also used to analyze the relationship between donors unsubscribing and the number of messages received, the number of messages clicked, the loyalty status of the donor, and the amount the individual donated to determine how St. Olaf Advancement should adapt their email communication strategy. The logistic regression in Figure 2 has been altered to show probability. The trend lines show the probability a constituent will unsubscribe from the mailing list based on the number of messages they have received.

# Results 

Using the Kruskal-Wallis test, we found a significant difference in the median giving amounts of the affiliation groups (H = 444.65, p-value < 0.001), the loyalty groups (H = 117.4, p-value < 0.001), and the message groups (H = 198.78, p-value < 0.001). Using the Wilcoxon-Mann-Whitney test, we found a significant difference in the median giving amounts of the two leadership groups (W = 421638, p < 0.001). 


<figure>
    <a href="/assets/img/Donor_Poster_3.png"><img src="/assets/img/Donor_Poster_3.png"></a>
     <figcaption> Figure 1. The skewed distribution of donoation amounts from Alumni. </figcaption>
</figure>




<figure>
    <a href="/assets/img/Donor_Poster_4.png"><img src="/assets/img/Donor_Poster_4.png"></a>
     <figcaption> Figure 2. A line graph demonstrating the probability that a constituent within a given loyalty segment unsubscribes from the email list. 
     </figcaption>
</figure> 



<figure>
    <a href="/assets/img/Donor_Poster_5.png"><img src="/assets/img/Donor_Poster_5.png"></a>
     <figcaption> Figure 2. The average donation amount of constituents for each message bracket and leadership segment. 
     </figcaption> 
</figure> 

