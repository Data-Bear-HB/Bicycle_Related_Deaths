# Bicyclist_Deaths
Using Excel, an analysis of bicycle-related deaths for Oregon, Washington, and a comparison to the national level
___________________________________________________________________________
Data Sources:

-Population: [US Census Data](https://www.census.gov/data-tools/demo/idb/#/table?dashboard_page=country&COUNTRY_YR_ANIM=2025&menu=tableViz&CCODE_SINGLE=US&subnat_map_admin=ADM1&CCODE=US&TABLE_RANGE=2014,2023&TABLE_YEARS=2014,2015,2016,2017,2018,2019,2020,2021,2022,2023,2025&TABLE_USE_RANGE=Y&TABLE_USE_YEARS=Y&TABLE_STEP=1&TABLE_ADD_YEARS=2025)

-Bicycle Deaths: [Crash Stats with the National Highway Traffic Safety Administration](https://crashstats.nhtsa.dot.gov/#!/PublicationList/19)
__________________________________________________
## Introduction
Many people in the United States regularly commute by bicycle. In a collision between a car and cyclist, the cyclist, having no seatbelt, airbag, or external structure, is much more vulnerable to injury or death. Of course, there are other, non-car-related ways to die on a bicycle. Recently, there has been a rise of bicycle-related-deaths in the United States.  This analysis looks at this rising rate and compares Oregon, Washington, and national rates.

### The Why: 
I made this project in my statistical analysis class because I am a bicyclist myself and moved from Washington to Oregon a few years ago. It definitely *felt* less safe to ride a bicycle in Oregon over Washington, but I wanted to see if the data supported this. I also was interested to see if bicycle-related-deaths were on the rise. 

## Limitations: 
It could be gathered that not every state's transportation feels it in it's own best interest to report every bicycle crash injury or fatality. Therefore, we take these data collections in good faith.
________________________________________________
## Analysis
-The chart visualizations are created using Excel.
_______________________________________________
-Question 1: What is the national average rate of bicyclist deaths? Or, on average, how many people per year die riding a bicycle?

#1 Answer: Using the raw data from the [national rate of bicycle deaths from the 2014-2022](https://github.com/Data-Bear-HB/Bicycle_Related_Deaths/blob/main/raw_data/Bicycle%20Fatalities%20Data.xlsx) we can use statstical analysis (below) to find the average (mean) is 886.22 bicycle deaths per year.

min =	729, max =	1105, Range	R =	376, n =	9, sum =	7976, mean =	886.22222, median =	859, standard deviation =	109.68452
__________________________________________________________

Question 2: Is Oregon or Washinton safer to ride? Comparing Oregon and Washington, states with varying levels of bicycle safety infrastructure, which state has a lower rate of bicyclist deaths per population?

![Bicycle Deaths in Oregon and Washington chart](images/Bicycle_Deaths_in_Oregon_and_Washington.png)

#2 Answer: It would appear on first glance, that Washington has more bicycle related deaths. But on further inspection, if we look at bicycle deaths per state popluation, we see that Washington is signifcantly lower, nearly half of Oregon's rate.

[Proportional Comparison of Oregon Washington and the United States.](images/Proportional Comparison of Deaths.png)
Furthermore, when we compare these rates to the national levels (US full count / 50 states) we see that OR and WA are much lower than the national average.
___________________________________________________________
Question 3: Is the number of bicycle deaths really rising? If so, is the rise statistically significant?

![Bicycle Deaths in the United States](images/US_bicycle_deaths.png)

#3 Answer:
-The rate of deaths is clearly is rising (see above chart). 
-The rate of bicycle deaths has risen more than 150% between 2014-2022.

_____________________________________________________________________________

##Summary: Bicycle deaths are on the rise in the United States but Oregon and Washinton remain statistically safer places to ride, especially Washinton.

Actionable insights: As this data began to be published, more states have moved to increase bicycle infrastructure, mirroring states with low cyclist injury or death incidents. Hopefully, this rise in infrastructure will keep cyclists safer throughout the country.
