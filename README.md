# Kickstarting with Excel (this is a great title and I won't change it)

## Overview of Project
The project was designed to help a faux playwright understand Kickstarter campaigns. Basically.

### Purpose
This aforementiod faux playwright wanted to launch a play and this analysis was to enlighten her to as to what makes a Kickstarter campaign successful (or unsuccessful.)

-----------------------------

## Analysis and Challenges

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/21095468/122130009-975f7400-cdfc-11eb-925e-2b1f629f6f79.png)
### Analysis of Outcomes Based on Launch Date
All of the data is interesting of course, but I think for our purposes the most important thing is essentially the differential between
[(successful campaigns / total campaigns) * 100] = % success per month. The more successful campaigns as a percentage, the better the probable window for launch. I would say May, eyeballing this graph. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/21095468/122130050-a9411700-cdfc-11eb-8dd0-8d191ada252d.png)
### Analysis of Outcomes Based on Goals
Unfortunately I don't think this is going to provide much hope to our playwright. "The less money you request, the more likely to are to get it" (the short version of what this graph says to me) is not what anyone hoping to undertake a business endeavor really wants to hear. There is a sweet spot between a $30,000 and $40,000 campaign that has more successes than failures, but it also has a much higher cancellation rate than lower cost fundraisers which almost completely negates the positive differential if we used the equation from the last analysis. Having said that though, campaigns less than $10,000, and especially those around $5,000 do tend to have significantly positive trends. If her ambition is modest and her pitch is good, perhaps she can share in that success.


### Challenges and Difficulties Encountered
A bunch of rows were added at the end of my table, so I had to figure out how to delete them, which was curiously unintuitive so I had to Google it.
Then, I later discovered that during this I had accidentally deleted about 400 rows of my data. So I had to redownload the original workbook, find out which filters
I had accidentally deleted rows of, and then copy paste them back in, and reapply the formulas for rows we had created during the module to the new rows.
 
 ---------------------------------
 
## Results *

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    -Do launch right when tax season ends and people get their returns
    -Absolutely do not launch right before Christmas
  
- What can you conclude about the Outcomes based on Goals?
    -Low goal campaigns have more success (<$10,000)
    -The most successful higher campaign goal is $30,000 to $40,000

- What are some limitations of this dataset?
     -It's very difficult to analyze the immense amount of qualatative data contained in the title and blurb section, which I suspect most people who have browsed          for shows to watch online know can be a very significant part of what drives success
     -Our dataset is not especially large, nor is our filter especially specific. "Plays" can come in a plethora of genres which we aren't given
     -Some of the filters we are given, such as country, are difficult to know how relevant that filtering would or would not be until analysis was done on other           regions and compared to our target region.

- What are some other possible tables and/or graphs that we could create?
    -I would like to compare the tables and graphs we already have to similar tables and graphs created to be filtered by other countries, and see whether or how much      trends differ. In the event that trends different a statistically non-significant amount, or perhaps based on countries where the difference was statistically        non-significant, I would add them to the current calculations and use this larger sample size to filter further with more confidence. Especially I would like to      know our playwright's intended genre and do analysis on that. At that point if any other countries's data was added would could separate and compare samples.
    -A table of titles and blurbs of successful plays, perhaps with a filter applied to discover the most commonly used words or phrases.
    
------------------------------------------------------

# Initial analysis of kickstarter campaigns.
UW Data Analysis Bootcamp Module 1 Exercise
*Mock exercise done to help a faux playwright find and examine data on what would create a successful play kickstarter campaign.

![Parent Category Outcomes](https://user-images.githubusercontent.com/21095468/121991829-0c339f00-cd66-11eb-8d42-8aa1a847521c.png)
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/21095468/121991796-00e07380-cd66-11eb-84f5-d4cea0913f01.png)

*To the mock playwright I would add to launch the campaign in May, and keep the goal between $1,500 and $5,000.

*Also, should anyone not involved with the course look at this, I must deeply apologize for the graphs with perhaps poorly labeled axes. Obviously much less useful,
*but not in the course flow.

