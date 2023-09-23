# Weather API Analysis with Python

Part 1: WeatherPy
In this deliverable, a Python script was created to visualize the weather of over 500 cities of varying distances from the equator. 

Generated a cities list using citipy library:

![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/5a2807fb-3bc1-4d9c-8486-6da770ef81ff)

![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/d73c233b-030d-41dd-b4a6-3cbf20a59e47)

![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/6ce962ba-d13c-40c7-9c61-5039b30e9d5b)


1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

Latitude vs. Temperature
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/61186621-a3a8-4e1f-80d6-5337b9b35df2)

Latitude vs. Humidity
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/7bdb6261-1e94-4181-8fe7-323e8d10fcd6)

Latitude vs. Cloudiness
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/0d540070-4fe2-4b56-9a88-26ff79354a40)

Latitude vs. Wind Speed
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/78f7c082-39d0-41ba-863f-ec8bd39a1193)

2: Compute Linear Regression for Each Relationship
Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/7235085f-135d-4813-91eb-c9e4d04994d8)


Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/dad91a1f-a935-4326-9c78-02fdbe6aa2b3)

Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/1dac512a-37fc-4d40-8e5f-8c9584337146)

Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/3687160e-6fce-447f-9ed2-bc8068562cad)

Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/fd80eb0a-3a41-4c14-976c-b265c2624dd9)



Part 2: VacationPy

Main tasks were to use the Geoapify API and the geoViews Python library and employ Python to create map visualizations.

Humidity map
Narrowed down the city_data_df DataFrame to find ideal weather condition. 

![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/24745ab0-a368-45ce-b3d9-91e45cf824b1)

Created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/dc7553de-868c-43df-9b4b-37cb34dcbbf7)

For each city, Geoapify API was used to find the first hotel located within 10,000 meters of the coordinates.
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/dd9b36aa-5071-4f50-b7a8-1ac7ea0cd6fa)

Added the hotel name and the country as additional information in the hover message for each city on the map.
![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/518370e5-b108-4157-a027-07709d19014c)

Hotel map

![image](https://github.com/albertdudek7/Weather_API_Analysis_with_Python/assets/127783844/c64d17af-d5bc-4dc9-8584-4920a59788d3)


