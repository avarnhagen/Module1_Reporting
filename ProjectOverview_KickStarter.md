# **Kickstarting with _Excel_**

## Overview of Project
 The Vanderbilt University Data Analytics Bootcamp is a streamlined coursework pipeline that exposes students to a broad set of technical applications and data management concepts, strengthening their problem solving skills in data-driven contexts. Module 1 of the program focuses on Microsoft Excel, the use of statistical measures of spread, pivot tables, formulas, conditional formatting, and data visualization with charts, culminating with the case study detailed herein.  

### Purpose
Artistic productions face the challenge of budgets and time constraints, moderating the frequency of campaign success (i.e. productions that make it to audiences) and increasing the likelihood of failure or cancellation.  This analysis, performed on behalf of our client, Louise, sets out to unearth patterns explaining campaign success and failure, with an emphasis on theatre productions (more specifically, plays), assessing what corrective feedback can be provided. Only $2,485 of the goal of $2,885 were met for the fundraiser for her play, **_Fever_**, in the given four week timeframe, leading to campaign failure. 
## Analysis and Challenges

The dataset, held in a Microsoft Excel Workbook, detailed 4,114 campaigns taking place from 2009 to 2017 and recorded the following data for each:
 
<div style="text-align:center"><img src="Resources/DataTypes.png" alt="your alt text" width="250"/>
<div style="text-align:left">


The mix of categorical and numerical data yields the opportunity to correlate campaign outcomes with both fundamental aspects of fundraising structure  (goal funds raised, total amount pledged, start date, end date ) and more tangential factors (location of project by country, number of campaign contributors).  Comparisons across project type (theatre, film/video, photography) and subtype (plays, musical, drama, documentary, television) lay the groundwork for inter-industry, intra-industry, inter-country, and intra-country comparison of campaign fundraising patterns.  

The course framework advises pinpointing the analysis in ways that will help Louise most directly, as well as emphasizing the role campaign **launch date** had in campaign outcomes for the purpose of helping Louise, as well as the role of campaign **funding goals**.

### Analysis of Outcomes Based on Launch Date

Compare total number successes across any given month

Percentage success/failure or cancel for any given month


<img src="Resources/Theater_Outcomes_vs_Launch.png" alt="your alt text" width="600"/>

### Analysis of Outcomes Based on Goals



<img src="Resources/Outcomes_vs_Goals.png" alt="your alt text" width="1000"/>



### Challenges and Difficulties Encountered


## Results

- What are conclusions you can draw about the Outcomes based on Launch Date?

With mean number of campaign successes in any given campaign month of 70, successful campaigns most frequently began in May (111), June (100) and July (87), with 67%, 65%, and 63% of all campaigns started in those months suceeding, respectively.   Likewise, May (33%), June (35%), and July (37%) were the least likely to yield either cancellation or failure by percentage.  With the p-value <0.05 (0.0495), t-test results suggest that the average success rate of campgaigns beggining in the summer is higher than that of those beginning in the fall, winter, or spring.  


This trend of success for campaigns beginning in the summer months was not as pronounced in 2016. The year of **_Fever's_** campaign, 2016, KickStarter campaigns beginnning in July (83%), April (76%), and August (71%),  were most likely to succeed. Campaigns that began in June of 2016 were the third least likely to succeed of any given month that year, with at only a 51% success rate, preceded by September (50%) and December (41%).  Moreover, June 2016 had the lowest success rate of any summer month in the data set for theatre campaigns, or the 18th percentile of success rate for a campaign start date of any given month in the dataset (z=-.1.39). 

Across all years, campaigns for _plays_ (**_Fever's_** subcategorization) begun in June, like Fever, were most likely to succeed, but in 2016 only 59% of KickStarter's begun that month succeeded, the third lowest of any month of campaign starts that year.


- What can you conclude about the Outcomes based on Goals?


- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
