# PyBer_Analysis
# Overview of the Analysis
> Explain the purpose of the new analysis.

The CEO has given you and another colleague a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type.
> A written report will be submitted to summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer. 
Below are the deliverables of the project
* Deliverable 1: A ride-sharing summary DataFrame by city type
* Deliverable 2: A multiple-line chart of total fares for each city type
* Deliverable 3: A written report for the PyBer analysis (which is this `README.md` file)

# Resources
* Data Source: `city_data.csv` and `ride_data.csv`
* Provided resource: `PyBer_Challenge_starter_code.ipynb` renames as `PyBer_Challenge.ipynb`
* Software: Python 3.7.6, Jupyter Notebook 6.1.4, Pandas, Matplotlib 3.3.2

## Deliverable 1
> A ride-sharing summary DataFrame by city type

The requirements for this deliverable as well as screenshots of `codes`are listed below;
1. The total rides for each city type
![1](https://user-images.githubusercontent.com/76136277/106187444-a7d7c080-6173-11eb-90d2-15b17959f96e.PNG)
2. The total drivers for each city type
![2](https://user-images.githubusercontent.com/76136277/106187493-b625dc80-6173-11eb-8ae2-35ec35417a67.PNG)
3. The total amount of fares for each city type
![3](https://user-images.githubusercontent.com/76136277/106187528-c0e07180-6173-11eb-92b5-7a6b01b6049a.PNG)
4. The average fare per ride for each city type
![4](https://user-images.githubusercontent.com/76136277/106187551-c8077f80-6173-11eb-804b-07cf86bc2a64.PNG)
5. The average fare per driver for each city type
![5](https://user-images.githubusercontent.com/76136277/106187617-db1a4f80-6173-11eb-9ac4-04cfa2837b03.PNG)
6. PyBer Summary DataFrame
![6](https://user-images.githubusercontent.com/76136277/106187647-e53c4e00-6173-11eb-92a8-a78f5c2d4ef5.PNG)
7. Cleaned up DataFrame by deleting the `index` name
![7](https://user-images.githubusercontent.com/76136277/106187671-ea010200-6173-11eb-94a5-9c41dc29eb62.PNG)
8. Formatting the Columns 
![8](https://user-images.githubusercontent.com/76136277/106187687-f08f7980-6173-11eb-9fb5-9e56e5e10a5f.PNG)

## Deliverable 2
> A multiple-line chart of total fares for each city type
![PyBer_fare_summary](https://user-images.githubusercontent.com/76136277/106188077-7e6b6480-6174-11eb-827e-2e27bc3ff02f.png)

## Deliverable 3
The requirements for this deliverable includes;
 1. An overview of the analysis
 2. Results
 3. Summary

### 1) Overview of the analysis
> Explain the purpose of the new analysis. A detailed overview of the analysis is explained above.

### 2) Results
> Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

City Type | Total Ride | Total Driver| Total Fare | Differences in ride-sharing |
--- | --- | --- | --- | --- |
Urban | 1625 | 2405 | $39,854.88 | 1. Fare started around $1,800 in January, rose to about $2,450 in late Feb and early March, dropped in late-march to about $1,950, and by the end of April, it increased to $2,300. The fare is pretty consistent here. Also, it has the cheapest average fare per ride and driver ($24.53 & $16.57 respectively), but most profitable |
Suburban | 625 | 490 | $19,356.33 | Fare started around $700 in January.The analysis was not profitable because fare wasn't consistent. It dropped in March and in mid-April  but went up to $1,400 by the end of April. Average fare per ride and drive is $30.97 and $39.50 respectively, but there wasn't much profit either.  |
Rural | 125 | 78 | $4,327.93 | Fare started around $200 in January. The analysis shows fare increase and dropped by the end of April. Also, the most expensive in average fare per ride and driver($34.62 & $55.49 respectively), and still made lesser profit.|
> PyBer DataFrame image
![6](https://user-images.githubusercontent.com/76136277/106187647-e53c4e00-6173-11eb-92a8-a78f5c2d4ef5.PNG)
> Multiple-line chart of total fares for each city type
![PyBer_fare_summary](https://user-images.githubusercontent.com/76136277/106188077-7e6b6480-6174-11eb-827e-2e27bc3ff02f.png)
> PyBer Ride-Sharing Data (2019)
![Fig1](https://user-images.githubusercontent.com/76136277/106195504-3a7d5d00-617e-11eb-9298-2326410ed9f4.png)

### 3) Summary
> Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

1.  In the rural and suburban cities, there is room for growth and expansion. The CEO should consider hiring more drivers. For example, Newtonview, Taylorhaven in the rural city has 
just one driver. Increasing the number of driver will lead to increase in the number of rides and more income.
![Fig7](https://user-images.githubusercontent.com/76136277/106202789-67cf0880-6188-11eb-853d-b52f50319916.png)

2. The rural city has the lowest fare and financial gain. By hiring more drivers as mentioned above, the CEO should also consider reducing the average fare per driver and increase ride fares. This is because the workload on each driver is reduced (when we hire more), and more financial income for the company (from the reduced fare for drivers and increased ride fare).
![PyBer_fare_summary](https://user-images.githubusercontent.com/76136277/106188077-7e6b6480-6174-11eb-827e-2e27bc3ff02f.png)

3.  Rides in urban cities can be expanded since there is consistency and more profits are being made here.
![Fig5](https://user-images.githubusercontent.com/76136277/106196670-b88e3380-617f-11eb-95ff-f78c703e5eb2.png)
