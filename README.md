# Marketplace for Companies and Influencers

Final project for the Building AI course

## Summary

Connect Companies with the right influencer for their campaign!Via good filters to find the right influencer for their budget and industry! Instagram, TikTok, Snapchat! 


## Background

Social Media marketing is the biggest in marketing nowadays. If you are a company or private person and wants to market your products how will you find the right Influencer that fits your target group and is within your budget?
We want to collect data from the Influencer: Followers etc so that the company can filter to target the right influencer for their product!


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
The database needs to be created by scraping influencer data (followers, industry, and more). Those who will use the platform are influencers themselves, as well as public profiles. Customers will become members to match with the right influencer based on their intended target audience. We operate as a broker between companies and influencers.

![Cat](https://github.com/Rob-Amandi/my-new-project/blob/main/Influencer-Tipps_SOM_Header-2048x1367.jpg)
![Cat](https://github.com/Rob-Amandi/my-new-project/blob/main/Influencer.jpg)

## Data sources and AI methods

Common sources include social media platforms (Instagram, Twitter, YouTube, etc.), blogs, websites, and public databases.

We will use web scraping tools or libraries (such as Beautiful Soup, Scrapy, or custom scripts) to retrieve data from web pages. These tools simulate human browsing behavior and extract relevant information.

We will create a list of URLs corresponding to influencer profiles.

Data Extraction:
Profile Information: Extract basic details like username, follower count, bio, location, and profile picture.
Posts and Engagement Metrics: Collect data on the influencer’s posts, likes, comments, shares, and engagement rates.
Audience Demographics: Gather information about the influencer’s audience (age, gender, location, interests).
Content Categories: Identify the influencer’s niche (e.g., fashion, fitness, travel).
Some websites load data dynamically using JavaScript. In such cases, tools like Selenium can automate interactions with the page to retrieve dynamic content.
Collaborations and Partnerships: Look for sponsored posts, brand collaborations, and partnerships.
Hashtags and Keywords: Extract relevant hashtags and keywords used by the influencer.

Handling Dynamic Content:
APIs (Application Programming Interfaces) provided by social media platforms can also be used to access data in a structured way.

[Meta API] https://developers.facebook.com/docs/instagram-api/#instagram-graph-api

Data Storage:
We will store the scraped data in a structured format (e.g., CSV, JSON, or a database).

Data Cleaning and Validation:
We will remove duplicates, handle missing values, and validate data integrity.
Ensure that the data is accurate and up-to-date.

## Challenges

The data we retrieve must be public. If an influencer does not wish to be part of the network, it should be easy to leave.
Negotiations regarding compensation and more are handled directly between the customer and the influencer within our application, as we receive a kickback on every transaction.

## What next?

We need a Data Engineer to help us set up the APIs. We will build the Frontend of the site but need help with the backend. 
Currently, the application does not handle marketing campaigns, statistics, and more, but we plan to expand these features in the future.

## Acknowledgments
[Pictures](https://www.internetworld.de/social-media-marketing/influencer/influencer-marketing-im-dialog-meinungsfuehrern-1084806.html) / https://www.som-onlinemarketing.com/2020/09/22/influencer-marketing-7-essentielle-tipps-fuer-den-erfolg/)

