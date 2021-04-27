# DataScienceGuidedCapstone

## Guided Capstone Project Report - Step 6
### Write a 1-2 page report summarizing your recommendations for Big Mountain Resort. Be sure to include the figures you created to back up your recommendations 

### Audience = Big Mountain Resort Stakeholders

### Introduction 
Big Mountain Resort is not realizing its full potential of the facilities it offers to skiers and thus they need to select a better price for their tickets. Since installing a ski lift, their operation costs have increase by $1.54 million dollars. This report was requested to summarize our findings of what ticket price they could be charging with the data we were given. 

### Data 
We were given data from analysis of most of the resorts in the United States, 330 resorts, a proper playground for Big Mountain Resorts competition. We dropped things like resorts with no price data. In the data we can see target features for desired ticket prices are; terrain parks, skiable terrain, number of days open for resorts previous year, and if the resort had night skiing available. 
Another dataset was added that contained information about the state the resorts were in such as population and area of the state.

### Methods/Analysis 
When we did exploratory data analysis we looked at features each state had such as; total skiable area, total days open for skiing, and how densely the resorts were in the state.  Average ticket price by state was also plotted to see how states differed, however no patterns were found to see any relationship between state and ticket price. 
Looking at the specific features of each resort in each state lead us to model their data based on the features. We learned from modeling that the features of the resorts that were most important were: vertical drop, snow making area coverage, total chair lifts, fast quads, number of runs, the longest run in miles, number of trams, and the total skiable terrain area. 
We tried a Random Forest regressor imputing missing values using the median and found we didn’t need to use standard scaling. The cross validation with this RF and the estimate was consistent.
We have decided to use the Random forest model going forward. The reason behind this decision is we expect the correct price is closer by 1.00 USD on average. This is important because with a high number of visitors per day could equal a significant loss or gain of capital over the course of the ski season.

### Conclusions 
To start off with my summary, Big Mountain Resort charges 81 for a normal adult ticket. Big Mountain Resort modeled price is 94.22, actual price is 81.00. Even with the expected mean absolute error of 10.39, this suggests there is room for an increase, BMR has amazing features in its resort that others do not.
I would suggest to the executives of the company that adjusting the ticket price higher certainly would benefit them, and wouldn’t loose customers due to their resorts unique features.
Additional operating costs like a new chair lift only add to the overall inclination to boost ticket prices. Extending the vertical drop, even with the additional costs of chair lifts and snow making area, is the TOP scenario for increased revenue. Closing 1-3 runs that are difficult/expensive for the resort to maintain could be done, but closing 6 or more runs leads to a drop in ticket price.
The data does not go over how much each resort’s expenses are when it comes to maintaining ski runs, facilities, etc. I would include recommendation for additional data set of cost of maintenance for Big Mountain Resort.


