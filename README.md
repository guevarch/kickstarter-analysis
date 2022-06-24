# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of the project is to analyze the outcomes based on the Launch Start Date and the Goals for Louise's campaigns to determine the relationship. Another purpose is to help Louise understand more about how the different campaigns fared in relation to their launch date and funding goals. Lastly, to continue to test our excel prowess using pivot charts, tables, countifs, chart elements, graphs and a host of other excel functions.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

- For the analysis of outcomes based on launch date deliverable, one challenge that arose was converting the x-axis or the row labels to months. Trial and error and attention to detail is the best way to overcome this challenge. By holding and dragging the subcategory years to the pivot table twice will convert the rows to months. 

- ![image](https://user-images.githubusercontent.com/107594143/175439847-04541cc4-8ef2-47a4-8fc2-d2579de13c88.png)


### Analysis of Outcomes Based on Goals

- For the analysis of outcomes based on goals delivereable, one challenge that arose was learning the syntax for the countifs function. The function is quite lengthy - =COUNTIFS(Kickstarter!$F:$F,"cancelled",Kickstarter!$D:$D,">=10000",Kickstarter!$D:$D,"<=14999",Kickstarter!$O:$O,"plays"). The best way to overcome this challenge is to read the example outlined carefully and to follow it as best as possible.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From the analysis of the outcomes based on launch date, the most successful months are May and June and the least successful months are November and December.

- What can you conclude about the Outcomes based on Goals?

From the analysis of outcomes based on goals, the higher the goal amount the lower the success rate. 

- What are some limitations of this dataset?

Some of the limitations of the data set include the outliers that would skew the data in either direction. A possible solution is to identify the outliers using mean, standard dev., median and IQR analysis and eliminate these outliers.

- What are some other possible tables and/or graphs that we could create?

Some of the possible tables/graphs we could create is the box and whisker plots.The box and whisker plot helps identify outliers within a data set using standard deviation and IQR. By identifying these outliers, we can eliminate them from the data set, producing more accurate and precise information.

