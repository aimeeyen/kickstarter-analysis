# kickstarter-analysis


# Kickstarting with Excel
Downloadable link: [Kickstarter_Challenge](https://github.com/aimeeyen/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)

## Overview of Project
Performing analysis on Kickstarter dataset to uncover trends 

### Purpose
Provide visualization of dataset and drilled insight to better understand key factors in launching successful campaign

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/aimeeyen/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://github.com/aimeeyen/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
    While working throught some excel formulas -(Countifs)-, total count of campaign doesn't add up. After an hour trying to fix my code, redoing the exericse, thinking about possiblity of data corruption. Then went back to the Kickstart dataset, found out that "freeze panes" was on, it interfered with filter and the formulat. After removing the "unfreeze panes" the total count of Goal range add up.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
 
    -:white_check_mark::date: Summer season: May and June is the ***best*** time to launch campaign.

    -:x: :date:               Winter season: Dec - Feb has the ***worst*** time to launched campaign.  


- What can you conclude about the Outcomes based on Goals?

    -:white_check_mark: :heavy_dollar_sign: Goal less than $5000 and between $35K to $44.9K shown the ***highest*** success rate

    -:x: :heavy_dollar_sign: Goal between $45K and above have the ***lowest*** success rate


- What are some limitations of this dataset?
 
 
Do not have duration/length of the campaign period. To detmerine if longer or shorter campasign based on data created date and end date place a significant factor to achieve desired outcome


- What are some other possible tables and/or graphs that we could create?
   Chart of total duration of Successful and Failed campgaign, with scatter chart around season or during times when 


On setting Goals: Successful campaign, it's more symmetic distribution IQR vs Standard Deviation ($3,500 vs $7,749).
On setting Goals: Failed campaign, data distriution is skewed. IQR are rougly 3 times the Standard Deviation ($8,000 vs. $21,968) signify really high unmet goals.
On Successful Campaign's Mean Pledge are closely aligned with its Mean Goal ($5,602 vs $5,049)
On Failed Campaign's Mean Pledge are far from its Mean Goal ($559 vs $10,554)
Conclusion: A campaign's goal setting and launch date/duration maybe a key factor in promoting successful and efficient campaign: allocating proper resources, labors, marketing targeted audiances, forecast/manage cost in the duration of the campaign.
