# 🚒 Wake County Fire Response Analysis

## Overview

Analyze Wake County Fire Department data to understand **response times**, **station performance**, and **peak hours** for fire calls, focusing on actual fire incidents.

## Data

* **File:** `Fire_Incidents.csv`
* Includes incident location, type, dispatch/arrival/cleared times, and responding station.

## Tools & Libraries

* **R Libraries:** `tidyverse`, `lubridate`, `dplyr`, `tidyr`, `data.table`, `ggplot2`

## Key Features

* Clean and preprocess data
* Calculate response times
* Summarize average, median, min, and max response times by station
* Analyze trends over time
* Identify peak hours for fire calls
* Separate analysis for actual fires

## Outputs

* Cleaned dataset (`clean_fire_incidents_data`)
* Station summary tables (`station_summary`, `actual_fire_station_summary`)
* Hourly call counts (`dispatch_hour_count`, `actual_fire_dispatch_hour_count`)
* Visualizations: response times over time by station

## Usage

1. Place `Fire_Incidents.csv` in your working directory.
2. Run the R script.
3. Explore tables and visualizations to uncover fire response patterns.

## 💡 Insights

* Some stations respond faster on average than others.
* Response times fluctuate over time, possibly due to varying call volume or staffing.
* Peak call times help identify when the department is busiest, aiding resource planning.

