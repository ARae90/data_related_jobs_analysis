# Project1_group3

# Introduction to the Data-Related Job Market

PRESENTATION LINK : https://docs.google.com/presentation/d/1mPUwf7lgu8Lb8Lbk4uwzh39GZ8-XKJUqyTCxqrlMqzk/edit#slide=id.gc6f9e470d_0_0

# U.S. Bureau of Data Statistics - Rna Babikar
## Introduction

My focus was to have an overview of the employment sectors in the United State of America per state, what are the top sectors per employment, what are the employment projection for 2029 and What are the top 8 states for number of graduates by major. Data source used was U.S. Bureau of Data Statistics, in-order to create three bar charts representing, employment by industry sector, employment and projection for computer systems design and related services for 2029, and to show the number of graduates by major for top 8 states. 

## Limitations of datasets
• Missing data. 

## Questions with Associated Analysis: 
Q1. What are the top sectors per employment?
Q2. What are the employment and projection for computer system design and related services for (2029)?
Q3. What are the top 8 states for number of graduates by major?


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

# Analysis - David W. Mueller

    I compared each US state and the District of Columbia (DC) by the number of data scientist employment positions per 1,000 people 25 years of age and older with at least one bachelor’s degree. I also compared annual median wage for data scientist occupation for each US state and DC. Annual median wage included the 10th and 90th percentiles for each US state and DC. Data on employment were missing for five states: Delaware, New Mexico, North Dakota, Vermont, and Wyoming. Data on annual median wage were missing for four states, including Delaware, North Dakota, Vermont, and Wyoming, however, data for New Mexico was included.
    Data on employment were collected from the Bureau of Labor Statistics Occupational Employment and Wage Statistics May 2020 estimates for data scientists and all other mathematical science occupations. Data on educational attainment, degree type, and academic field were collected from the US Census 2019 American Community Survey, 1 year estimate.
    According to the 2018 Standard Occupational Classification System, a data scientist is defined as someone hired to develop and implement methods to transform raw data into meaningful information using data-oriented programming languages and visualization software. This includes the application of data mining, data modeling, natural language processing, and machine learning to extract, analyze, and present data from large structured and unstructured datasets (Bureau of Labor Statistics, 2020).
    I found that the five states with the highest employment of data scientists per 1,000 people 25 years of age and older with at least one bachelor’s degree included Illinois, Florida, North Carolina, Maryland, and Tennessee. All five states had over 1,000 total data scientist employment and from five to nearly ten positions per 1,000 people 25 and over with a bachelor’s degree in any field. Illinois had the highest employment per 1,000 people 25 and older with a bachelor’s degree, with 9.8 employment per person, and 3,290 total employment. Tennessee had the least employment and employment per 1,000 people 25 and older with a degree among the top five states. Employment was 1,280, with five per 1,000 people 25 and older with a degree. 
    The annual median wage for data scientists in Illinois was $96,500. The 10th percentile was $56,100 and the 90th percentile was $154,010. Tennessee had a lower annual median wage, at $78,750. The 10th percentile was $52,550. The 90th percentile was $135,860. The state with the highest annual median wage was California, equalling $127,310. It also had the greatest 90th percentile wage, at $197,890. California also had the largest number of raw employment, at 9,510. There was only one employment per 1,000 people 25 years and older with a bachelor’s degree. The five states with the highest annual median wage were California, New York, Washington, New Jersey, and Arizona. Of these, all were above $100,000. Arizona was the lowest with $111,900 annual median wage. Surprisingly, Arkansas’s annual 10th percentile wage was $80,310, the highestes in the US.

# About Occupational Employment and Wage Statistics (OEWS)

Estimates are made from three years of survey data, covering 1.1 million establishments and about 57 percent of the employment in the United States. Estimates are established for every May and November. This improves the reliability of estimates for detailed occupations in small geographical areas. Combining multiple years of data is necessary to obtain full coverage of the largest establishments. In order to reduce respondent burden, the OEWS survey samples these establishments with virtual certainty once every three years. Limitations associated with this estimation procedure are that it requires "updating" for the earlier years of data and limits the usefulness of OEWS data for time series analysis (Bureau of Labor Statistics, 2021).

# Definitions

## 2018 Standard Occupational Classification System (SOC) Definitions

    Data Scientists:
        Develop and implement a set of techniques or analytics applications to transform raw data into meaningful information using data-oriented programming languages and visualization software. Apply data mining, data modeling, natural language processing, and machine learning to extract and analyze information from large structured and unstructured datasets. Visualize, interpret, and report data findings. May create dynamic data reports. Excludes "Statisticians" (15-2041), "Cartographers and Photogrammetrists" (17-1021), and "Health Information Technologists and Medical Registrars" (29-9021).
        Illustrative examples: Business Intelligence Developer , Data Analytics Specialist , Data Mining Analyst , Data Visualization Developer

    Mathematical Science Occupations, all other:
        All mathematical scientists not listed separately.
        Illustrative examples: Harmonic Analyst , Mathematical Engineering Technician (Bureau of Labor Statistics, 2020)

## Occupational Employment and Wage Statistics (OEWS) Definitions

    Employment:
        The estimated total occupational employment (not including self-employed).

    Employment per 1000 jobs: 
        The number of jobs (employment) in the given occupation per 1,000 jobs in the given area.

    Location Quotient (State, metropolitan, and nonmetropolitan statistical area estimates only):
        The ratio of an occupation's share of employment in a given area to that occupation's share of employment in the U.S. as a whole. For example, an occupation that makes up 10 percent of employment in a specific metropolitan area compared with 2 percent of U.S. employment would have a location quotient of 5 for the area in question.

    Median Wage:
        The estimated 50th percentile of the distribution of wages based on data collected from employers in all industries; 50 percent of workers in an occupation earn less than the median wage, and 50 percent earn more than the median wage (Bureau of Labor Statistics, 2021).

# Citations and Data Sources

## Occupational Employment and Wages, May 2020
Data Scientists and Mathematical Science Occupations, All Other

    Bureau of Labor Statistics. (2021). Occupational Employment and Wage Statistics, May 2020. [Data set]. U.S. Department of Labor. https://www.bls.gov/oes/current/oes152098.htm

## National Employment Matrix
Data scientists and mathematical science occupations, all other
Employment by industry, occupation, and percent distribution, 2019 and projected 2029.

    Bureau of Labor Statistics. (2020). Employment Projections. [Data set]. U.S. Department of Labor. https://data.bls.gov/projections/nationalMatrix?queryParams=15-2098-248&ioType=o

## Detailed Field of Bachelor’s Degree for First Major for the Population 25 Years and Over
2019: American Community Survey 1-Year Estimates 
TableID: B15010

    U.S. Census Bureau. (2020). 2019 American Community Survey 1-Year. [Data set]. U.S. Census Bureau. https://data.census.gov/cedsci/table?q=B15010&tid=ACSDT1Y2019.B15010

## World Population Review
    World Population Review. (2021). Cost Of Living Index By State 2021. [Data set]. World Population Review. https://worldpopulationreview.com/state-rankings/cost-of-living-index-by-state

## North American Industry Classification System (NAICS) at BLS
    Bureau of Labor Statistics. (2020, February 27). North American Industry Classification System (NAICS) at BLS. https://www.bls.gov/bls/naics.htm

## 2018 Standard Occupational Classification System
    Bureau of Labor Statistics. (2020, April 17). 2018 Standard Occupational Classification System. https://www.bls.gov/soc/2018/home.htm


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

# Analysis - David W. Mueller

    I compared each US state and the District of Columbia (DC) by the number of data scientist employment positions per 1,000 people 25 years of age and older with at least one bachelor’s degree. I also compared annual median wage for data scientist occupation for each US state and DC. Annual median wage included the 10th and 90th percentiles for each US state and DC. Data on employment were missing for five states: Delaware, New Mexico, North Dakota, Vermont, and Wyoming. Data on annual median wage were missing for four states, including Delaware, North Dakota, Vermont, and Wyoming, however, data for New Mexico was included.
    Data on employment were collected from the Bureau of Labor Statistics Occupational Employment and Wage Statistics May 2020 estimates for data scientists and all other mathematical science occupations. Data on educational attainment, degree type, and academic field were collected from the US Census 2019 American Community Survey, 1 year estimate.
    According to the 2018 Standard Occupational Classification System, a data scientist is defined as someone hired to develop and implement methods to transform raw data into meaningful information using data-oriented programming languages and visualization software. This includes the application of data mining, data modeling, natural language processing, and machine learning to extract, analyze, and present data from large structured and unstructured datasets (Bureau of Labor Statistics, 2020).
    I found that the five states with the highest employment of data scientists per 1,000 people 25 years of age and older with at least one bachelor’s degree included Illinois, Florida, North Carolina, Maryland, and Tennessee. All five states had over 1,000 total data scientist employment and from five to nearly ten positions per 1,000 people 25 and over with a bachelor’s degree in any field. Illinois had the highest employment per 1,000 people 25 and older with a bachelor’s degree, with 9.8 employment per person, and 3,290 total employment. Tennessee had the least employment and employment per 1,000 people 25 and older with a degree among the top five states. Employment was 1,280, with five per 1,000 people 25 and older with a degree. 
    The annual median wage for data scientists in Illinois was $96,500. The 10th percentile was $56,100 and the 90th percentile was $154,010. Tennessee had a lower annual median wage, at $78,750. The 10th percentile was $52,550. The 90th percentile was $135,860. The state with the highest annual median wage was California, equalling $127,310. It also had the greatest 90th percentile wage, at $197,890. California also had the largest number of raw employment, at 9,510. There was only one employment per 1,000 people 25 years and older with a bachelor’s degree. The five states with the highest annual median wage were California, New York, Washington, New Jersey, and Arizona. Of these, all were above $100,000. Arizona was the lowest with $111,900 annual median wage. Surprisingly, Arkansas’s annual 10th percentile wage was $80,310, the highestes in the US.

# About Occupational Employment and Wage Statistics (OEWS)

Estimates are made from three years of survey data, covering 1.1 million establishments and about 57 percent of the employment in the United States. Estimates are established for every May and November. This improves the reliability of estimates for detailed occupations in small geographical areas. Combining multiple years of data is necessary to obtain full coverage of the largest establishments. In order to reduce respondent burden, the OEWS survey samples these establishments with virtual certainty once every three years. Limitations associated with this estimation procedure are that it requires "updating" for the earlier years of data and limits the usefulness of OEWS data for time series analysis (Bureau of Labor Statistics, 2021).

# Definitions

## 2018 Standard Occupational Classification System (SOC) Definitions

    Data Scientists:
        Develop and implement a set of techniques or analytics applications to transform raw data into meaningful information using data-oriented programming languages and visualization software. Apply data mining, data modeling, natural language processing, and machine learning to extract and analyze information from large structured and unstructured datasets. Visualize, interpret, and report data findings. May create dynamic data reports. Excludes "Statisticians" (15-2041), "Cartographers and Photogrammetrists" (17-1021), and "Health Information Technologists and Medical Registrars" (29-9021).
        Illustrative examples: Business Intelligence Developer , Data Analytics Specialist , Data Mining Analyst , Data Visualization Developer

    Mathematical Science Occupations, all other:
        All mathematical scientists not listed separately.
        Illustrative examples: Harmonic Analyst , Mathematical Engineering Technician (Bureau of Labor Statistics, 2020)

## Occupational Employment and Wage Statistics (OEWS) Definitions

    Employment:
        The estimated total occupational employment (not including self-employed).

    Employment per 1000 jobs: 
        The number of jobs (employment) in the given occupation per 1,000 jobs in the given area.

    Location Quotient (State, metropolitan, and nonmetropolitan statistical area estimates only):
        The ratio of an occupation's share of employment in a given area to that occupation's share of employment in the U.S. as a whole. For example, an occupation that makes up 10 percent of employment in a specific metropolitan area compared with 2 percent of U.S. employment would have a location quotient of 5 for the area in question.

    Median Wage:
        The estimated 50th percentile of the distribution of wages based on data collected from employers in all industries; 50 percent of workers in an occupation earn less than the median wage, and 50 percent earn more than the median wage (Bureau of Labor Statistics, 2021).

# Citations and Data Sources

## Occupational Employment and Wages, May 2020
Data Scientists and Mathematical Science Occupations, All Other

    Bureau of Labor Statistics. (2021). Occupational Employment and Wage Statistics, May 2020. [Data set]. U.S. Department of Labor. https://www.bls.gov/oes/current/oes152098.htm

## National Employment Matrix
Data scientists and mathematical science occupations, all other
Employment by industry, occupation, and percent distribution, 2019 and projected 2029.

    Bureau of Labor Statistics. (2020). Employment Projections. [Data set]. U.S. Department of Labor. https://data.bls.gov/projections/nationalMatrix?queryParams=15-2098-248&ioType=o

## Detailed Field of Bachelor’s Degree for First Major for the Population 25 Years and Over
2019: American Community Survey 1-Year Estimates 
TableID: B15010

    U.S. Census Bureau. (2020). 2019 American Community Survey 1-Year. [Data set]. U.S. Census Bureau. https://data.census.gov/cedsci/table?q=B15010&tid=ACSDT1Y2019.B15010

## World Population Review
    World Population Review. (2021). Cost Of Living Index By State 2021. [Data set]. World Population Review. https://worldpopulationreview.com/state-rankings/cost-of-living-index-by-state

## North American Industry Classification System (NAICS) at BLS
    Bureau of Labor Statistics. (2020, February 27). North American Industry Classification System (NAICS) at BLS. https://www.bls.gov/bls/naics.htm

## 2018 Standard Occupational Classification System
    Bureau of Labor Statistics. (2020, April 17). 2018 Standard Occupational Classification System. https://www.bls.gov/soc/2018/home.htm


# Indeed Data-Related Job Analysis - Amanda Pesch

## Introduction
Most of us will be thinking about where the jobs in our field exist, some within Michigan, some maybe remote.  So how can we better visualize what's out there?


My exploration focused on understanding the current data-related job market in Michigan and the U.S.
- I first extracted two .csv datasets using an open-source Indeed webscraping tool found on GitHub (https://github.com/vittoriotriassi/jobs_scraper).  One dataset was for data-related current jobs (pulled 4/30/21) posted on Indeed within Michigan.  "Data-related" meaning Data Analyst, Data Scientist, Data Engineer, Business Intelligence Analyst, etc. using the keyword "data" in the job title.
- The second dataset was for "Data Analyst" keyword-only current jobs (pulled (4/30/21) within the entire U.S.  

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

