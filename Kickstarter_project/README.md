# What factors make a Kickstarter campaign successful?

# Introduction

Kickstarter is a global crowdfunding platform which helps creative projects to raise funding from backers. Project creators choose a deadline and a minimum funding goal. Projects must reach their funding goal, otherwise no money will be collected. People who back Kickstarter projects are offered tangible rewards such as custom editions and early releases of the projects as well as special experiences in exchange for their pledges. The platform is currently only open for project creators from a small selection of countries but project backing is available internationally.

# Data
The data was obtained from Kaggle, at https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201801.csv . The original dataset contained 15 variables.

The data set contained the following columns:
•	id - Internal Kickstarter project ID
•	name - Name of the project
•	category - Category (specific)
•	main_category - Category (main)
•	currency - Currency of funds for project
•	deadline - Deadline to fund goal amount
•	goal - Goal amount to fund
•	launched - Date project was launched
•	pledged - Amount pledged in country's currency
•	state - State of the project, includes "successful" , "failed" , "live" , "cancelled" , "undefined" , "suspended"
•	backers - Number of people who contributed to the campaign
•	country - Country project was launched in
•	usd.pledged - Amount pledged in US dollars, conversion done by kickstarter
•	usd_pledged_real - Amount pledged in US dollars, conversion done by Fixer.io API
•	usd_goal_real - Goal amount in US dollars, conversion done by Fixer.io API

### The questions I asked:

1.	What is the average number of days it takes for a campaign to become successful?
2.	What campaign categories have the highest success rate?
3.	Does the number of backers affect the success or failure of a project?
4.	Does the funding goal amount affect the success or failure of a project?

# Data Visualization

![Kickstarter Dashboard](https://user-images.githubusercontent.com/92667306/140593458-9cff3657-8a6c-4d3f-b2bb-06d63bea764b.jpg)





