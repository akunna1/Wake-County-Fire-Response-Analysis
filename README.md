# 🚒 Wake County Fire Response Analysis

## Overview

Analyze Wake County Fire Department data to understand **response times**, **station performance**, and **peak hours** for fire calls, focusing on actual fire incidents.

## Data

* **File:** `Fire_Incidents.csv`
* **Columns include:**
  `X`, `Y`, `OBJECTID`, `incident_number`, `incident_type`, `incident_type_description`, `arrive_date_time`, `cleared_date_time`, `dispatch_date_time`, `exposure`, `platoon`, `station`, `address`, `address2`, `apt_room`, `GlobalID`, `CreationDate`, `Creator`, `EditDate`, `Editor`

### Sample rows:

```
X          Y          OBJECTID incident_number incident_type incident_type_description arrive_date_time          cleared_date_time         dispatch_date_time      exposure platoon station address
-78.62660452 35.87021286 474765 07-0031665 NULL 2007/11/15 11:17:00+00 2007/11/15 11:25:00+00 2007/11/15 11:10:00+00 0       6647 LAKE HILL DR RALEIGH, NC 27601
-78.69364226 35.79289581 474766 08-0017918 NULL 2008/06/29 06:20:00+00 2008/06/29 06:42:00+00 2008/06/29 06:17:00+00 0       539 METHOD RD RALEIGH, NC 27606
-78.6277871  35.81217058 474767 08-0032426 NULL 2008/11/18 04:19:00+00 2008/11/18 04:24:00+00 2008/11/18 04:12:00+00 0       2100 RUARK CT RALEIGH, NC 27601
-78.59542157 35.76121328 474768 07-0023051 444 Power line down 2007/08/21 22:52:00+00 2007/08/21 22:58:00+00 2007/08/21 22:47:00+00 0 A 12 1216 BEVERLY DR RALEIGH, NC 27601
```

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

