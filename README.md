# An Exploratory Analysis of Kickstarter Theater Plays Campaigns

## Overview
With the goal of providing insights for a playwright who wanted to start a kickstarter campaign, a dataset containing information on Kickstarter projects launched from 2009 to 2017 was analyzed.

### Purpose
Identify patterns of successful and failed kickstarter theater plays campaigns.

## Analysis and Challenges
Two main exploratory analyses were performed. First, it was examined whether the outcomes of theater projects varied according to the month the projects were launched. Second, it was examined whether the percentage of successful and failed theater plays campaigns varied by the projects’ funding goals.

### Analysis of Outcomes Based on Launch Date
From 2009 to 2017, there were a total of 1,393 Kickstarter theater campaigns and the majority of them (60%) had successful outcomes. Looking into all years together (See Chart 1), the number of failed and canceled theater campaigns is roughly constant across the months the campaigns were launched. The number of successful theater campaigns, however, seems to vary according to the launch date. Specifically, there are a greater number of successful theater campaigns in May and June, and a smaller number of successful theater campaigns in December, compared to the rest of the year.

Chart 1
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/89421440/138539954-bd12c9ea-249d-4395-bc81-86d448ceb928.png)

### Analysis of Outcomes Based on Goals
From 2009 to 2017, the overall percentage of successful, failed  and canceled theater plays campaigns were 66%, 34% and 0%, respectively. By taking into account the campaigns’ initial funding goals, these percentages were broken down as showed in Chart 2. While the percentage of canceled campaigns remains constant across values, the percentages of successful and failed theater plays campaigns varies by goal amount in an intricate pattern. From Chart 2, it appears that campaigns with smaller goals (less than $5,000) are more likely to succeed and campaigns with higher goals (greater than 45,000) are more likely to fail. That seems like a direct relation between campaigns’ outcomes and goals.

Chart 2 also indicates that there may be an indirect relation between campaigns’ outcomes and goals when values are not at the extremes. From $5,000 to $20,000, campaigns seem to have the same chance of failing or succeeding. From $25,000 to $35,000, campaigns seem to have higher chance of failing. From 35,000 to 45,000, campaigns seem to be more likely to succeed. These differences if statically significant cannot be explained only the campaigns’ goals. There are probably other variables mediating the relationship between outcomes and goals.

Chart 2
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89421440/138539937-fb512bcc-e26e-4896-b064-ba505e4e8599.png)

### Challenges
The analysis presented here is limited as they are exploratory analysis and do not include statistical testing. The apparent effects of launch date and goals on outcomes identified in Chart 1 and 2, respectively, may not be statically significant. Therefore, the analysis presented here, although insightful, should be interpreted carefully.

## Results
- There are two main conclusions that can be drawn about the theater campaigns’ outcomes based on their launch date. First, new theater campaigns should aim at launching their projects at the middle of the year as there was an increase in successful outcomes in these months, especially May and June. Second, new theater campaigns should avoid launching their projects at the end of the year as there was a decrease in successful projects in these months, in particular in December.
- There is one main conclusion that can be drawn about the theater campaigns’ outcomes based on their goals: new theater plays campaigns should aim at setting low funding goals as the rate of successful is higher for goals at the lower end (especially those less than $5,000). 
- Note that the dataset is not up to date and patterns showed here for Kickstarter theater projects may have changed since 2017, especially with a pandemic in place since early 2020.
- Further analysis could examine: a) the impact of launch date on outcomes for all Kickstarter project categories. If the results presented here are confirmed for the whole dataset, it will it strength the notion that with respect to launch dates the middle of the year should be preferred and that the end of the year should be avoided for launch dates. b) if campaigns with successful outcomes and smaller goals, e.g. those with goals lower than $5,000, tend to end up with a pledged amount that surpass the initial goal. This analysis has the potential to strength the notion that new Kickstarter theater plays campaigns should aim at setting small funding goals.
