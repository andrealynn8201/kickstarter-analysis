# Launch Dates and Goals Chart
An analysis of launch dates throughout the year as well as similar campaign goals and their most successful range.

## Analysis and Challenges
When compiling the data, I used the whole data from Kickstarter. I created a new column where I took just the year from the “Date Created Conversion” data points to see if there were any discrepancies between the years. I created a pivot table, which filtered out the years and theater from the parent category.  Outcomes was in the columns field, date created conversion was in the rows, and count of outcomes was in the values field.  This gave me a tally for all the successful, failed and canceled campaigns for each month.  I could filter each year out to see if there were any trends or discrepancies.  I was also able to filter specifically for theater.  If Louise would like to see other categories besides theater and their launch campaign, this would be easily rendered with this pivot table.  It allowed me to see that a full years worth of data wasn’t available until 2015-2016.  I needed to see all the years as I didn’t have enough data to give much of an analysis. I was then able to put the data into a graph, to more easily visualize what the pivot table was telling me. I would say that one challenge is that using the data from 2009-2017, I only have 2 complete years of information. From 2009-20014, the data is spotty.  In 2017, I only have January’s data to use. Even though the range is good, the data isn’t able to give me a more accurate view of what a typical year of campaigning in the theater industry looks like.  

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93801125/142805465-e2af276a-f65c-49d6-9d6e-001fa51f3422.png)

When looking at the best outcomes based on goals, I created a table for goal ranges, whether they were successful, failed or were canceled, and only used the criteria “plays” from the subcategory.  This gave me the total number of successful, failed and canceled plays in each goal range, and a total of plays within each goal range.  By doing this, I was able to get a percent of successful, failed, and canceled plays, which in turn, allowed me to see much easier, how each goal range fared overall.  Using a graph helped visualize how each outcome did as the goals increased. A challenge I faced was when finding the number of canceled funding campaigns, which there weren’t any cancelations, I found I was having a tough time trusting the data. Out of hundreds of funding goals, not one of them were canceled.  I would have liked to do more research to find out why this was the case.  In much of the other subcategories, there were at least some cancelations if the numbers for that subcategory was a good representation, as plays seems to be. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93801125/142805526-12d4a5b8-369d-4870-9448-88fd682cc34f.png)

 ## Results 

According to the data, the best time to launch a campaign to get the most success, would be in May or June. Even though the trend is heading downward, The successes are much higher overall.  I would also add that the chances of canceling the campaign are pretty much the same, no matter what time of year.

In regards to the Funding goals, the sweet spot seems to be between $0-$4999.  With a percentage of successful campaigns over 70%.  

A limitation to this particular data set, is you don’t see why the lower the funding expectation, the more successful you’ll be.  Another limitation is you don’t see where, geographically, these successes/failures are taking place.  Is it higher in the US or GB?

I would like to filter where the plays were located to see the results of success/failure. Possibly create a pie chart with each pie representing success/failure and the geography within each.
