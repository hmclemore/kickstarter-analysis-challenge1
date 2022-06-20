# Kickstarting with Excel
Louise created a Kickstarter Project for her Play 'Fever'. It fell short of its fundraising goal and she wanted some analysis performed to understand how other campaigns performed.  There will be insight gathered from analyzing her data that she can incorporate into her next attempt at fundraising for a Play. 

## Overview of Project
Review Kickstarter Play data to understand and help Louise determine how she could have been successful in her fundraising by studying trends from the data. High level stats are that Louise launched her play fundraising on June 13, 2016. Louise's play , 'Fever', had a fundraising goal of $2,885.00.  It reached a pledged amount of $2,485.00 representing an 86% completion rate but this was not enough to be considered successful.  The outcome was this play fundraising was a 'failure'.  

### Purpose
Analysis of comparable plays will give insight into how a successful play campaign can be launched which will help Louise and other play fundraisers. 

## Analysis and Challenges
The Analysis of Louise's Play 'Fever' needed extra work to break up the categories into Parent category and subcategories.  This was performed by using a delimiter on the data to separate the Category and subcategory into their own columns.  All charts will be based on the one subcategory of 'Plays' so we can compare only 'Plays'.  Other subcategories would yield results but are not comparable since they cover different audience interests.  One cannot assume that if a person donates to art books they would donate to Plays.  
Another challenge presented was the data was written in epoch time and had to be converted into traditional month/day/year conversion.  Two columns were created (S,T) to illustrate these epoch date conversions for creation date and end date. An additional 'Year' column (U) was also created.  

### Analysis of Outcomes Based on Launch Date
The first analysis performed was to review Outcomes based on their launch dates. Louise's Play fundraising was launched on June 13, 2016. Fundraising ended 28 days later on July 11, 2016, 28 days after launch date and reached an 86% funded rate but did not reach full 100%.  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/104876690/174508478-ec980002-14fe-47ca-a586-60b0212ace2a.png)


Louise chose the second most popular month to launch a play fundraiser.  The most popular month to launch is May followed by June, and July in third place.  In addition to these three months having the most launches they also had the highest count of outcomes.  May had 111 successful launches followed by 100 in June and 87 in July respectively.  Failed launches over those three months are pretty closely associated with May at 52 , June 49, and July at 50 failed outcomes.  This tight grouping indicates further analysis needs to be performed to since Louise chose a good month to launch in. Since Louise launched in 2016 i will toggle the year filter in the pivot table to show her competition in 2016. By switching to 2016 it reveals a steep downtrend of 34 successful outcomes in May followed by 20 successful outcomes in June.  This is the start of a downward decline in successful plays launched on Kickstarter and could reveal that interest in funding them was on the decline and Louise should have selected May . 
![Theater_Outcomes_vs_Launch_2016](https://user-images.githubusercontent.com/104876690/174508496-1cb875d3-7709-4717-b1aa-ca023fc37beb.png)


### Analysis of Outcomes Based on Goals
The second analysis performed was to review Louise's outcomes Based on goal amounts.  The Plays ranged anywhere from less than $1,000 to greater than $50,000.  Louise's Play goal was at $2,885.00.  Louise's play value was the most popular range ($1,000 to $4,999).  In her range 73% of plays were successfully funded, and 27% of plays failed.  This infers that Louise immediately had a 73% chance of being successful and when you review her individual funding percentage she actually received 86% funding and was only $400 short of her $4,885.00 goal.  

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/104876690/174508519-d6478578-0750-497a-9e8c-86a91083bea9.png)

If you look at the Outcomes Based on Goal chart below you will see that percentage of successfully funded plays steepens a downward trend at $1,000 all the way to $5,000.  Louise's play being valued at $4,885 is at the bottom of this steep decline representing a lower likelihood than the table calculation of percent successful for her bracket.  Her actual likelihood of success is near 58% while her funding bracket average is at 76% according to the data in the table.  

### Challenges and Difficulties Encountered

Some of the challenges in this data analysis involved converting Epoch times into short form date (month,day, year ) formatting.  I also converted one column into years to help out with a pivot filter.  Other challenges was the sample size.  Louise was fortunate to be fundraising in the US because that country had the most data of all the countries with 671 plays. Great Britain came in second with 314 plays. 
Other difficulties or unknowns in this analysis were any local or economical factors during this time in the theater fundraising category.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

For my analysis on the Launch Date I determined that while Louise did pick the second most popular month overall to start a fundraiser for a Play it was only when i drilled into the actual year 2016 before i realized she chose the 5th (tie) most successful month that year and should have chosen April or May to increase her chances of successfully fundraising.  
Another conclusion i came to was that her month was at a top trend of failed play campaigns totaling 18 for that month.  She only allowed 28 days for her kickstarter campaign and came up $400 short. If she would have allowed it to go another 28 days she would likely have reached her goal since successful plays were up in July vs. June when looking at 2016. I will attach this 2016 chart to show the uptick in successes the following month. Perhaps funding plays became more popular that next month and she could have capitalized on that popularity. 

- What can you conclude about the Outcomes based on Goals?
- When reviewing the outcomes based on goals chart I was surprised that my table calculated percent of success for Louise's bracket was 76% successful but her actual success at her $4,885 goal was much lower (58%).  This shows that the average of her bracket had a wide range and one would need to review this data graph to see that.  

- What are some limitations of this dataset?
- This data set is limited to not showing years. With more time to review i would probably recreate this in a pivot table where i could filter between years because i believe in narrowing down to just the year (2016) Louise submitted and then comparing to overall years in general to find any similarities. 

- What are some other possible tables and/or graphs that we could create?

I had more questions so i created some tables on my own (found in my data sheet). Found on tab 'Pivot1'.  I was curious about submissions per country.  the US had the highest number of kickstarter campaigns (3038) with GB in second place (604) and Canada in 3rd place (146). all other countries  were very far behind which limits my conclusions to only the US market.  The other country submissions are not a large enough sample size for me to draw strong conclusions about consumer trends in fundraising. 
I also created another pivot that shows the amount of time elapsed between kickoff dates and end dates. I found that Louise only allowed her kickstarter campaign to go for 28 days.  She was $400 short.  If she had been allowed another 28 days i could reasonably conclude that she might have reached her final goal of $4,885.00.  
