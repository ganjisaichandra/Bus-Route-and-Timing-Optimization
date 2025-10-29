# Bus-Route-and-Timing-Optimization

1. Problem Statement:  
Students and commuters frequently face delays and overcrowding due to inconsistent bus 
timings and poorly optimized routes. 
Despite having scheduled timetables, actual arrival and departure times often deviate, leading to: 
● Increased waiting times for passengers 
● Uneven distribution of passengers across buses 
● Inefficient resource utilization (some buses overcrowded, others underused) 
● Reduced punctuality and satisfaction among students 
This issue affects transport reliability, causes unnecessary stress, and wastes time for both 
students and drivers. 
2. Proposed Solution: 
To address these inefficiencies, this project introduces a data-driven bus route and timing 
optimization system using Excel analytics and AI-assisted recommendations. The solution is 
simple yet practical, leveraging real-world data to enhance punctuality and passenger comfort. 
The approach involves: 
1. Data Collection – Recording 100 entries of bus operations, including route, timing, and 
passenger data. 
2. Data Cleaning and Analysis – Using Excel to calculate key metrics such as delay, crowding 
percentage, and punctuality rate. 
3. Visualization Dashboard – Developing charts and pivot tables to show average delays, 
crowding categories, and trends. 
4. AI/Logic Recommendations – Suggesting 
optimized schedules, additional buses for high-demand routes, and merging of low-demand 
routes. 
Outcomes: 
 • Reduced average delays by 20–30% 
 • Balanced passenger load across routes 
 • Improved student satisfaction and punctuality 
 • Foundation for predictive scheduling in the future 
3. Introduction:  
                                 Efficient and reliable transportation is essential for ensuring that students 
reach their educational institutions on time. However, many institutions face persistent issues, 
such as bus delays, inconsistent routes, and overcrowding, which lead to frustration, time loss, 
and inefficient use of resources. 
These challenges often stem from poor route planning, unoptimized schedules, and the lack of 
data-driven monitoring. Traditional systems depend on fixed timetables that fail to adapt to 
real-world conditions, such as variable traffic patterns or fluctuating passenger demand. 
This project aims to address these challenges through the use of data analytics. By analyzing 
real-time and historical bus data, we can extract patterns related to delays, crowding, and route 
performance, and use these insights to propose data-backed scheduling improvements. 
4. Objective: 
                       The primary objective of this project is to analyze and optimize bus routes and 
schedules to enhance punctuality and passenger distribution efficiency. 
 The objectives include: 
1. Analyzing bus delay patterns across different routes. 
2. Identifying the least and most crowded routes using occupancy rates. 
3. Determining peak hours for passenger demand. 
4. Providing AI-based or rule-based recommendations for improving timing and route 
allocation. 
Creating an interactive Excel dashboard to visualize results and insights effectively. 
                      
5. Data Description: 
                                         The dataset contains 100 records representing bus operations collected 
over a specific period. Each record provides details about timing, crowding levels, and 
punctuality. The attributes used in this project are described below: 
Field Name Description 
Date The date on which the bus trip was recorded. 
Route The route identifier (e.g., Route A, Route B, etc.) represents a specific 
travel path. 
Bus No The unique number or ID assigned to each bus. 
Departure 
Time 
The actual departure time of the bus from its starting point. 
Arrival Time The actual arrival time of the bus at the destination. 
Scheduled 
Arrival 
The planned or scheduled arrival time is used as a reference to calculate 
delays. 
Capacity The total seating capacity of the bus. 
Passengers The actual number of passengers who traveled on that trip. 
Delay (min) The time difference in minutes between the actual and scheduled arrival. 
A positive value indicates lateness. 
Crowding % The percentage of bus occupancy, calculated as (Passengers ÷ 
Capacity) × 100. 
Crowding 
Category 
Categorization of crowding as Low, Moderate, or High based on 
occupancy percentage thresholds. 
On Time Status indicating whether the bus arrived On Time, Slightly Delayed, or 
Highly Delayed based on defined delay criteria. 
6. Methodology: 
 The project was executed in several key stages to ensure accuracy and actionable results: 
1. Data Collection: Gathered 100 records from sample bus route and timing data. 
2. Data Cleaning: Removed duplicates, formatted time data, and handled missing values in 
Excel. 
3. Key Metrics Calculation: Calculated average delays, crowding percentage, and 
punctuality rates. 
4. Categorization: Classified buses based on crowding levels (Low, Medium, High). 
5. Visualization: Created charts and pivot tables to visualize trends and route performance. 
6. AI Recommendation Logic: Suggested optimal timings and route adjustments based on 
the data insights. 
7. Analysis: 
● Average delay across all routes: 6.8 minutes 
● Most delayed route: Route C 
● Least crowded route: Route A 
● Peak crowding time: Between 07:30 – 08:00 AM 
● Highest passenger load observed on Route D with an average of 90% occupancy. 
8. Dashboard Insights: 
● Bar charts for average delay comparison across routes. 
● Pie charts for crowding distribution (Low, Medium, High). 
● Line chart for daily performance trends. 
● Pivot tables for on-time performance by route and time window 
