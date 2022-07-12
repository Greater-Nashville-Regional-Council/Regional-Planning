# **Comprehensive Plans**

## *Table of Contents*  
+ Overview  
+ Data Prep  
+ Calculations  

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

From the *2010 American Community Survey 5-Year Estimates*
**
+

From the *American Community Survey 5-Year Estimates*  
+ B01001_001E Series: Age by Sex  
+ B01001A - I Series: Race and Ethnicity  
+ Variable B25010_001E: Average Household Size  
+ B27001 Series: Healthcare Coverage by Age and Sex  
+ B27002 Series: Private Healthcare Coverage by Age and Sex  
+ B27003 Series: Public Healthcare Coverage by Age and Sex  
+ Variable B25001_001E: Total Housing Units  
+ B25002 Series: Occupancy  
+ B25003 Series: Tenure  
+ B25024 Series: Units in Structure  
+ B11001 Series: Household Type  
+ Variable B19013_001E: Median Household Income  
+ B25091 Series: Cost Burden by Tenure  
+ B25097 Series: Home Value  
+ B25034 Series: Year Structure Built  
+ B08006 Series: Commute Mode  
+ B08014 Series: Vehicles  
+ B05006 Series: Place or Origin for Foreign-Born Population  
+ B16007 Series: Language Spoken at Home by Age Population 5+  
+ B15003 Series: Educational Attainment  
+ B08128 Series: Class of Worker  
+ B23001 Series: Labor Force Status for the Civilian Population by Sex  
+ Variable B19301_001E: Per Capita Personal Income in the Past 12 Months  
+ B07001 Series: Geographic Mobility in the Past Year by Age  
+ B25044 Series: Vehicles by Tenure  
+ C24030 Series: Industry Employment  
+ C24010 Series: Occupational Employment  
