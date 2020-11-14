# kickstarter-analysis


# Kickstarting with Excel
Completed Analysis Excel File: [Kickstarter_Challenge](https://github.com/aimeeyen/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)

## Overview of Project
Performing analysis on Kickstarter dataset to uncover trends and discover findings on key factors in determinig a successful campaign in "Plays" subcategory. 

### Purpose

Provide visualization of dataset and drilled insight from data to better understand which key factors contribute the success of fundraising. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://github.com/aimeeyen/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
 - Highest performning month: May (Memorial and Mother's day) Also Feburary (Valentine)
 - Decline in success rate during School break: Spring, Summer, and Winter Break
 - Deline in success rate during Holiday season: 4th of July, Thanksgiving and Christmas
 - Low performing month Nov-Dec, maybe signifiy lower purchasing power during Holiday seasons
 - The two variance Failed and Successful Outcomes, are in positive correlation. 

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://github.com/aimeeyen/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
   
####   
Having some difficulties with code/excel formula. Googles some answer from different site and watched few videos on *(Countifs)* While working on compiling Outcome vs goal dataset *(Countifs)*, total count of campaigns did not add up, after few data validation concluded that the formula wasn't working or it's outputting bad data. 

After hours of trying to fix the code, debugging, redoing the exericse, *thinking* the possiblity of data corruption. Then, went back to the Kickstart dataset to re-examine the raw data and clear any filter and resetting the data, found out that **"freeze panes"** was on, it somehow interfered with filtered "outcome" and produced bad result. After the "unfreeze panes", total count adds up. Phew, it was a :relieved: relief and a sense of accomplishment and tiny boost of confidence :smirk: 

Despite the challenges, it was a great learning to make sure data are clean/cleared and not in "freeze pane" in order for filter to work properly. This debugging process somehow made me believe in my ability to resolve issues at hand, just put in the time/effort to backtrack your steps. 
   
# Results

### - What are two conclusions you can draw about the Outcomes based on Launch Date?


   - :white_check_mark: Summer season: May and June is the ***best*** time to launch campaign

   - :x: Winter season: Dec - Feb is the ***worst*** time to launch campaign and in Jan has the ***highest*** canceled campaigns

   - Both Failed and Successful campaign have positive correlations, signify that both variable were affected equally by the time of launch date, such as School break or Holiday season. 


### - What can you conclude about the Outcomes based on Goals?

   
   - :white_check_mark: :heavy_dollar_sign: Goal less than $5000 and between $35K to $44.9K shown the ***highest*** success rate


   - :x: :heavy_dollar_sign: Goal between $45K and above have the ***lowest*** success rate


![Descriptive Statistics](https://github.com/aimeeyen/kickstarter-analysis/blob/main/Descriptive%20Statistics.png)

  1. On setting Goals: Successful campaign, it's more **symmetic** distribution IQR vs Standard Deviation ($3,500 vs $7,749).
  2. On setting Goals: Failed campaign, data distriution is **skewed**. IQR are rougly 3 times the Standard Deviation ($8,000 vs. $21,968) signify really high unmet goals.
  3. On Successful Campaign's Mean Pledge are **closely aligned** with its Mean Goal ($5,602 vs $5,049)
  4. On Failed Campaign's Mean Pledge are **far from** its Mean Goal ($559 vs $10,554)

### - What are some limitations of this dataset?
  
   - Do not have duration/length of the campaign period. To detmerine if longer or shorter fundraising campaigns resulted in positive or negative effect towards pledge outcome. And if it's favorable towards **holiday** season, to host shorter fundraising campaign to achieve desirable outcome as per "Theater Outcome Based on Launch Date" chart depicted a sigificant decline in success rate during Spring Break, Summer Break and also Holiday seasons: 4th of July, Thanksgiving, and Christmas. 

### - What are some other possible tables and/or graphs that we could create?
   - Chart of total duration (days) of Successful and Failed campaign vs launch date. Also it will be insightful visualization to draw conculsion on any correlation between Goal, Pledge outcome, vs duration of the campaign during Holiday season or school break. 
   - Create above chart for different countries to discover any trends or best period to launch particular campaign per region
   - "Spotlight" column data and "Staff Pick" vs "Outcome" to see if there's any correlation towards a successful campaign

## Conclusion: 
A campaign's goal setting and launch date/duration *maybe* a key factor in promoting successful and efficient campaign: allocating proper resources, labors, marketing targeted audiances, forecast/manage cost in the duration of the campaign. And moreover, avoid Holiday season when majority of population are out of town. 
