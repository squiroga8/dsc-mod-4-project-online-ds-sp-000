
# Module 4 Final Project - Forecasting Median House Prices

## Contents of this Repo:
Contained within these repo are:
- The **Module4Project_ExecutiveSummary_SerenaQuiroga_27Nov2019.pdf** - *Non-technical summary of findings and recommendations, based on completed analysis*
- The data used: **zillow_data.csv**
- The **Module_4_Final_Project jupyter notebook** - *with all code and mark-ups for executing the time-series analysis*


## Project Overview
The goal of this project is to pick the top 5 zip codes that are the "best" for real estate investments by using ARIMA (Autoregressive Integrated Moving Average) models based on the median house prices in the past.

Within this notebook, I forecasted real estate prices of various zip codes using data from Zillow to make final recommendations to a fictitious real-estate investment firm, called Redwood Real Estate.

For the purposes of this project, I defined the following information regarding this fictional firm and their interests:

- Redwood Real Estate (hereafter referred to as Redwood) invests in residential real estate markets across the Pacific Northwest,  with a previous focus on rural areas in northern California, Oregon, and Washington state.
- Redwood is now seeking to invest in intermediary cities in the Pacific Northwest.
- Redwood is weary of areas where housing prices are surging, including San Francisco and Seattle, as they are a family-owned business that identifies as more risk adverse with a focus on ethical and shared growth.
- Redwood's business values include sustainable investments, establishing ties with local community, and responsible real estate appraisal practices. Redwood seeks to set new precedents in terms of corporate social responsibility in the real estate industry.
- Redwood's slogan is: "Let's grow together."


## Project Parameters:
- **Data Used:** Zillow Research Data https://www.zillow.com/research/data/ (contained as a csv in this repo as well).
    - April 1996 - April 2018
    - 14723 unique zip codes in the USA
- **Models and Tests Used:**
    - ARIMA Models
    - XX
    - XX
- **Approach (Using the CRISP-DM framework):**
    - Establish initial Business Understanding
    - Conduct additional research related to Business Understanding
    - Obtain data
    - Select subset of data based off of business understanding
    - Update business understanding based off of data understanding and initial exploration
    - Clean round 1 of data
    - De-trend and control for stationarity assumption
    - Model
    - Forecast
    - Evaluate and make recommendations