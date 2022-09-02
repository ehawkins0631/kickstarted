
Kickstarter-Analysis



Project Overview:


Purpose:

This analysis aims to provide insights and recommendations to Louise, to be able to certain when she should begin 
her first crowdfunding campaign for her upcoming play 'Fever" for which she has a estimate budget of $10,000. The 
insights and recommendations have been sourced from a Kickstarter dataset which comprises of 4114 campaigns which
were launched between 2009-2017, across 9 entertainment categories, with a focus on theaters.

Background:

Louise, a playwright and our client is looking to come up with her first kickstarted crowdfunding campaign for her play 'Fever'.
She would like to know how different campaigns fared in relation to their launch dates and their funding goals.

Analysis and Challenges

The Analysis covers a dataset containing 4,114 Kickstarter campaign IDs, 9 parent categories and 41 subcategories, funding
goals data of the campaign IDs, pledged amount of the campaign IDs, and funding outcomes of each of them. (success, canceled,
failed) 

We are focusing on the theater parent category where we are observing the volume of successful, failed and canceled theater campaigns
in each month (between 2009-2017) and comparing the success/failure rate of these theater campaigns across these months to better
understand which months had the most successes and rate of success.

Challenges

Some of the challenges encountered with the data was the UNIX timestamp formats of the goal deadline and launched deadlines which needed
to be converted to date format and splitting the category and subcategory data into parent category and subcategory to effectively view 
the data of the theater campaigns which is relevant to Louise.

Results :

Theater Outcomes by Launch Date:


Conclusion 1 - Campaigns under the Theater category which began during the summer months of May, June and July were much more successful 
with May being the most successful month.


Conclusion 2 - The winter months of Nov, Dec and January had the lowest performance in terms of successes along with very low volume of 
launched campaigns - 259 total across these months while 457 campaigns or 76.4% were launched across May, June and July.
Outcomes based on Goals.


Outcomes based on Goals:

Conclusion - The most number of succesful theater campaigns were for ones which had funding goals below $15,000 (661 campaigns). For Louise's
budget ($10K) she could expect a market success rate of 55%.

Data Set Limitations:
We are not clear of the average run time of each campaign which is an important metric for Louise to know how long she can expect to wait 
to hit her funding goals. This data set doesn't provide average amount of money received per campaign in each month as well, which can be
an important piece of information for Louis to understand which month brought in the most funds per campaign.

Figure 1
![image](https://user-images.githubusercontent.com/101227930/188048487-fc927df6-d946-4b35-b00c-96fda78c3576.png)




Figure 2
![image](https://user-images.githubusercontent.com/101227930/188048549-38c0e5c6-a569-4432-b943-506ee2a1605c.png)


Recommendations:

Recommend creating a new column in the Kickstarter data set which provides the total run time of each campaign in terms of days. This can
tell us the time it took for each campaign in the theater category to meet or fail this campaign fund goals. From this we can also 
uncover the average run time of successful theater campaigns to better inform Louise of the time she can expect to wait for a campaign to
meet goals in a given month.

Additionally we can recommend the creation of a bar chart which provides the average amount of money received per campaign (Y axis), 
in each month (X axis). This can help us get close to the month which provides the best rate of success at a budget of $10,000.




email:  ehawkins0631@gmail.com

twitter: @evahawkins0630

https://www.linkedin.com/in/eva-hawkins-a9b333147/

