# Kickstarting with Excel

## Overview of Project
The project encompasses analysis of data related to Kickstarter campaigns to help Louise make decisions on future Kickstarter campaigns

### Purpose
Louise has run some Kickstarter campaigns in the past and she is looking to understand how campaigns have performed with respect to their launch dates and outcomes of the campaigns. We will comb through the data to help provide Louise with insights on the campaign performance.

## Analysis and Challenges
The analysis was to slice and dice the data using the columns that were in the Excel file. We created pivot tables and pivot charts to understand how kickstarter campaigns within the category 'Theatre' performed based on the month that the campaign was launched in and also conducted analysis to understand how the campaigns within the subcategory 'Plays' performed based on the goals that were set. 

### Analysis of Outcomes Based on Launch Date
As mentioned in the overview, the analysis of outcomes based on Launch date was conducted using the data filtered for the category 'Theatre' and created a pivot table to chart the campaign count against the month of the launch date. The screenshot of the pivot chart is pasted below. 

![Theatre_Outcomes_vs_Launch_date](https://github.com/dkatragadda/kickstarter-analysis/blob/main/Resources/Theatre_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The outcomes based on Goals was conducted using the COUNTIFS function in excel to identify the number of campaigns that were successful, failed or canceled within the subcategory 'Plays' based on the ranges defined on the Goals. 

![Outcomes_Based_on_Goals](https://github.com/dkatragadda/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The dataset used has given us direction on the trends for the campaign data. Some possible challenges that could be encountered with the dataset is to dive deeper into the data within the subcategory 'Plays' and identify more attributes that can be an indicator of success such as backer profiles etc. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The most successful campaigns were launched in the month of May and the trend for successful campaigns was on a downward trajectory and had the least successful campaigns in the month of December.
2. The total number of successful campaigns (839) outweighed the number of failed campaigns (493) based on the dataset

- What can you conclude about the Outcomes based on Goals?
1. The probability of success outweighs the probability of failure if the goal of the campaign is under $15000 and the lower the goal, the higher the probability of success. 

- What are some limitations of this dataset?
1. This dataset does not include certain information regarding the demographics of the backers
2. This dataset does not include the States or the regions within the country where the campaigns were successful. This would help in deciding where to target the campaigns. 
3. This dataset does not include information on the quality of the plays in the campaigns i.e. if the plays are by successful and reputed production houses etc. 

- What are some other possible tables and/or graphs that we could create?
1. We can create charts based on the metrics related to the backers including average donation per campaign.
2. We can look at other charts based on the following metrics: Spotlight, Staff pick, length of campaign, backer count etc.
