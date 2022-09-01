# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis was to provide the client Louise more information how other Kickstarter campaigns fared. Louise was specifically interested in the outcome of play campaigns with respect to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I conducted of the outcome of theater productions by creating a pivot table. I used parent categories and years as filters. I used month data as the axis. I used count of outcomes as the values and outcomes as the legend. 

### Analysis of Outcomes Based on Goals
I conducted an outcome of plays based on their goal amount by using a countifs function (=COUNTIFS(Kickstarter!F6:F4119,"successful",Kickstarter!R6:R4119,"plays",Kickstarter!D6:D4119,"<25000",Kickstarter!D6:D4119,">19999") adjusting the bolded terms as need. Then I calculated the sum of these values and their individual percentage. After that I visualized the percentages as of successful, failed and canceled goals at different goal levels by creating a line graph.

### Challenges and Difficulties Encountered
I initially encountered a challenged with my countif statements. I had not included the sheet information.  I had also initially tried to include both my upper and lower range in one criterion. I separated them and included the sheet range information so it read the correct values and functioned as intended.

## Results
One conclusion, I drew from the theater outcomes by launch was that starting in spring and continuing in summer individuals are more likely to back a play campaign. 
Another conclusion, I drew from the theater outcomes by launch was are more campaigns created in the spring and summer months.
One conclusion, I drew from the outcomes based on goal is there is a clear general trend in which successful campaigns are negatively correlated with the goal amount. 
