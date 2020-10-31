# Optimizing customer acquisition funnel using A-B test
Customer acquisition funnel is a process/place where you turn prospects into customers. Is it optimized? 

Do you have a high number of visitors coming to your website, and only a very few are converting into customers?
Do You have plenty of users who sign up for free trials, but many of them aren’t converting into paying customers?

This is an indication that your customer acquisition funnel isn’t optimized.

In this project, I will analyze the customer Acquistition funnel of a Gym named <b>BodyWorks</b>. BodyWorks has an SQLite database, which contains several tables that will be helpful in this investigation:

- <b> visits</b> -contains information about potential gym customers who have visited MuscleHub
- <b> fitness_tests</b> -contains information about potential customers in "Group A", who were given a fitness test
- <b> applications</b> -contains information about any potential customers (both "Group A" and "Group B") who filled out an application. Not everyone in visits will have filled out an application.
- <b> purchases</b> -contains information about customers who purchased a membership to MuscleHub.

I have downloaded the data from their database into csv files, which i will load into a Jupyter Notebook using Python Pandas.
