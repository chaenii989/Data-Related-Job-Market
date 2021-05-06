# Project1_group3
Introduction to the Data-Related Job Market

Amanda's Analysis:
![Image of Indeed](https://cdn.worldvectorlogo.com/logos/indeed-logo.svg)

Most of us will be thinking about where the jobs in our field exist, some within Michigan, some maybe remote.  So how can we better visualize what's out there?

My exploration focused on understanding the current data-related job market in Michigan and the U.S.
- I first extracted two .csv datasets using an open-source Indeed webscraping tool found on GitHub (https://github.com/vittoriotriassi/jobs_scraper).  One dataset was for data-related current jobs (pulled 4/30/21) posted on Indeed within Michigan.  "Data-related" meaning Data Analyst, Data Scientist, Data Engineer, Business Intelligence Analyst, etc. using the keyword "data" in the job title.  - The second dataset was for "Data Analyst" keyword-only current jobs (pulled (4/30/21) within the entire U.S.

Limitations of the datasets:
- Both datasets did not include search criteria for level of experience (entry-level, senior, etc.)
- In the Michigan dataset, there were postings with the location of "Michigan" - these were cleaned out of the dataframes, any "United States" location postings were kept for the remote work analysis. 

Questions with Associated Analysis:
- Q: In Michigan, what *companies* have the most data-related job postings currently?  
- Q: In Michigan, what *cities* in Michigan have the most data-related job postings currently?
- Q: With today's evolving work climate, what percentage of the Data Analyst jobs in the U.S. right now are *remote*?

Analysis:


Heat map for current jobs location in Michigan - top 3 companies with the most # of current openings as special icon - Amanda
Count by Company - bar chart - Amanda
Count by City - bar chart - Amanda
% Remote positions in US (pie chart) - Amanda
