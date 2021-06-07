# Indeed Data-Related Job Analysis

## Introduction
Most of us Data Analysts will be thinking about where the jobs in our field exist, some within Michigan, some maybe remote.  So how can we better visualize what's out there?

My exploration focused on understanding the current data-related job market in Michigan and the U.S. 

- I first extracted two .csv datasets using an open-source Indeed webscraping tool found on GitHub (https://github.com/vittoriotriassi/jobs_scraper).  One dataset was for data-related current jobs (pulled 4/30/21) posted on Indeed within Michigan (called "Current MI Data Jobs.csv").  "Data-related" meaning Data Analyst, Data Scientist, Data Engineer, Business Intelligence Analyst, etc. using the keyword "data" in the job title.
- The second dataset was for "Data Analyst" keyword-only current jobs (pulled (4/30/21) within the entire U.S. (called "U.S. Data Analyst Jobs").  
- The `gmaps` library was used to obtain a map of Michigan.

## Limitations of the datasets
- Both datasets did not include search criteria for level of experience (entry-level, senior, etc.).
- In the Michigan dataset, there were postings with the location of "Michigan" - these were cleaned out of the dataframes, any "United States" location postings were kept for the remote work analysis. 

## Questions with Associated Analysis
- Q: If we were to visualize the hotspots for data-related jobs on a map of Michigan, where would those geographical hotspots be?  Where would there be "cooler" areas with less jobs?  Within that map, can we pinpoint the job locations and company?  What are the top three locations with the most data-related jobs posted?
  - See google map with heatmap layer, marker layer, and symbol layer.  The heatmap is showing that most data-related jobs exist on the East side of Michigan (metro Detroit to Ann Arbor region).  The markers depict a sample job from each city with the job title, company, city, and URL.  The three yellow symbols highlight the three cities with the most job postings (Detroit, Ann Arbor, and Dearborn).

![Image of Gmap](https://github.com/APesch90/data_related_jobs_analysis/blob/master/Indeed_Layered_Gmap_Screenshot.png)

- Q: In Michigan, what are the top five *cities* in Michigan with the most data-related job postings currently?

  - *See bar chart in the .ipynb.*   
  - *See bar chart in the .ipynb.*
  - The job counts from these top five cities account for 63% of the overall data-related jobs in Michigan.   
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

