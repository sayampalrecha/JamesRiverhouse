# JamesRiverhouse
Course - Data_Science_DATS_6101_Intro_to_Data_Science 

## Predicting and Analyzing U.S. Flight Delays: Identifying Key Factors and Improving Forecast Accuracy

## Proposal -

- Flight delays are one of the most serious challenges in the US aviation industry, causing huge inconvenience and coupled with losses to airline companies.<br>
- This work examines the key patterns, causes, and trends in US flights taken from January 2017 to July 2022 that have an impact on flight punctuality.<br>
- This will help airlines understand the root cause of the delay problem and thus enable them to optimize their flight schedule further for better passenger satisfaction.

- The dataset from Kaggle contains flight details, including the departure and arrival time, airline operating, airport from which and where it landed, duration of delay, and finally consolidated weather data. This dataset has over millions of values, thereby providing an adequate overview of flight operations and further delays in the US over a considerable period.

```bash
# Install tidyverse (includes ggplot2, dplyr and other essential packages)
install.packages("tidyverse")

# Load the packages after installation
library(tidyverse)  # Loads all tidyverse packages
# Or load individually
library(ggplot2)
library(dplyr)

# First install pak if you haven't already
install.packages("pak")
pak::pak("tidyverse/tidyverse")
```



## Objectives:
1. Causes of Delays: Analyze different causes of flight delays, including but not limited to weather conditions, airline performance, and airport performance, seasonal causes, among others, for actionable insights helpful in mitigating delays.
2. Trend Analysis: Analyze the trends of flight delays with respect to time. This will include high-traffic time, holidays, and seasonal impacts.
3. Airline & Airport Performance: Ascertain how different airlines and different airports perform in causing or being caused by delays and, later, assess their performances against these measures.
4. Predictive Modeling: Utilize the insights to construct machine learning models that can predict, using airline data, flight delays resulting from weather, time of day, and other factors.

This analysis will offer valuable insights to airlines, passengers, and policymakers, leading to improved operational efficiency, better planning, and enhanced customer satisfaction in the aviation sector.

## SMART questions – 

1. What are the top 3 carriers with the highest average delay times during peak summer months (June-August), and how do their delay patterns correlate with specific routes and time of day

2. For top 5 most delayed airlines, can we identify major reasons and its trend over 6 months, so that it can help airlines to relocate proper resources and improve its operational efficiencies

3. Which U.S. airports consistently experience the highest cumulative delays across different delay causes (Carrier, Weather, NAS, Security, Late Aircraft) for both origin and destination flights, and how does this ranking vary on a monthly or seasonal basis over the observed period?

Kaggle Dataset: https://www.kaggle.com/datasets/undersc0re/flight-delay-and-causes/data
