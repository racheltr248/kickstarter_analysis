# Kickstarting with Excel

## Overview of Project
Up-and-coming playwright Louise Belcher intends to launch a Kickstarter to fund her play in the United States, *Fever*. She estimates a budget of over $10,000. 

### Purpose
The purpose of this project was to analyze other crowdfunding data, specifically within the United States and the theater industry. This analysis will determine factors that make for a successful crowdfunding campaign and help Louise Kickstart her own project successfully. 

## Analysis and Challenges
To begin the analysis, I gathered data from over 4,000 Kickstarter projects. The projects ranged in categories, locations, goals, launch dates, and outcomes. The data was represented in a variety of forms, including text, numerical, and unconverted UNIX dates. 

First, I needed to create some additional columns for subcategory of projects so we could compare Louise's goal of crowdfunding a play to other examples of play crowdfunding. It was important to convert the UNIX dates into a more recognizable format in order to analyze the impact of launch dates. There is a worksheet that computes the central tendancy and spread based on successful and failed projects, which informed the final analysis of outcomes based on goals.  

The data analysis provided useful information that can aid Louise in achieving her goals. Based on parent category outcomes, Kickstarters in support of theater are very popular, far exceeding other kinds of Kickstarters. 

![This chart shows a comparison of the different parent categories of Kickstarters in the United States](/Resources/Parent_Category_Outcomes_US.png)

Of the theater projects that have been submitted for crowdfunding, plays have been both the most popular and the most successful. 
![This chart shows a comparison of the different subcategories of theater projects that have been submitted for Kickstarters in the United States](/Resources/Subcategory_Outcomes_Within_Theater_US.png)

### Analysis of Outcomes Based on Launch Date
Another important step of the data analysis was to determine the best time for Louise to launch her Kickstarter. According to the data, the most successful months for launching Kickstarters have been May and June, while the least successful are December, January, and March. 
![This chart shows a comparison of the most successful theater Kickstarter launches by month](/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Since Louise estimated a budget of over $10,000, I checked to see the rate at which Kickstarters are funded based on goals. Perhaps unsurprisingly, Kickstarters with lower goals are more readily funded. 
![This chart shows a comparison of the most successful play Kickstarters by goal](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
This dataset did not present too many difficulties, although thinking through some of the conditional language was a bit challenging. The biggest difficulty I face right now is that I have never had formal statistics training, so I am attempting to wrap my head around that, as well.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
     1. The best months to launch Kickstarters are May and June
     2. The worst months to launch Kickstarters are December, January, and March

- What can you conclude about the Outcomes based on Goals?
     - The lower your goal, the more likely it is to be funded. The sweet spot is between $1000-$4999, which has a 73% likelihood of being funded. 

- What are some limitations of this dataset?
     1. This dataset runs between 2011-2017, which means it is only a five-year time range
     2. Country is listed with a 2-letter code, so it is possible that not all of the entries would clearly understandable to everyone without conversion
     3. Deeper granularity of backer information could be useful

- What are some other possible tables and/or graphs that we could create?
     1. Percentage of theater projects funded vs unfunded
     2. Best location for funding similar projects
     3. Deadline comparison
