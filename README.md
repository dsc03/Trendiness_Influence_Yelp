# Not All Users are Equal
## Using Dynamic-Time-Warping, Unsupervised Clustering &amp; Network Analysis to Identify Yelp’s Most ‘Trendy’ &amp; Influential Users

---
## Overview:

This project was done with the goal of creating a foundational analysis for identifying the most 'trendy' & influential users on Yelp. One key component that I was particularly excited about with this project was trying to take an incredibly subjective concept of 'trendiness' and try to establish a technical, concrete definition for it that was well supported by the data.

The dataset I worked with is from Yelp's most recent Data Challenge, and the analysis in this notebook was done for businesses in the city of Cleveland. Much of the time was spent performing cleaning, filtering, and shaping the original dataset, and to make it easier to follow the basic logic & flow of my work, I have excluded most of that code from the three Jupyter Notebooks. The notebooks should be viewed in the following order:

- **Yelp Time-Series Analysis**: includes **dynamic-time-warping & unsupervised clustering** work, which was used to classify businesses as 'trending' or 'not trending'.

- **Yelp Network Analysis**: includes **network analysis** for the businesses, the trendy-reviewers, and the individuals they influenced.

- **The Value of Influencer's Case Study**: includes a **case-study** of Porco's Lounge & Tiki Room, and the difference that having trendy, influential reviewers can have on a businesses' early growth & presence on Yelp.

**For an in-depth, less-technical explanation of my work, you can read my Medium post here.

---
## The Value this Analysis Provides:
For both Yelp & local businesses, knowing who the most trendy and influential reviewers are is critical. 

### Value for Yelp: Better Target Advertising & Value Proposition
Yelp’s business model & main revenue stream revolves around advertising local businesses on their platform. For advertising businesses, achieving high conversion rates and earning large profit margins are critical for long-term sustainability. By better understanding who the most trendy & influential users are in a given city, Yelp can increase their ad-conversion rates for cities, and can thus command a greater premium on their advertising and increase their profit margins.

### Value for Local Businesses: Lower Customer Acquisition Costs
For local businesses, every dollar spent on customer acquisition needs to be used optimally. Early-on, most local businesses have little to no cash to spend on marketing & customer acquisition, so they need to be very selective and strategic about who they target and how they target them. However, if local businesses are able to efficiently target the most trendy people (those individuals who are willing to give the business a try before anyone else is) and the most influential people, then they place themselves in the best position to grow early-on while also decreasing their customer acquisition costs.

**Consider the following scenario**: a new local business wants to acquire new customers through an advertising campaign, and has asked Yelp to advertise on their platform. Yelp, in return, wants to achieve a high ad-conversion rate and achieve optimal bring as many new customers to that business as possible. By knowing which reviewers are the most influential early adopters (our trendsetters), Yelp is able to target these individuals and puts themselves and the local businesses in the best position to achieve optimal growth and returns.

---
## Moving Forward
The beautiful thing about working on a data mining project like this is that there are ENDLESS possibilities to explore. There is always a different avenue to explore and there is so much more work that needs to be done. For me, there are 3 specific areas of interest to build-on:

- 2nd-degree-connections: What does the level of influence for our trendiest reviewers look like at the 2nd-degree level? We sort of touched upon this already with eigenvector centrality, but we can still be much more rigorous in quantifying this.
- Categories: A user may be influential when reviewing about Mexican restaurants, but not when reviewing about Yoga studios. Understanding this is critical for Yelp advertising model, and adding it into our analysis will give us another of rigor and classification.
- City-Level-Modeling: There are 10 other cities in this dataset, 6 in North America and 4 in Europe. It would be interesting to see the different levels of trendiness & influence at the city-level and even compare the characteristics & attributes of our most trendy & influential reviewers.


