# Kickstarting with Excel


## Overview of Project

Louise's play "_Fever_" came close to reaching its fundraising target. She now wanted to know how certain campaigns fared in terms of their debut dates and financial targets. I presented the campaign outcomes based on their launch dates and financial targets using the Kickstarter dataset below that I looked through.
To visualize my findings, I used a PivotTable and a line chart.

### Purpose

The goal is to look at how Louise's play "Fever" relates to the different campaigns, as well as the monthly trend in Project Launch Dates throughout time. Whether or not the "Launch Date" & "Funding Goals" are relevant, and whether they influence the project's Outcome - "Successful," "Failed," or "Canceled." 


## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

Considering Louise was interested in examining the influence of the Play's Launch Date, the data was sorted by Category "theatre" and the results were structured by Months for all of the campaigns over the years.

![Theater Outcomes vs Launch](/kickstarter-analysis/resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

From the second analysis basis the funding Goals, the data was filtered by Subcategory "Plays" amd presented "Successful" and "Failed" Outcomes in percentage over the Range of Funding Goals Category.

![Outcomes vs Goals](/kickstarter-analysis/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

The first problem I ran into was reading UNIX timestamps and converting them to real dates. 
The second challenge was determining whether the **COUNTIFS** range would contain the value of the intervals or not. Then verified the data that there are no Canceled Plays existed.
Everything became much easier to plot line charts and analyze how the launch date and funding goals were related to the success of the plays once I had solved the challenges.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The conlusion determined is that the launch dates funding amounts influences the successful outcome of the campaigns.

2. As per the analyis of Theater Outcomes vs Launch Date, around the globe campaigns launched in May had the greater success rate than the ones launched in December. The success rate decreased gradually from May till December with a little bump in October.

- What can you conclude about the Outcomes based on Goals?

There were more "Successful" Outcomes as compared to the "Failed" Outcomes with funding Goals below $10,000 or between $35,000 - $45,000.

- What are some limitations of this dataset?

The data layout the countries and the outcomes of the campaigns, but it limits the states/regions within the country where the campaigns are "Successful", "Failed" or "Canceled". It could help Loiuse to figure out specific region to Launch to have a better change of getting funded and be successful.

- What are some other possible tables and/or graphs that we could create?

    - We could create a graph presenting which Country has better success rate than others.
    - Country wise break-up of the Number of Backers for the successful campaigns.
    ![Number_of_Backers](/kickstarter-analysis/resources/Number_of_Backers.png)
    - In which country Plays are more Successful.
    
    ![Countrywise_outcomes](/kickstarter-analysis/resources/Countrywise_outcomes.png)

    