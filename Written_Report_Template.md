# Kickstarting with Excel

## Overview of Project

### Purpose
The overview and overall purpose of the project is to visualize the campaign for Theater outcomes based on their launch dates, the result provides us with a graph where we can see if the outcomes were successful, failed or canceled.
Furthermore, in another graph we can visualize the Plays outcomes of the camping in percentages of successful, failed, and canceled based on the funding goal amount. To create the graph for the Goal we used dollar-amount ranges to make the projection in percentage outcomes in the y-axis and goal-amount ranges on the x-axis.
As mentioned previously, the first graph helps us visualize how the campaign for Theater outcomes are by launch dates. The second graph helps us visualize the Plays outcomes in percentage ranges based on goal-amount ranges. This graph helps us understand the percentages of successful, failed, and canceled outcomes in percentages and dollar-amount ranges. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the analysis of Outcomes Based on Launch Date for this pivot graph we filtered the parent category on Theater so the outcome reflects the years using the YEAR() function which was extracted from the “Date Created Conversion” column, the pivot table filters that we used were “Parent Category” and “Years” as well as Theater, the chart that we selected shows the number of successful, failed and canceled projects by month or the launch date.

### Analysis of Outcomes Based on Goals
The analysis of Outcomes Based on Goals we visualize the percentages of successful, failed and canceled plays based on the funding goal amount, we used COUNTIFS() AND SUM() functions to populate “Number Successful”, “Number Failed”, “Number Canceled”, “Total Projects”, “Percentage Successful”, “Percentage Failed”, “Percentage Canceled”.

### Challenges and Difficulties Encountered
One of the challenges I encountered was to determine what field would go in each box for the pivot table.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion about the Outcomes based on Launch Date results is that the Theater was very successful in May, the lowest point it failed was in November, and lowest point it canceled was in July. The second point is that there seems to be missing information for canceled from September through November, this leaves room for many interpretations.  

- What can you conclude about the Outcomes based on Goals?
The Outcomes based on Goals is that the percentage for successful keeps declining as the goal-amount keeps increasing until the 20% of 25000 to 29999 where we can see an increase of the percentage and goal-amount, it reaches its maximum of 67% for the goal-amount of 35000 to 39999 through 40000 to 44999 and then it declines again very sharply to 0 at the goal-amount of 45000 to 49999 and then increases again. On the other hand, for the percentage failed we can see from the beginning that it increases as the percentage and goal-amount increase, and the percentage canceled is flat. These two last percentages can be a prediction that the plays outcomes are more negative than positive.

- What are some limitations of this dataset?
Some of the limitations of this dataset is that there is no comparison to be made between the other parent categories. 

- What are some other possible tables and/or graphs that we could create?
We could create a box plot graph to see if there are outliers in our data. This could give us a better understanding of the data and what we are analyzing.


- What are some limitations of this dataset?
Some of the limitations of this dataset is 

- What are some other possible tables and/or graphs that we could create?
We could create a box plot graph to see if there are outliears in our data. This could give us a better understanding of the data and what we are analyzing. 
