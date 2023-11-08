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
# Python code for creating the scene
import matplotlib.pyplot as plt
import numpy as np

# Create a canvas
fig, ax = plt.subplots(figsize=(8, 6))

# Draw influencers and customers
influencers_x = np.random.uniform(0, 1, 5)
influencers_y = np.random.uniform(0, 1, 5)
customers_x = np.random.uniform(0, 1, 10)
customers_y = np.random.uniform(0, 1, 10)

ax.scatter(influencers_x, influencers_y, color='b', label='Influencers', s=100, marker='o')
ax.scatter(customers_x, customers_y, color='g', label='Customers', s=50, marker='s')

# Set background colors
ax.set_facecolor('#f9f9f9')

# Add title and labels
plt.title("Influencers and Customers Meeting", fontsize=16)
plt.xlabel("X-axis")
plt.ylabel("Y-axis")

# Hide axes
ax.spines['top'].set_visible(False)
ax.spines['right'].set_visible(False)
ax.spines['bottom'].set_visible(False)
ax.spines['left'].set_visible(False)
ax.tick_params(axis='both', which='both', length=0)

# Add legend
plt.legend(loc='upper right')

# Show the plot
plt.show()

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

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments
[Pictures](https://www.internetworld.de/social-media-marketing/influencer/influencer-marketing-im-dialog-meinungsfuehrern-1084806.html) / https://www.som-onlinemarketing.com/2020/09/22/influencer-marketing-7-essentielle-tipps-fuer-den-erfolg/)

