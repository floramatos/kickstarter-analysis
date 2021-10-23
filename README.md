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
From 2009 to 2017, the overall percentage of successful, failed  and canceled theater plays campaigns were 66%, 34% and 0%, respectively. By taking into account the campaigns’ initial funding goals, these percentages were broken down as showed in Chart 2. While the percentage of canceled campaigns remains constant across values, the percentages of successful and failed theater plays campaigns varies by goal amount in an intricate pattern. From Chart 2, it appears that campaigns with smaller goals (less than 5,000) are more likely to succeed and campaigns with higher goals (greater than 45,000) are more likely to fail. That seems like a direct relation between campaigns’ outcomes and goals.

Chart 2 also indicates that there may be an indirect relation between campaigns’ outcomes and goals when values are not at the extremes. From 5,000 to 20,000, campaigns seem to have the same chance of failing or succeeding. From 25,000 to 35,000, campaigns seem to have higher chance of failing. From 35,000 to 45,000, campaigns seem to be more likely to succeed. These differences if statically significant cannot be explained only the campaigns’ goals. There are probably other variables mediating the relationship between outcomes and goals.

Chart 2
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89421440/138539937-fb512bcc-e26e-4896-b064-ba505e4e8599.png)
