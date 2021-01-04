# kickstarter-analysis
Performing analysis on Kickstarter data
## Project Overview
Up-and-coming playwright, Louise, is seeking advice on reaching funding goals for the kickstarting campaign for her play, Fever. She believes that her play will cost approximately $12,000 and she would like to gain insights from the outcomes of similar Kickstarter campaigns and the factors that led to their success. 
## Analysis Overview
To provide Louise with the information she needs to create a successful Kickstarter campaign, data was taken from Kickstarter for analysis. This dataset includes details on various categories of Kickstarter campaigns, such as: film and video, food, games, journalism, music, photography, publishing, technology, and theater. Each category contains additional information on each campaign’s fundraising goal and the amount pledged, the outcome of the campaign, as well as the campaign’s launch dates.
![Outcomes_vs_Goals](/Outcomes_vs_Goals.png)
![Theater_Outcomes_vs_Launch](/Theater_Outcomes_vs_Launch.png)
## Challenges
The main challenges encountered while analyzing the Kickstarter dataset come from data noise and figuring out how to handle outliers. The issue with data noise was overcome by creating parent categories and subcategories, and by filtering the data to eliminate all unnecessary data in our analysis. Once we had all the data around theater Kickstarter campaigns, it was easier to visualize and examine the outcomes that Louise was looking for.
The other challenge faced was on how to address outliers that were skewing the results. Rather than eliminate fundraising goals and pledged amounts that were greater or lower than three standard deviations than the mean, we felt that it would be better to leave these values in our analysis. This would allow us to provide Louise with a full picture of the Kickstarter data. 
## Results
Through analysis, we were able to determine that the best month to launch a Kickstarter campaign in the theater category was May, as it had the highest number of successful campaigns. From there, we saw the number of successful campaigns decrease to its lowest point in December. 
We also observed that campaigns that had fundraising goals under $5,000 and between $35,000 and $45,000 had the highest percentages of successful outcomes. If Louise’s budget remains at $12,000, the data shows that she may have a 54% chance of being successful.
## Recommendation
While these insights will help Louise in making the decisions needed to launch a successful, we believe that she will also benefit from a graph that shows the relationship between outcomes and campaign lengths. This would give us an idea of how long it would take for Louise to achieve her fundraising goals. 
