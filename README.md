# Project1_group3
# Introduction to the Data-Related Job Market

PRESENTATION LINK : https://docs.google.com/presentation/d/1mPUwf7lgu8Lb8Lbk4uwzh39GZ8-XKJUqyTCxqrlMqzk/edit#slide=id.gc6f9e470d_0_0

# U.S. Bureau of Data Statistics - Rna Babikar
## Introduction

My focus was to have an overview of the employment sectors in the United State of America per state, what are the top sectors per employment, what are the employment projection for 2029 and What are the top 8 states for number of graduates by major. Data source used was U.S. Bureau of Data Statistics, in-order to create three bar charts representing, employment by industry sector, employment and projection for computer systems design and related services for 2029, and to show the number of graduates by major for top 8 states. I also comparing the degrees in computer mathematics and statistics by regions using boxplot. Data source used was https://raw.githubusercontent.com/cphalpert/census-regions/master/us%20census%20bureau%20regions%20and%20divisions.csv.

## Limitations of datasets
• Missing data. 

## Questions with Associated Analysis: 
Q1. What are the top sectors per employment?
Q2. What are the employment and projection for computer system design and related services for (2029)?
Q3. What are the top 8 states for number of graduates by major?
Q4. Comparing the degrees in computers, mathematics and statistics by region?

## Analysis: 
• A: 1. Professional, scientific, and technical services
     2. Finance and insurance
     3. Management of companies and enterprises
     4. Information
     5. Educational services
     6. Health care and social assistance
     7. Wholesale trade
     8. Other services
     9. Transportation and warehousing
     11. Real estate and rental and leasing
     12. Arts, entertainment, and recreation construction
      Fig (1)
      
 • A: Employment Percent will increase by 48.7% in 2029. Fig (2).
 
 • A: The top 8 states for number of graduates by major Fig (3).
   
     1. California
     2. Texas
     3. New York
     4.Florida
     5.Illinois
     6.Virginia
     7.New Jersey
     8.Pennsylvania

  • A: No significant differences between degrees in computers, mathematics and statistics by region
     Fig (4)
     
     

# Glassdoor Data-Related Job Analysis - Chloe Lee
## Introduction

Data-related job is one of the new fields and is expected to grow in the future as the era of the Fourth Industrial Revolution arrives. My exploration focused to find out and visualize which industries are currently looking for data-related job in the United States, which companies are there, and which states are looking for the most by using ‘glassdoor’ information.

• Retrieved three csv files from kaggle(Kaggle.com/datasets). 
• Each csv files are Data Analyst, Data Scientist, Data Engineer job listings scraped from glassdoor which includes job title, salary, company name, location etc. 
• Concatenated all csv files to one ‘final’ csv file. 
• From the final data frame, visualized industry and company ranking with bar chart. 
• By using geopy, retrieved latitude and longitude for each state.

## Limitations of the datasets: 
• All datasets did not include search criteria for level of experience (entry-level, senior, etc.) 
• Some salary estimation has broad ranges to use (ex. 12K to 200K). 
• Dataset did not include all states.

## Questions with Associated Analysis: 
• Q: In US, what are the Top 5 Industries have the most data-related job postings currently? 
• Q: In US, what are the Top 5 companies have the most data-related job postings currently? 
• Q: Which states are looking for the most data-related job?

## Analysis: 
• A: 1. IT Services (1,152 job postings) 
     2. Staffing & Outsourcing (838 job postings) 
     3. Computer Hardware & Software (619 job postings) 
     4. Internet (448 job postings) 
     5. Health Care Services & Hospitals (399 job postings) 
     (Bar chart 1)
     
• A: 1. Apple (88 job postings) 
     2. Staffigo Technical Services, LLC (86 job postings) 
     3. Amazon (78 job postings) 
     4. IBM (64 job postings) 
     5. Diverse Lynx (62 job postings) 
     (Bar chart 2)

• A: 1. New York, NY (800) 
     2. Chicago, IL (652) 
     3. Austin, TX (625) 
     4. San Diego, CA (561) 
     5. Houston, TX (490)
     (Heatmap with markers) - screenshot:IMAGE 



# Indeed Data-Related Job Analysis - Amanda Pesch

## Introduction
Most of us will be thinking about where the jobs in our field exist, some within Michigan, some maybe remote.  So how can we better visualize what's out there?

My exploration focused on understanding the current data-related job market in Michigan and the U.S. 

Link to my .ipynb: (https://github.com/chaenii989/Project1_group3/blob/d56273d8b47b5977c93a43231a1fae4e60c7e022/A.Pesch%20-%20Indeed%20Web%20Scraped%20Data%20Analysis.ipynb)

- I first extracted two .csv datasets using an open-source Indeed webscraping tool found on GitHub (https://github.com/vittoriotriassi/jobs_scraper).  One dataset was for data-related current jobs (pulled 4/30/21) posted on Indeed within Michigan (called "Current MI Data Jobs.csv").  "Data-related" meaning Data Analyst, Data Scientist, Data Engineer, Business Intelligence Analyst, etc. using the keyword "data" in the job title.
- The second dataset was for "Data Analyst" keyword-only current jobs (pulled (4/30/21) within the entire U.S. (called "U.S. Data Analyst Jobs").  
- The `gmaps` library was used to obtain a map of Michigan.

## Limitations of the datasets
- Both datasets did not include search criteria for level of experience (entry-level, senior, etc.).
- In the Michigan dataset, there were postings with the location of "Michigan" - these were cleaned out of the dataframes, any "United States" location postings were kept for the remote work analysis. 

## Questions with Associated Analysis
- Q: If we were to visualize the hotspots for data-related jobs on a map of Michigan, where would those geographical hotspots be?  Where would there be "cooler" areas with less jobs?  Within that map, can we pinpoint the job locations and company?  What are the top three locations with the most data-related jobs posted?
  - See google map with heatmap layer, marker layer, and symbol layer.  The heatmap is showing that most data-related jobs exist on the East side of Michigan (metro Detroit to Ann Arbor region).  The markers depict a sample job from each city with the job title, company, city, and URL.  The three yellow symbols highlight the three cities with the most job postings (Detroit, Ann Arbor, and Dearborn).

- Q: In Michigan, what are the top five *cities* in Michigan with the most data-related job postings currently?
  - *See bar chart in the .ipynb.*
  - The job counts from these top five cities account for 63% of the overall data-related jobs in Michigan.   
  1. Detroit (20 jobs)
  2. Ann Arbor (10)
  3. Dearborn (7)
  4. Troy (4)
  5. Warren (4)
     
- Q: In Michigan, what are the top five *companies* in Michigan with the most data-related job postings currently? 
  -  *See bar chart in the .ipynb.*
  -  The job counts from these top five companies account for 21% of the overall data-related jobs in Michigan.
  1. Synergy Solutions (6 jobs)
  2. General Motors (3)
  3. Coupa (2)
  4. Ford Motor Company (2)
  5. Hearst Media Services (2)

   
- Q: With today's evolving work environment, how many & what percentage of the Data Analyst jobs posted in the U.S. right now are *remote*?
  - There are 6813 Data Analyst jobs currently posted in the US on Indeed.  There are **490** remote Data Analyst jobs and 6323 on-site jobs.
  - **7.2%** of Data Analyst jobs posted in the US are remote, 92.8% are on-site jobs.  
  - *See pie chart in the .ipynb.*



**Bureau of Labor Statistics Data Scientist Job Market – John Burke**

**## Introduction**
Most of us will be looking for a new data related job once we finish this class.  As data related jobs are growing in the United States, I investigated which states would be best to apply for Data Scientist positions based on job and salaries data from the Bureau of Labor Statistics and the Cost-of-Living index provided from the World Population Review website.

Imported 2 CSV files
-  First csv file was from the Bureau of Labor Statistics using the Occupational Employment and Wage Statistics Query System.  This dataset extracted employment and salary information for Data Scientists per state in the United States.
-  Second CSV file contained information regarding the cost of living per state from the World Population Review.  The cost-of-living index is based on sustaining a certain standard of living by affording basic needs such as housing, food, healthcare, and more.

## Limitations of the datasets

-  Bureau of Labor Statistics dataset did not separate Data Scientist employment and salary data based on experience levels (entry-level, senior, lead, etc.)
-  Bureau of Labor Statistics did not have information on Delaware, North Dakota, Vermont, Wyoming.  These states were eliminated from the dataset.
-  Specific calculation to generate the cost-of-living index was not shared on the World Population Review.

## Questions with Associated Analysis
With most of us looking to apply for Data related jobs after this class, I wanted to answer what states hired the most Data Scientists, what states based on mean salaries pay their Data Scientists the most, and show a scatter plot explaining which states would be the best places to apply for Data Scientist positions based on mean salary and the cost of living per state. 

Q1:  What states currently have the most data scientist positions in the state?
     1.	California (9,510)
     2.	Texas (4,310)
     3.	New York (3,950)
     4.	Illinois (3,290)
     5.	Washington (2,610)

Q2:  What states pay their Data Scientists the most?  
     1.	California ($129,060)
     2.	New York ($124,240)
     3.	Washington ($118,320)
     4.	North Carolina ($117,370)
     5.	New Jersey ($116,250)

Q3:  Based on linear regression on the Data Scientist average salaries and cost of living per state, show a scatter plot showing which states are the best to apply to based on the salary you’ll make vs the cost of living per living in the state?

![image](https://user-images.githubusercontent.com/79127355/117588656-d2ca9c80-b0f2-11eb-9f5f-b69dd8f19193.png)

