---
Author: Bryan Tamsir
Date: 5/04/2019
Title: Individual Project - Revision
output: html_document
---

## Documentation and the making of violations in the city of Chicago  

> This RMD/MD file documents the making of three distinct, unique, non-trivial, and somewhat surprising visualizations for the mayor of Chicago regarding the Speed Camera Violations dataset. 

*** 

The full project can be seen here. 
[Tableau Public Project](https://public.tableau.com/profile/btamsir#!/vizhome/FirstVersion-IP/Dashboard1?publish=yes)

## Data Explanation and Data Cleaning. 

The original dataset is speed camera violations in Chicago where each record gives the number of violations captured by a particular camera on a given day. The dataset has data from 2014 to 2019, but years 2014 and 2019 have an incomplete dataset that doesn't cover all 12 months. As a result, I subsetted the data to contain data from 2015-2018. 

There are 9 total variables: 

* Variables
    + Address
    + Camera ID
    + Violation Date
    + Violations
    + X - Coordinate
    + Y - Coordinate
    + Latitude  
    + Longitude
    + Location

[Chicago Speed Camera Violation Source](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4)  

***

### Visualization #1, Average Violation Time Trend

![](/Images/V1final.png)  



This first visualization clearly showcases the 2015 - 2018 average violations partitioned into years and months. The average line was added to show the average number of violations per year and we are able to observe a decreasing average for every year. Furthermore, This visualization acutely shows higher number of violations with a darker red and fewer violations in yellow. Finally, the violation observations have increased opacity to highlight the average line. Step 3 of making this visualization was an extremely simple iteration of the message and I wanted to add the observations to validate the chart. The making of this visualization from beginning to end in steps can be seen below. 

* Compared to step 3, the final visualization is: 
    + Easier to digest average lines
    + Provides statistical reference
    + Appropriate color Schema
    + Comparison of Years

*** 

**Step 1** 

![](/Images/V1s1.png)




Attempting to show the mayor of Chicago the decreasing overall violations time trend, the is the first iterations. We can see that there is a decrease in sum of violations over time. But the data can be misleading since the year 2014 and 2019 does not have data for all 12 months. I ommited 2014 and 2019 as as result. The logic for this to show the years and size with respect to sum of total violations. Further steps will change the colors accordingly. 

* Comments
    + First pass
    + Decrease in sum of violations
    + Excludes 2014 and 2019

***

**Step 2** 

![](/Images/V1S2.png)



This next iteration is was to show the message of decreasing violations using a line plot with area under the curve, but I realized that perhaps the mayor may not understand that. For that reason, I decided to ditch the area under the curve and to use a simple, yet unexpected stoplight visualization. 

* Comments
    + Area under the curve may be misinterpreted
    + Line trend over years
    
***


**Step 3**

![](/Images/V1S3.png)

 

This final step showcases a "stoplight" with color and size coordinated aspects. This is a simple visualization that forefronts the red to orange aspect since the sum of total violations have decreased over the past four years. 

* Comments
    + Color and size schema to show decreasing violation trend. This is fine as an initial story but this visualization doesn't have statistical referencing and can be deemed misleading. 
    + The size of the bars are pointless and the finalized iteration of this message/chart can be observed at the top. 

*** 

### Visualization #2, Top 4 Violation Address

![](/Images/V2final.png)  

For this next visualization, I wanted to delve deeper and identify the top four addresses and identify the yearly time trend within those addresses. I wanted to develop the story from the first visualization to identify if a decreasing violation trend in the top addresses. 

* Comments
    + Labeled each bar chart. This will give a number to the audience that can be related to the trend line compared to without it. However, this may increase the clutter of the visualization. 
    + Lowered opacity for the bars to highlight the trend line. The important factor is the decreasing trend for the four addresses. We notice that the decreasing trend holds true to overall trend. 
    + Bolded the trend line. 

**Step 1** 

![](/Images/V2S2.png)

This visualization depicts the top four addresses. This color trend matches that of Visualization #01 to maintain consistent communication integrity. 

* Comments
    + Bar Chart for the top four addresses. This is fine, but it leaves too much for interpretation to the audience. 
    + Line trend over years
    
*** 

![](/Images/V2S3.png)
**Step 2**

This step visualization depicts the top four addresses wth a violation trend line. This trend matches that of Visualization #01. Furthermore, this visualization matches the color and sizing of the first visualization to maintain consistent communication integrity. The message to the mayor is that even in the top 4 addresses, the decreasing trend is consistent. This is the final iteration before the finished product seen above. 

* Comments
    + The width of the bar chart is unneeded. There should be a standardized width for all observations. 
    + This step still has the trend line, but it isn't bolded. 

***

### Visualization #3, Top Violation Addresses in 2018

![](/Images/V3final.png)



** Step 1 ** 

![](/Images/V3S2.png)

This iteration is a tree map of all years and addresses with respect to violations. My logic was to show the mayor the address with the highest violations. But thinking further, I decided to subset only into the year of 2018. The reason is simply because it is the most recent whole dataset. 

*** 

** Step 2 ** 

![](/Images/V3S3.png)

This is the step before the newly revised chart for the Mayor of Chicago. This visualization shows the addresses with the highest amount of violations and the actual interger amount. This finalizes the story of violations in Chicago because although the trend is decreasing, these neighborhoods are crucial to lowering violations. Furthermore, I added the color palatte that is in line with the previous final two visualizations. The message for the mayor is that these neighborhoods have the highest violations still in 2018 and to monitor them for the future. 

* Comments
    + Although the tree map is an easy way to categorize the worst addresses, it is inefficient at telling a story past the top 2-3 addresses. The area of the tiles are not proportionate to the number of violations and thus is an ineffective chart. 
    + This step still has the trend line, but it isn't bolded. 
    + The final visualization is seen above. On the X-axis has the violations and address on the Y-axis for readability. Furthermore, the addresses are ordered in a descending order. 
