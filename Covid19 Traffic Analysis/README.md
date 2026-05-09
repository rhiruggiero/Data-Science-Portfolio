**COVID-19 Traffic Analysis**

A project completed for my master’s in data science degree.

**Introduction**

This project uses R to see how traffic patterns were affected by the COVID-19 Pandemic.

**Background**

The Covid-19 pandemic changed the way that many people interact with the world.   The pandemic disrupted lives, caused panic and altered daily routines.  Many predictions of habits for the future did not assume that a pandemic would occur as well.  Data science can be used to see how much things have changed, specifically with transportation.  People began working from home, were told to stay 6 feet apart from others and some lost their jobs and income.  Many less cars were on the road and people were not travelling as much.  I want to see how the pandemic affected transportation and whether people now travel mainly by car, if they have returned to using public transportation or have used other means.  This is an important topic as it can show if CO2 emissions have generally increased (and predict whether they will continue to increase) which can help influence various policies or actions that can be taken to decrease them.  Alternatively, it can show if emissions have declined that we can focus more on other areas of concern.  It also can show us how traffic patterns may have changed and if there will be more vehicles on the road than previously, which could lead to more areas needing maintenance.  Data science can help figure out trends in the data.

**Data**

Linkes to the data sources:
- https://data.census.gov/table/ACSDT1Y2019.B08141?q=transportation%20in%20the%20united%20states%20in%202019
- https://data.census.gov/table/ACSDT5Y2020.B08141?q=transportation%20in%20the%20united%20states%20in%202020
- https://data.census.gov/table/ACSDT1Y2021.B08141?q=transportation%20in%20the%20united%20states%20in%202021
- https://data.bts.gov/Research-and-Statistics/Transportation-Services-Index-and-Seasonally-Adjus/bw6n-ddqk/about_data 
- https://data.ny.gov/Transportation/MTA-Daily-Ridership-Data-Beginning-2020/vxuj-8kew/about_data
- https://new.mta.info/open-data


**Tools used for this project and required packages:**

For this project I will use ggplot2 to help create plots to help discover if the data is normal and to also help identify any outliers in the data that might be affecting the results. I will also use dplyr to help filter the data to my needs and to clean it up.   I also may need to use the purrr package to help remove any “NA” values in my data sets however most of them do not seem to have any missing values. 
	
