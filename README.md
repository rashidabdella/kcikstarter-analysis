# Kickstarting with Excel

## Overview of Project

 The purpose of this analysis is to provide insight on the outcomes of the campaigns for plays based on Goals and date created regarding theater.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
 Created a pivot table to filter the parent category under theater. We found that the most successful Kickstarter campaigns launched in the months of May and June while most failed campaigns occurred around the months of May throughout June. 

### Analysis of Outcomes Based on Goals
I used the formula =COUNTIFS(Kickstarter!$F:$F,"=successful",Kickstarter!$D:$D,"<1000",Kickstarter!R:R,"plays") in order to get the number successful. Did the same with the rest of the columns but changes the goal range as well as the successful, failed, and cancelled parameters. To get Percentages I just divided the selected parameter, i.e., Number failed/total projects and did the same for the rest. 
### Challenges and Difficulties Encountered
I had no challenges in creating the pivot, however, getting the correct data may be difficult depending on the values you enter in the pivot rows and columns. As far as creating a line graph for the outcomes based on goals chart, I had to play with the selection of the table in order to generate appropriate row and column labels.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?  
-We found that the most successful Kickstarter campaigns launched in the months of May and June while most failed campaigns occurred around the months of May throughout June. Cancelled outcomes stayed fairly low throughout the year with a peak in cancellations during January.

- What can you conclude about the Outcomes based on Goals?
-The highest percentage of successful outcomes were with goals of less than 5000. All campaigns failed when the goal was between 45000-50000. I can conclude that a majority of campaigns will be successful if the goal is set below 5000, and campaigns generally fail the higher the goal is set. 

- What are some limitations of this dataset?
-The data set only shows plays, individually charts will need to be made with different subcategories in order to capture data from each campaign by specifying each category on the outcomes based on goals chart. 

- What are some other possible tables and/or graphs that we could create? 
-It is possible to create stacked bar graphs to interpret data in a different way, however, with this data set, line graphs are more easily interpreted. 
