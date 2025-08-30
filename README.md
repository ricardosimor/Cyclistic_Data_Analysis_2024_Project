# Google Capstone Track 1 Case Study 1: Cyclistic 2024

## Import Library Used
```shell
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.preprocessing import StandardScaler
from sklearn.cluster import KMeans
import seaborn as sns
import folium
```

## Business Understanding
### Business Background
**Increase profitability by converting casual customers into annual members.**
<p>Financial analysts have found that annual memberships are significantly more profitable, and rather than seeking new customers, Cyclistic believes there's a significant opportunity to convert casual riders already familiar with its services. To achieve this, the marketing team needs to analyze bike travel data to understand the behavioral differences between casual riders and annual members, which will form the basis for designing an effective digital marketing strategy.

### Objectives
1. Which bicycle type will be in high demand in 2024?
2. Which bicycle type has the longest average usage time?
3. What is the trend in bicycle usage over the year (months & days)?
4. Where are the most popular locations (member vs. casual)?

### Data Description
- **ride_id**: Unique ID for each bike trip.
- **rideable_type**: Type of bike used (electric bike, classic bike, electric scooter)
- **started_at**: Time/date when the trip started
- **ended_at**: Time/date when the trip ended
- **start_station_name**: Name of the starting station (departure location)
- **start_station_id**: Unique ID for each starting station
- **ended_station_name**: Name of the destination station (end location)
- **ended_station_id**: Unique ID for each ending station
- **start_lat**: Starting latitude coordinate
- **start_lng**: Starting longitude coordinate
- **end_lat**: Ending latitude coordinate
- **end_lng**: Ending longitude coordinate
- **member_casual**: Name of user type (member and casual)
- **ride_length**: Trip duration (minutes)

## NOTE - RUN MAP VISUALIZATION
If you want to see the data visualization results regarding the map visualization of Most used locations (Casual & Member). <br>
Run the `top_locations_map.html` in a browser Or run it on a notebook by doing Trusted Notebook.
> File -> Trusted Notebook



