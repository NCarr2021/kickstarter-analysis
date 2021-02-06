# Module 1 Challenge – Kickstarting with Excel

## Overview of Project

# Louise’s play Fever came close to its fundraising goal in a short time. She wants to know how different campaigns fared in relation to their launch dates and funding goals. Using knowledge of Excel (filters, conditional formatting, pivot tables/pivot charts) analyze the Kickstarter data set.

### Purpose

# Analyze launch dates and funding goals and present Louise with deliverables specific for Theater campaigns that includes visual charts and a report to identify how campaigns did with funding goals and launch dates.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The Theater campaign is the most successful overall with the best months in May (111), June (100), July (87), August (72) but can also include October (65). December is the worst month to launch any theater productions. 

![Theater_Outcomes_vs_Launch
(https://github.com/NCarr2021/kickstarter-analysis)

### Analysis of Outcomes Based on Goals

Overall, the most successful campaigns at 76% are those with goals less than $1000. Second most successful at 73% with goals between $1,000-$4,999. Campaigns with goals $5,000-$9,999 were successful only 55% of the time with goals $10,000-$14,999 at 54% of the time. The least successful two campaigns at 17% had goals greater than %50,000. A campaign with $45,000-$49,999 failed completely at 100%.

![Outcomes_vs_Goals]
(https://github.com/NCarr2021/kickstarter-analysis)

 ### Challenges and Difficulties 

Ensuring that the individual pledged amounts for the Outcomes Based on Goals worksheet/pivot chart included all required Successful-Failed-Canceled ‘plays’ from the data worksheet. The sum of the column and results of COUNTIF were mismatched. Corrected by reviewing the functions and correcting conditions (missed using the = in some. 

=COUNTIFS(Kickstarter!$F:$F,"=failed",Kickstarter!$D:$D,">**=**1000",Kickstarter!$D:$D,"<=

Getting pivot chart for Outcomes Based on Goals y/x axis to display properly. Corrected by changing the axis options bounds/units.

![axisbounds]
(https://github.com/NCarr2021/kickstarter-analysis)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

-  Different times of the year impact success. The most successful campaigns occur in May, June, July and August which are summer months. This can be due to more outside activity in the warmer weather. Summer months don’t guarantee a successful campaign since there are other successes throughout the year with the highest in October, February and April.  

-	Lower goals have better chance of success. Availability of outside venues to reduce cost whereas indoor venues during the winter months would be more costly with a higher goal.

- What can you conclude about the Outcomes based on Goals?

Campaigns with funding goals less than $1,000 or $5,000 succeed. A smaller goal implies less backers are required. Smaller goals also imply less cost for supplies (less required, others reused) or venues with varying costs for indoor vs. outdoor. Based on the chart, campaigns over $20,000 tend to fail possible due to the large goal and a limited number of backers that can afford to donate larger sums.

- What are some limitations of this dataset?

Data set is a broad range. It’s measuring theater/plays within a broad measurement area, the US vs. individual states or regions. With additional data such as city or state, outcomes can be narrowed to a specific area and include other campaign types. Data for backer type whereas regular donators support a success. Include and additional subcategory to identify genre like for theater/plays.

- What are some other possible tables and/or graphs that we could create?

Table or graph for each outcome, drill down further in the goal range for example the $1000 to $5000 range to further identify the specific goal amounts and the impact. Table or graph to include backers, goal and pledged to identify any link to monies.


Location of README https://github.com/NCarr2021/kickstarter-analysis
