# Project1_group3

Introduction to the Data-Related Job Market


Chloe's Analysis:

Data-related job is one of the new fields and is expected to grow in the future as the era of the Fourth Industrial Revolution arrives. My exploration focused to find out and visualize which industries are currently looking for data-related job in the United States, which companies are there, and which states are looking for the most by using ‘glassdoor’ information.

• Retrieved three csv files from kaggle(Kaggle.com/datasets). 
• Each csv files are Data Analyst, Data Scientist, Data Engineer job listings scraped from glassdoor which includes job title, salary, company name, location etc. 
• Concatenated all csv files to one ‘final’ csv file. 
• From the final data frame, visualized industry and company ranking with bar chart. 
• By using geopy, retrieved latitude and longitude for each state.

Limitations of the datasets: 
• All datasets did not include search criteria for level of experience (entry-level, senior, etc.) 
• Some salary estimation has broad ranges to use (ex. 12K to 200K). 
• Dataset did not include all states.

Questions with Associated Analysis: 
• Q: In US, what are the Top 5 Industries have the most data-related job postings currently? 
• Q: In US, what are the Top 5 companies have the most data-related job postings currently? 
• Q: Which states are looking for the most data-related job?

Analysis: 
• A: 1. IT Services (1,152 job postings) 
     2. Staffing & Outsourcing (838 job postings) 
     3. Computer Hardware & Software (619 job postings) 
     4. Internet (448 job postings) 
     5. Health Care Services & Hospitals (399 job postings) 
• A: 1. Apple (88 job postings) 
     2. Staffigo Technical Services, LLC (86 job postings) 
     3. Amazon (78 job postings) 
     4. IBM (64 job postings) 
     5. Diverse Lynx (62 job postings) 
• A: 1. New York, NY (800) 
     2. Chicago, IL (652) 
     3. Austin, TX (625) 
     4. San Diego, CA (561) 
     5. Houston, TX (490)
