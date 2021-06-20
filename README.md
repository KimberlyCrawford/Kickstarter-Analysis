# Analysis of Kickstarting Campaigns using Excel
A Kickstarter analysis to uncover trends and patterns for successful campaigns.

## Overview of Project
An upcoming playwrite wants to launch a Kickstarter campaign to fund the play "FEVER" with a $10,000 budget and needs insight to plan the campaign and set it up for success. Kickstarter is a crowdfunding platform available to fund creative projects. For more information, visit https://www.kickstarter.com/about. 

### Purpose
The purpose of this project is to determine if there are specific factors that make a crowdfunding campaign successful or not. Analyzing an Excel dataset of over 4,000 crowdfunding campaigns and data can help a client gain a greater understanding of campaigns from start to finish and allow the client to set the campaign to mirror successful ones in the same category.

## Analysis and Challenges
The overview of the analysis is well described with screenshots (2 pt). Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered. Challenges or difficulties that were encountered, and how they were overcome, are well explained. If there were no difficulties, describe any possible challenges or difficulties that could be encountered (2 pt).

Using Excel; the data was organized, sorted and filtered specifically for “theater” categories and “play” subcategories. Color-coded conditional formatting was applied to the dataset to easily distinguish between four outcomes: Successful, Failed, Canceled, and Live. Goals and pledged columns were sorted to research projects with similar budgets. Data was filtered and pivot tables were generated to get a refined review of the data. Summary statistics were calculated and interpreted.

### Analysis of Outcomes Based on Launch Date
https://github.com/KimberlyCrawford/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals
Chart here

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the above "Outcomes Based on Launch Date" chart, two conclusions can be made: (1) A trend of outcomes based on launch date in months revealing higher success rates than failed or cancelled. (2) A greater success rate of campaigns were held during the months of May and June with May being the highest. However; you will also notice January, June, July and October all had roughly the same number of failed campaigns launched.

- What can you conclude about the Outcomes based on Goals?
One conclusion is made about the Outcomes based on Goals (2 pt).

- What are some limitations of this dataset?
There is a summary of the limitations of the dataset, and there is a 

- What are some other possible tables and/or graphs that we could create?
recommendation for additional tables or graphs (2 pt).



 
Notes from Practice
## Findings:
Out of the 4,114 observed crowdfunding campaigns; 53% were successful, 37% failed, 8% were cancelled, and 1% were live. Out of the successful campaigns, theater accounted for the highest percentage at 38% compared to the rest of the parent categories.  In the subcategory for plays, 65% were successful while only 33% failed. In the United States campaigns, there were 525 successful theater Kickstarters. Goals and pledged columns were sorted to research projects with similar budgets around $12K. The data was filtered to reveal all theater/play campaigns with budgets ranging from $11K - $13K which results in 18 campaigns of which 50% were successful and 50% failed. Out of the failed campaigns, a majority did not even receive 25% of the campaign goal.

The below bar chart compares the number of outcomes for each parent category and reveals which categories did well and which ones did not:
![Parent Category Outcomes](https://user-images.githubusercontent.com/85641229/122625466-e1e62800-d06a-11eb-9f69-82393758f25e.png)

The below bar chart compares the number of outcomes for each subcategory within the “theater” category and reveals there are only a total of 604 Kickstarter campaigns for plays in Great Britain; however, out of those, the "theater" category is the most successful.
![Subcategory Outcomes](https://user-images.githubusercontent.com/85641229/122625482-f1fe0780-d06a-11eb-819d-71b4de652947.png)

Based on the “Descriptive Statistics” sheet that compares measures of central tendency for successful versus failed campaigns, we can determine the following:
*	The mean of each distribution is around the 3rd quartile, so the data follows similar distributions in each subset.
*	The standard deviations are larger than the mean, which means everything below the mean is considered "close" to the center.
*	Some large values are driving all of these distributions. The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. There must be some failed Kickstarters with really high goals.
	 
The below Box and Whiskers chart shows the distribution of campaign goals and the distribution of total amounts pledged for plays in Great Britain. We can see that the mean campaign goal is around £4,000. This is outside of the range of outliers for amount pledged, so Louise should probably try to get her play produced for less than £4,000. Half of the campaign goals are less than £2,000, which is just over the 3rd quartile for amounts pledged.
![Goals_versus_pledged_Great_Britain_Musicals](https://user-images.githubusercontent.com/85641229/122625502-0b9f4f00-d06b-11eb-8be1-42bd33b5d6c0.png)

## Recommendations:
Based on the above findings, the following actions are recommended: 
* A thorough review of the filtered successful and failed campaigns around the same budget should be performed to see if there is a correlation between the type of plays that were successful compared to those that failed.
* Failed Kickstarter campaigns have much higher fundraising goals than successful Kickstarter campaigns. Based on the visuals and statistics above, Louise is asking for more than twice the average successful Kickstarter goal and should try to get her play produced for less than £4,000. Half of the campaign goals are less than £2,000, which is just over the 3rd quartile for amounts pledged.

