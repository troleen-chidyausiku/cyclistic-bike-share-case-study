# Cyclistic Bike-Share Case Study

An analysis of Cyclistic, a bike-share company in Chicago, exploring how annual members and casual riders use the service differently — with the goal of informing a marketing strategy to convert casual riders into members. The analysis covers 12 months (April 2022 to March 2023) of Cyclistic trip data and combines data cleaning, modeling, business analysis, and dashboard storytelling.

This project was done on Kaggle , kindly use the link to access it [Kaggle Notebook](https://www.kaggle.com/code/troleen/cyclistic-bike-share-analysis)

## Table of Contents
- Business Question
- Data Source
- Tools Used
- Process
- Key Findings
- Recommendations
- Dashboard

## Business Question

Key question: In what ways do members and casual riders use Divvy bikes differently?
Understanding these differences is intended to help shape a marketing strategy aimed at converting casual riders into annual members.

## Data Source

12 months of Cyclistic trip data (April 2022 – March 2023), made available via Kaggle: Cyclistic Bike Share Apr'22 - Mar'23 Dataset
Each monthly file contains ride-level records including ride ID, bike type, start/end times, station names, and rider type (member vs casual).


## Tools Used
- R (via Kaggle Notebooks)
- tidyverse (dplyr, ggplot2, lubridate, etc.) for data wrangling and visualization
- Power BI for additional/extended visuals
  
## Data Cleaning Process
The 12 monthly Cyclistic datasets were combined into a single dataset containing 5,803,720 records.
During data-quality checks:
- 99 rides with negative ride durations were removed.
- 440 rides with zero ride durations were removed.
- 502 rides with durations exceeding seven days were removed as extreme observations.
- Missing-value checks returned zero missing values across all 15 columns.
- Duplicate ride IDs were not identified.
- The final analytical dataset contains 5,802,679 rides.
Analyze — Compared ride length and ride frequency between member and casual riders, by day of week and by month.
Visualize — Built summary charts in R (ggplot2) and extended visuals in Power BI.

##Visuals from the analysis

## Key Findings
1. Casual riders take longer trips. Median ride length is ~12.7 minutes for casual riders vs. ~8.7 minutes for members; average duration is ~25.2 vs. ~12.5 minutes respectively (pulled up by longer outlier trips).
2. Usage patterns differ by day. Casual riders show stronger weekend usage — suggesting leisure-driven use — while members ride more consistently across weekdays, suggesting commuting behavior.
   
## Recommendations
1. Launch a members-only weekend promotion to encourage members to ride more on weekends.
2. Offer casual riders a weekend-only membership trial so they can experience membership benefits on the days they already ride most.
3. Offer casual riders weekday discounts to encourage trying the service outside of leisure hours.
4. Run a leisure-focused marketing campaign for members — since members currently ride at a consistent duration on weekdays (commuting), highlight how biking can also be an enjoyable weekend activity with friends/family.

This project was done on Kaggle , kindly use the link to access it [Kaggle Notebook](https://www.kaggle.com/code/troleen/cyclistic-bike-share-analysis)
