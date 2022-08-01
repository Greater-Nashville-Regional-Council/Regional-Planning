# **Comprehensive Plans**

## *Table of Contents*  
+ Overview  
+ Data Sourcing
+ Data Prep  

## Overview

This is a template for recreating the data pull and calculations used for Comprehensive Plans.  

## Data Sourcing    

Data is sourced to represent three different time frames. 2000, 2010 or 2006-2010, and 2016-2020 or 2020. The data from 2000 is made up from two sources: the SF1 product, standard population and housing numbers usually provided by the Decennial Census efforts; and the SF3 product, a very robust database relative to other Decennial products. The 2010 data is taken from either the 2010 SF1 product, again providing standard population and housing numbers, as well as from the 2006 - 2010 American Community Survey 5-Year Estimates. While these are both "2010 data", there is a caveat not to consider them equally as the SF1 presents data *on* 2010 and the ACS presents a smoothed average representing the time period between 2006 and 2010. Finally, 2020 data is taken from either then 2020 redistricting Decennial Census data, giving less population and housing numbers than the SF1 table, or the 2016-2020 ACS 5-Year Estimates. Data sourcing decisions are made based on prioritizing true counts from Decennial Census products and availability, keeping in mind the difference between a 1-year point in time count and a smoothed average.

### 2000  

From the *2000 Decennial SF1*  
+ Variable P001001: Total Population  
+ P012: Sex by Age  
+ P003: Race  
+ P004: Hispanic or Latino, and Not Hispanic or Latino by Race  
+ Variable P017001: Average Household Size  
+ Variable H001001: Total Housing Units  
+ H003: Occupancy Status  
+ H004: Tenure  
+ P018: Household Size, Household Type, and Presence of Own Children  

From the *2000 Decennial SF3*  
+ Variable P001001: Total Population  
+ Variable HCT012001: Median Household Income  
+ P052: Household Income in 1999  
+ P037: Sex by Educational Attainment for the Population 25 Years and Over  
+ P049: Sex by Industry for the Employed Civilian Population 16 Years and Over  
+ P050: Sex by Occupation for the Employed Civilian Population 16 Years and Over  
+ P051: Sex by Class of Worker for the Employed Civilian Population 16 Years and Over  
+ PCT035: Sex by Age by Employment Status for the Population 16 Years and Over  
+ Variable P082001: Per Capita Income  
+ P087: Poverty Status by Age  
+ H094: Mortgage Status by Selected Monthly Owner Costs as a Percentage of Household Income in 1999  
+ H069: Gross Rent as a Percentage of Household Income in 1999  
+ Variable H076001: Median Home Value for Owner Occupied Units  
+ Variable H063001: Median Gross Rent for Renter Occupied Units  
+ Units in Structure: H030  
+ P030: Means of Transportation to Work  
+ H044: Tenure by Vehicles Available  
+ P039: Sex by Age by Armed Forces Status by Veteran Status for the Population 18 Years and Over  
+ Variable P041001: Tally of Total Disabilities  
+ P024: Residence in 1995 for the Population 5 Years and Over State and County Level  

### 2010  

From the *2010 Decennial SF1*  
**Note that although many variable names are the same as the 2000 Decennial Census, the nomenclature for naming tables changed between years as did some ways that different things were measured: race and ethnicity (Hispanic or Latino Origin is here measured by race where it was not in 2000 SF1), tenure (measured here by mortgage status, in 2000 it was measured only by homeowner versus renter), and household type (various differences between years).**
+ Variable P001001: Total Population  
+ P12: Sex by Age  
+ P3: Race  
+ P4: Hispanic or Latino Origin  
+ P5: Hispanic or Latino Origin by Race  
+ Variable H001001: Total Housing Units
+ Variable P017001: Average Household Size  
+ H3: Occupancy  
+ H4: Tenure **Note some change in variables between 2000 and 2010**  
+ P18: Household Type **Note some change in variables between 2000 and 2010**  

From the *2006 - 2010 American Community Survey 5-Year Estimates*
**
+ Variable B01001_001E: Total population  
+ Variable B25010_001E: Average Household Size  
+ B17001 Series: Poverty Status in the Past 12 Months by Sex by Age  
+ B25024 Series: Units in Structure  
+ B11001 Series: Household Type (Including Living Alone)
+ Variable B19013_001E: Median Household Income in the Past 12 Months (in 2010 Inflation-Adjusted Dollars)  
+ B19001 Series: Household Income in the Past 12 Months (in 2010 Inflation-Adjusted Dollars)  
+ B25091 Series: Mortgage Status by Selected Monthly Owner Costs as a Percentage of Household Income in the Past 12 Months  
+ B25070 Series: Gross Rent as a Percentage of Household Income in the Past 12 Months  
+ B08006 Series: Sex of Workers by Means of Transportation to Work  
+ B05006 Series: Place of Birth for the Foreign-Born Population in the United States  
+ B08128 Series: Means of Transportation to Work by Class of Worker  
+ B23001 Series: Sex by Age by Employment Status for the Population 16 Years and Over  
+ Variable B19301_001E: Per Capita Income in the Past 12 Months (in 2010 Inflation-Adjusted Dollars)  
+ B07001 Series: Geographical Mobility in the Past Year by Age for Current Residence in the United States  
+ B25044 Series: Tenure by Vehicles Available  
+ C24030 Series: Sex by Industry for the Civilian Employed Population 16 and Over  
+ C24010 Series: Sex by Occupation for the Civilian Employed Population 16 and Over  
+ B16004 Series: Age by Language Spoken at Home by Ability to Speak English for the Population 5 Years and Over  
+ B21001 Series: Sex by Age by Veteran Status for the Civilian Population 18 Years and Over  
+ C08134 Series: Means of Transportation to Work by Travel Time to Work  
+ B08511 Series: Means of Transportation to Work by Citizenship Status for Workplace Geography  
+ B15002 Series: Sex by Educational Attainment for the Population 25 Years and Over  

From the *2006 - 2010 American Community Survey 5-Year Estimate Subject Tables*  
+ Variable S0801_C01_046E: Average Commute Time to Work

### 2020

From the *2020 Decennial P.L. Redistricting Estimates*  
+ Series P1: Race
+ Series P2: Ethnicity  
+ Series H1: Occupancy Status  

From the *2016 - 2020 American Community Survey 5-Year Estimates*  
This data pull includes all of the series and variables from the 2006 - 2010 ACS 5 Year Estimate. If the table changed between estimates, the new series is included below, as well as new data:    
+ B01001_001E Series: Sex by Age
+ B01001Series: Sex by Age by Race and Ethnicity
+ B27001 Series: Health Insurance Coverage Status by Sex by Age  
+ B27002 Series: Private Healthcare Coverage by Sex by Age  
+ Variable B25001_001E: Housing Units    
+ B25003 Series: Tenure
+ B25097_001E Series: Mortgage Status by Median Value (Dollars)  
+ Variable B25064_001E: Median Gross Rent (Dollars)  
+ B25034 Series: Year Structure Built  
+ B15003 Series: Educational Attainment for the Population 25 Years and Over  
+ B08128 Series: Means of Transportation to Work by Class of Worker  
+ B18101 Series: Sex by Age by Disability Status  
+ B18102 Series: Sex by Age by Hearing Difficulty  
+ B18103 Series: Sex by Age by Vision Difficulty  
+ B18104 Series: Sex by Age by Cognitive Difficulty  
+ B18105 Series: Sex by Age by Ambulatory Difficulty  
+ B18106 Series: Sex by Age by Self-Care Difficulty  
+ C18108 Series: Age by Number of Disabilities    
+ B18107 Series: Sex by Age by Independent Living Difficulty  
+ B08134 Series: Means of Transportation to Work by Travel Time to Work  

From the *2016 - 2020 American Community Survey 5-Year Estimate Subject Tables*  
+ Variable S0801_C01_046E: Average Commute Time to Work

**Process:**  
The data pulls for the SF1 2000, SF3 2000, SF1 2010, ACS5YR '06-'10, PL 2020, and '16-'20 ACS5YR are all separate documents. The data pulls for the subject tables from both '06-'10 and '16-'20 are in one document together. The variables are compiled in a csv document called a "data guide", where each variable is listed along with column names generated by GNRC research that are common between documents and projects. These guides are imported into the notebook file and formatted as lists to be run through an API call. As per Census Bureau API constraints, 50 variables are pulled at once. Each pull formats the variable and column name lists for retrieving data at the county level, the state level, the national level, and the place level. So, one loop pulls 46 variables (including up to 4 names/geoid columns) for a set amount of places. This data is joined and formatted as a dataframe where custom regions (GNRC Region, GNRC 14 County operating area, and MPO region) are created, as well as calculations made for incorporated vs unincorporated county where places do not cross county lines. All data is exported at the end of each file.

## Data Prep  
The raw data from each document is respectively processed through a "calculations" file. These are simplest to keep separate as there are slight differences between each data series. The raw data is either used in a calculation as a part of a group, used to find percent of a whole, or simply renamed to fit the final product. New column names are consistent between files, and raw data is dropped as the process goes along. At their final points, all calculations and raw data-drops are in the same cell for ease of running code, but they are all clearly marked for expedient alterations. Data is exported both with the year appended to the column title, and without, for different kinds of figures.  

Next, all of these files are imported as dataframes and joined. Once in a wide-form dataframe with all years appended to the column title, and once as tidy formatted data with a column for either year, or time frame, where percent change and real change is calculated in a loop for every data point over all three time frames. Here, geographical filters are imposed so that data is ready to be visualized for a specific comprehensive plan.  

## Visualizations  
Data visualizations are produced for a variety of internal and external products. First is the internal technical document.
