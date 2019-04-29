---
Author: Bryan Tamsir
Date: 4/28/2019
Title: Individual Project - First Version
output: html_document
---

## The Making Of. 

> This RMD/MD file documents the making of three distinct, unique, non-trivial, and somewhat surprising visualizations for the mayor of Chicago regarding the Speed Camera Violations dataset. These three visualizations are to convey visualizations that are somewhat unexpected but yet holds the audience into valuable account. The audience is the mayor and the message is to identify the decreasing violations trend, but more work needs to be done.

**Visualization #1, Violation Time Trend** 
*** 

![Visualization 1, Step 1](https://github.com/btamsir/Data-Visualizations/blob/master/V1s1.png)


**Step 1** 

Attempting to show the mayor of Chicago the decreasing overall violations time trend, the is the first iterations. We can see that there is a decrease in sum of violations over time. But the data can be misleading since the year 2014 and 2019 does not have data for all 12 months. I ommited 2014 and 2019 as as result. The logic for this to show the years and size with respect to sum of total violations. Further steps will change the colors accordingly. 

***

![Visualization 1, Step 2](https://github.com/btamsir/Data-Visualizations/blob/master/V1S2.png)

**Step 2** 

This next iteration is was to show the message of decreasing violations using a line plot with area under the curve, but I realized that perhaps the mayor may not understand that. For that reason, I decided to ditch the area under the curve and to use a simple, yet unexpected stoplight visualization. 

***

![Visualization 1, Step 3](https://github.com/btamsir/Data-Visualizations/blob/master/V1S3.png)

**Step 3** 

This final step showcases a "stoplight" with color and size coordinated aspects. This is a simple visualization that forefronts the red to orange aspect since the sum of total violations have decreased over the past four years. 

*** 

**Visualization #2, Violation Address Time Trend** 

For this next visualization, I wanted to delve deeper and identify the top four addresses and identify the yearly time trend within those addresses. I wanted to develop the story from the first visualization. There is a decrease in violations over time, but what of the most troubled addresses and areas? 

![Visualization 2, Step 1](https://github.com/btamsir/Data-Visualizations/blob/master/V2S2.png)
**Step 1**

This visualization depicts the top four addresses. This color trend matches that of Visualization #01 to maintain consistent communication integrity. 

*** 

![Visualization 2, Step 2](https://github.com/btamsir/Data-Visualizations/blob/master/V2S3.png)
**Step 2**

This final visualization depicts the top four addresses wth a violation trend line. This trend matches that of Visualization #01. Furthermore, this visualization matches the color and sizing of the first visualization to maintain consistent communication integrity. The message to the mayor is that even in the top 4 addresses, the decreasing trend is consistent. 

***

**Visualization #3, Address Tree Map** 

Moving forward, this visualization is to depict the most recent areas to address. The mayor would do well to know which addresses still have the most violations. As a result, I wanted to partition the visualization to just 2018 and to focus on the top addresses. This is in line with the story of the previous two visualizations as it builds a narrative because even though the trend is decreasing, these addresses have the highest violations. I used the tree map because I wanted the mayor to identify the top addresses and areas that have the largest violations. 

![Visualization 3, Step 1](https://github.com/btamsir/Data-Visualizations/blob/master/V3S2.png)

This iteration is a tree map of all years and addresses with respect to violations. My logic was to show the mayor the address with the highest violations. But thinking further, I decided to subset only into the year of 2018. The reason is simply because it is the most recent whole dataset. 


![Visualization 3, Step 2](https://github.com/btamsir/Data-Visualizations/blob/master/V3S3.png)

This is the final visualization for the Mayor of Chicago. This visualization shows the addresses with the highest amount of violations and the actual interger amount. This is finalizes the story of violations in Chicago because although the trend is decreasing, these neighborhoods are crucial to lowering violations. Furthermore, I added the color palatte that is in line with the previous final two visualizations. The message for the mayor is that these neighborhoods have the highest violations still in 2018 and to monitor them for the future. 


