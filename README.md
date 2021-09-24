# An Analysis of Kickstarter Campaigns
## Overview of the Project:
This report provides an analysis of Kickstarter campaign data to uncover any hidden trends. Using EXCEL as an analyzes tool, to provide the client with some insights and statistical measures, to identify the variables that influence campaign performance. Pivot tables and pivot charts are used to display results as well as some descriptive statistics. 
### Purpose:
The client's plan is to establish a Kickstarter campaign for her plays, _Fever_, with an estimated goal of $12,000, so the main purpose of this analysis is to determine the impact of goals and launch date on campaign outcomes. 
## Analysis and Challenges:
To provide Louise with general picture about the performance of Kickstarter campaigns, we perform descriptive statistics for campaigns performance filter by country. The initial shows that the total number of Kickstarter campaigns is just over 4,000.  Figure (1) show the number of campaigns in US is adjusted to 3,038.  In Great Britain there were 525 successful theater Kickstarters, while there are only a total of 604 Kickstarter campaigns for plays in Great Britain, the "theater" category is the most successful campaign. Based on these statistics[GitHub Pages]( https://github.com/intisarkhalil/kickstarter-analysis.git), we can determine the following:

    - The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.
    - The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.
    - Some large values are driving all these distributions. 
    - The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR.
    - There must be some failed Kickstarters with really high goals!
The specific goals can be determined through following two challenges:
  ### Analysis of Outcomes based on launch date:
Figure (2) shows that the month that launched the most successful Kickstarter campaigns was May. However, January, June, July and October all had roughly the same number of failed campaigns launched. 
Figure (2): Date Created Conversion
 ![Date created Conversion Chart](https://user-images.githubusercontent.com/62036983/134721115-fd0ac411-2646-4d7a-b7bd-20dc20a12d2a.png)

To provide information about the influence of launch date on the campaign’s outcomes, the following figure (3) [GitHub Pages](https://github.com/intisarkhalil/kickstarter-analysis.git) is constructed.
   ### Analysis of Outcomes based on goals:
Descriptive statistics table [GitHub Page](https://github.com/intisarkhalil/kickstarter-analysis.git) allows us to determine a few things. For one, failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns. Louise is asking for more than twice the average successful Kickstarter goal, so this isn't great news for her campaign. In addition, the mean and median pledged amounts are much lower than the successful pledges, which indicates that failed Kickstarter campaigns are unsuccessful for reasons other than asking for too much money. In other words, if the failed projects were also getting a median pledge amount of around $3,000, it's possible that those that failed just asked for too high of a price. Since the median is much lower, there must be another factor keeping people from pledging to those unsuccessful projects. 
Figure (1): Parent Category Outcome
 ![Parent Category Chart](https://user-images.githubusercontent.com/62036983/134721181-5b54fdc8-96bd-4b67-a00a-0ace96df3cda.png)

To provide information about the influence of goal on the campaign’s outcomes, the following figure (4) [GitHub Pages](https://github.com/intisarkhalil/kickstarter-analysis.git) is constructed.
### Challenges and Deficulties Encountred:

- Create average donation column
- Create Percentage Funded
- Create year column 
- We found (#DIV/0) error in the average donation column, so we use the IFFERROR function to correct it. 
- Create the Subcategories column: splitting the Category and Subcategory column into two distinct columns: "Parent category" and "Subcategory." This gives us additional data to use in our analysis.

## Results: 
- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - The month that launched the most successful Kickstarter campaigns was May.
    - While December is the least successful Kickstarter’s month.
- What can you conclude about the Outcomes based on Goals?
    - Failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns 
- What are some limitations of this dataset?
    - Some information needs to be converted 
    - The data out of date, Louise may consider a more recent data.
    - Louise provides less information about her upcoming campaign. 
    - Outliers in the data may affecting the results accuracy significantly.
- What are some other possible tables and/or graphs that we could create?
    - It’s possible to break down theater parent category based on number of backers for each county filtered by plays.
    - It’s possible to break down the outcomes based on goals charts for each country.
