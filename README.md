# project-one-group-three
A shared repository for first group project

Team: Charles Lee, Kristen N. Broersma 
Cynthia Wonsch, Jimmy Fung 

# Title: Travelytics

# Does a travel advisory make travel destinations less attractive? 

# Null Hypothesis:
Travel advisories have no effect on Americans traveling abroad.

# Alternative Hypothesis:
If travel advisories are considered then the number of Americans traveling abroad should decline in the year going forward.

Procedure to Test Hypothesis:
We will take top 10 most popular travel destinations from the US to foreign countries.  We will rank on yearly data over 5 years (2013-2017).
Using the 10, we will search for travel advisory mentions of city.  If city is listed, we will run a T-test on the monthly travel one year before the travel advisory
and 1 year going forward.

# Outline: 

Our project is to find out what are the most popular travel destination for Americans and explore the reasons why people travel to that specific target destination. 
Is the decision based on attractions, events, weather, safety, accessibility, language, cost, etc. First, we plan on working on a dataset that contains information 
on outbound passengers from the US to the World. Once established the city with the highest amount of passengers, we will focus on getting the most popular 
attractions rated on Yelp Api to find out quantitative data from attractions (and then run a sentiment analyzer on the reviews?). We will also gather yearly 
information on the open weather Api  to see if it influences the number of US visitor per destination.  We will compare the top destinations visited to try 
to get an answer as to why that specific destination is ranked as the top.

# Data Sets to be used: 
• Bureau of Transportation Statistics (Air Carriers : T-100 International Market (US Carriers Only)) https://www.transtats.bts.gov/
• data.gov (Travel Warning) https://catalog.data.gov/dataset/travel-warning
• Wikipedia (Temperature Data for monthly average) https://www.wikipedia.org/

# Git procedures

## How to begin work on branch
git checkout <your_branch>
## On branch you can checking files and commit but never push to master
git add <file/directory to add>
git commit -m "<comment for commit>"
## This will push to git repository on your branch
git push origin <your_branch>
## To pull in changes from master for <your_branch> (executed from <your_branch> view)
git pull origin master

# Repository Structure:
# Root:
# Initial analysis of flight data and data organization
analysis.ipynb
# Hypothesis testing
csi_analysis.ipynb
# Plotting Data
plots_dest_vs_weather.ipynb
# Rain Plots
avg_rain_inches_plots.ipynb
# Linear Regression
weather_regression.ipynb

# ./Resources/:
## Data sets Downloaded
## All flights from or to US for 2013-2017
403043874_T_T100I_MARKET_US_CARRIER_ONLY_2013_All.csv
403043874_T_T100I_MARKET_US_CARRIER_ONLY_2014_All.csv
403043874_T_T100I_MARKET_US_CARRIER_ONLY_2015_All.csv
403043874_T_T100I_MARKET_US_CARRIER_ONLY_2016_All.csv
403043874_T_T100I_MARKET_US_CARRIER_ONLY_2017_All.csv
## Average Rain Data for Top 10 Cities from Wikipedia
avg_rain_inches.csv
## JSON formatted travel advisory
csi.json

## Dataframes output from manipulated data
analysis.csv
analysis_monthly.csv
analysis_monthly_avg.csv
averages_temp_passengers.csv

## Data plot outputs
cancun_avg_pass_temp.png
san_jose_cabo_temp_plot.png
cancun_rain.png
tokyo_avg_pass_temp.png
cancun_temp_plot.png
tokyo_temp_plot.png
top_cities_average_weather.csv
london_avg_pass_temp.png
london_temp_plot.png
all_cities_years.csv
mexico_city_avg_pass_temp.png
amsterdam_avg_pass_temp.png
mexico_city_temp_plot.png
amsterdam_temp_plot.png
paris_avg_pass_temp.png
paris_temp_plot.png
toronto_avg_pass_temp.png
punta_cana_avg_pass_temp.png
toronto_temp_plot.png
punta_cana_rain.png
punta_cana_temp_plot.png
vancouver_avg_pass_temp.png
san_jose_cabo_avg_pass_temp.png
vancouver_temp_plot.png
san_jose_cabo_rain.png

## Website Screen Caps for Data Sites
bts_website.png
travel_advisory_website.png

# ./Archive/:
Directory contains additional work which was not used for our project