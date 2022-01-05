# What factors make a Kickstarter campaign successful?

# Introduction

Kickstarter is a global crowdfunding platform which helps creative projects to raise funding from backers. Project creators choose a deadline and a minimum funding goal. Projects must reach their funding goal, otherwise no money will be collected. People who back Kickstarter projects are offered tangible rewards such as custom editions and early releases of the projects as well as special experiences in exchange for their pledges. The platform is currently only open for project creators from a small selection of countries but project backing is available internationally.

# Data
The data was obtained from [Kaggle](https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201801.csv). 

The data set contained the following columns:
1. id - Internal Kickstarter project ID
2. name - Name of the project
3. category - Category (specific)
4. main_category - Category (main)
5. currency - Currency of funds for project
6. deadline - Deadline to fund goal amount
7. goal - Goal amount to fund
8. launched - Date project was launched
9. pledged - Amount pledged in country's currency
10. state - State of the project, includes "successful" , "failed" , "live" , "cancelled" , "undefined" , "suspended"
11. backers - Number of people who contributed to the campaign
12. country - Country project was launched in
13. usd.pledged - Amount pledged in US dollars, conversion done by kickstarter
14. usd_pledged_real - Amount pledged in US dollars, conversion done by Fixer.io API
15. usd_goal_real - Goal amount in US dollars, conversion done by Fixer.io API

### The questions I asked:

1.	What is the average number of days it takes for a campaign to become successful?
2.	What campaign categories have the highest success rate?
3.	Does the number of backers affect the success or failure of a project?
4.	Does the funding goal amount affect the success or failure of a project?

# Dashboard

![Kickstarter Dashboard](https://user-images.githubusercontent.com/92667306/140593458-9cff3657-8a6c-4d3f-b2bb-06d63bea764b.jpg)





