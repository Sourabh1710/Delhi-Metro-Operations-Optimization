# Metro Operations Optimization

## Introduction
I am working on optimizing Metro operations by analyzing and visualizing operational data from the Delhi Metro Rail Corporation. My objective is to identify key areas where adjustments in train frequencies could significantly improve service levels, reduce wait times, and alleviate overcrowding.

## Dataset Description
The [dataset](https://statso.io/delhi-metro-operations-case-study/) consists of several files, each containing crucial information about metro operations:
- **Agency**: Details about the Delhi Metro Rail Corporation, including name, URL, and contact details.
- **Calendar**: Service schedules defining operational days (weekdays, weekends) and valid service dates.
- **Routes**: Information about metro routes, including short and long names, route type, and descriptions.
- **Shapes**: Geographical coordinates defining the precise paths taken by metro lines.
- **Stop Times**: Timetables indicating arrival and departure times at specific stops.
- **Stops**: Locations of metro stops with latitude and longitude coordinates.
- **Trips**: Data linking trips to routes, including trip identifiers and associated route IDs.

## Objectives
1. **Visualizing the geographical metro routes**
2. **Examining frequency and scheduling trends**
3. **Analyzing stop distribution and connectivity**
4. **Understanding route complexity and major hubs**
5. **Analyzing service frequency across different time intervals**
6. **Optimizing train frequencies to reduce overcrowding**

## Visualizing Metro Routes
I begin by plotting the geographical paths of different routes on a map to visualize the Delhi Metro network.

![Metro Routes](https://github.com/Sourabh1710/Delhi-Metro-Operations-Optimization/blob/main/images/Geographical%20Paths%20of%20Delhi%20Metro%20Routes.png)

Each colored line represents a different metro route as defined in the shapes dataset. This visualization helps in understanding how well the metro covers the geographical area of Delhi.

## Trip Frequency Analysis
The number of trips scheduled for each day of the week provides insights into operational strategies.

![Trips per Day](https://github.com/Sourabh1710/Delhi-Metro-Operations-Optimization/blob/main/images/Number%20of%20Trips%20per%20Day%20of%20the%20Week.png)

Observations:
- Weekday schedules are consistent, accommodating regular commuter traffic.
- Trip counts decrease slightly on Saturdays and more significantly on Sundays due to lower demand.

## Stop Distribution and Connectivity
To analyze the coverage, I visualize the geographical distribution of metro stops.

![Stop Distribution](https://github.com/Sourabh1710/Delhi-Metro-Operations-Optimization/blob/main/images/Geographical%20Distribution%20of%20Delhi%20Metro%20Stops.png)

Observations:
- The metro provides broad spatial coverage across Delhi.
- Densely clustered stops indicate high transit demand and major hubs.

## Route Complexity Analysis
Analyzing how many routes pass through each stop helps in identifying transfer points and central hubs.

![Route Complexity](https://github.com/Sourabh1710/Delhi-Metro-Operations-Optimization/blob/main/images/Number%20of%20Routes%20per%20Metro%20Stop%20in%20Delhi.png)

Observations:
- Larger circles (warmer colors) indicate key transfer points.
- Stops with fewer routes are more peripheral, serving specific areas with lower connectivity needs.

## Service Frequency Analysis
I examine the timing intervals between trips during different parts of the day to understand peak and off-peak trends.

![Service Frequency](https://github.com/Sourabh1710/Delhi-Metro-Operations-Optimization/blob/main/images/Average%20Interval%20Between%20Trips%20by%20Part%20of%20Day.png)

Observations:
- Shorter intervals during morning and evening peaks reflect higher demand.
- Midday intervals slightly increase, indicating a reduction in demand.
- Evening intervals decrease again to accommodate rush-hour commuters.

## Time Interval Analysis
To understand service level variations, I classify time intervals as follows:
- **Early Morning**: Before 6 AM
- **Morning Peak**: 6 AM - 10 AM
- **Midday**: 10 AM - 4 PM
- **Evening Peak**: 4 PM - 8 PM
- **Late Evening**: After 8 PM

![Trips per Time Interval](https://github.com/Sourabh1710/Delhi-Metro-Operations-Optimization/blob/main/images/Number%20of%20Trips%20per%20Time%20Interval.png)

Observations:
- Significant increase in trips during morning and evening peak hours.
- A steady number of trips during midday.
- A decline in late evening operations due to reduced demand.

## Optimizing Operations to Reduce Overcrowding
Based on the above analysis, I refine train frequencies:

- **Morning and evening peaks**: Increase trips by **20%** to reduce overcrowding.
- **Midday and late evening**: Reduce trips by **10%** to optimize resource utilization.

![Original vs Adjusted Number of Trips per Time Interval](https://github.com/Sourabh1710/Delhi-Metro-Operations-Optimization/blob/main/images/Original%20vs%20Adjusted%20Number%20of%20Trips%20per%20Time%20Interval.png)

These adjustments aim to improve operational efficiency and passenger satisfaction.

## Conclusion
Metro Operations Optimization involves using data-driven insights to enhance service reliability and efficiency. Through visual analysis and frequency adjustments, I demonstrate how Metro services can be optimized even in the absence of explicit passenger count data.



## Author 
Sourabh Sonker <br>
Data Scientist

