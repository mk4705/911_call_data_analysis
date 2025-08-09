911 Calls Data Analysis

Overview
This project analyzes 911 emergency call data to uncover trends and patterns in call types, times, and locations. Using Python and  libraries like matplotlib , seaborn and pandas within a Jupyter Notebook, I visualized and interpreted public safety data to provide insights for emergency response.

Creating new features:
Created new column Reason from the title code using lambda expression
Extracted Hour, Month ,Date of week from the timestamp column which of datetime type

Exploratory Data Analysis:Geographic mapping of call locations

Visualizations:
Count plots for categories and times
Heatmaps showing call frequencies by hour and day
Trends over time

The dataset contains records of emergency 911 calls with features such as:
Latitude & Longitude
Description
Zip code
Call Title
Time of call
Township
Address

Results: 
Most emergency calls fall under EMS (Emergency Medical Services) categories, followed by Fire and Traffic incidents.
Peak call times tend to be during the evening hours, with noticeable daily and weekly patterns—such as higher call volumes on weekdays or certain hours of the day.
Geographic mapping reveals hotspots where emergency calls are concentrated, often corresponding to densely populated or high-activity areas.
Temporal analysis shows variations in call frequency by hour, day of the week, and month, which could inform better resource allocation for emergency services.
Visualizations such as heatmaps pinpoint the busiest hours combined with day of the week, indicating critical periods requiring heightened readiness.
Identification of specific townships or zip codes with the highest number of calls helps target community safety initiatives.
 
