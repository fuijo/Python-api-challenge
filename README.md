# python-api-challenge

**Weather and Vacation Analysis with APIs**
This project demonstrated the power of data analytics and APIs in answering a real-world scientific question: "What is the weather like as we approach the equator?" By utilizing Python's capabilities for handling APIs, data visualization, and statistical modeling, we systematically analyzed weather data across various cities. Additionally, the project expanded its scope to plan ideal vacation destinations based on specific weather preferences.

**Part 1: WeatherPy**
This section focused on retrieving weather data for over 500 cities worldwide using the OpenWeatherMap API and analyzing the relationship between weather variables and latitude.

Key Analyses and Findings:

Created scatter plots to visualize the relationships between latitude and various weather variables, including temperature, humidity, cloudiness, and wind speed.
Observed that:
Temperature: Generally increased as cities approached the equator, with a clear peak at lower latitudes.
Humidity, Cloudiness, and Wind Speed: Showed no strong patterns but displayed variability across regions.
Computed and visualized linear regressions for each weather variable separately for the Northern and Southern Hemispheres, identifying the direction and strength of correlations.
Tools and Techniques Used:

**APIs:** OpenWeatherMap for retrieving live weather data.
Python Libraries: Pandas, Matplotlib, SciPy for data manipulation, visualization, and regression analysis.
Statistical Insights: Calculated regression lines, 
𝑟
2
r 
2
  values, and visually interpreted trends.
Part 2: VacationPy
This section extended the analysis to vacation planning by identifying cities with ideal weather conditions and locating nearby hotels using the Geoapify API.

Key Achievements:

**Mapping Humidity:** Created a global map displaying humidity levels in cities, with point sizes proportional to humidity.
Filtering Ideal Locations: Narrowed down cities based on specific weather criteria (e.g., moderate temperature, low wind speed, and zero cloudiness).
Hotel Search: For each selected city, identified nearby hotels within 10,000 meters using the Geoapify API.
Interactive Maps: Generated maps with hover-over messages displaying city names, countries, and hotel names for an intuitive visualization of vacation hotspots.
Challenges Overcome:

Ensured balanced sampling of cities by generating random coordinates across a wide range of latitudes and longitudes.
Managed API request limits effectively to retrieve data for the required number of cities.
**Project Outcomes:**
Answering the Scientific Question: Confirmed that temperatures generally increase as cities approach the equator, providing evidence-based insights using weather data.
Practical Application: Created an interactive and data-driven solution for planning vacations based on personal weather preferences.
Skill Development: Strengthened proficiency in Python programming, data visualization, API integration, and statistical analysis.
This project not only highlighted the utility of Python for large-scale data handling and analysis but also showcased the potential of APIs and visualization tools to solve real-world problems in science and leisure planning.
