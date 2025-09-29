# User-Interaction-Analysis-on-Youtube


## Date : 



Started : september 16, 2025
Ended : september 28 2025



## Tools :

Python,
Pandas,
Mysql Workbench,
Jupyter notebook,
Microsoft Power BI



## DataSet Production :

Due To Extremely Unstable Functionality Of Webscraping On Youtube & High Costs Of API Services, Both Google And Other Web Companies, The Whole Data Is Collected Manually.

At first I tried to collect the data through scraping but it was really unstable and did not work efficiently. then i tried " Googleapiclieant " library which as you may know, it has a few limits &
You can not get the whole data that you want, all at once, if you're going to have a large dataset or many requests. there are a few websites that offer these sort of services but I did not 
Find them affordable at the time, there I had to collect the whole data manually.



## The Idea :

* The Main Questions Were
1- Which youtube channels, somehow make their audience to interact with their videos ?
2- Do the channels with high subscrption numbers have the most interaction between their channels and their audience ?
3 - is it related to the subject that they mostly focus on ?
4- does the duration of videos play an important role here ?



## Interaction Rate :

The calculation of the interaction rate is only around the count of both likes & comments !!

due to youtube privacy policies on dislike & channel subscription list,
we don't know exactly, whether the viewers or users that liked the content or the ones who made comments,
are they actually the channel subscribers or just random users scrolling up & down on youtube pages.
so I considered the viewers of each video as the source of channel subscribers.

The rate is the result of these calculations : 
First I dis get a sum of all like counts from the chosen videos of a channel and did the same also for comment counts,
Then I add the results together, after that I divided the result of the sum, to the sum of all chosen videos view counts, the multiply to 100.

(((sum of like counts from chosen videos) + (sum of comment counts from chosen videos))  /  sum of view numbers from chosen videos ) * 100



## Also :
During the cleaning part, I intentionally exclude a few values across the dataset from filters, so it gives the chance to encounter the errors in different levels and steps, which i think it's important to face these issues anywhere possible & probable, just to get better at solving the problems.
some categories have more presence than the others and vice versa in the dataset, because I wanted the data to be more balanced in order to have an indication of differenceو growth or decline
in details and more in depth, not on surface.
