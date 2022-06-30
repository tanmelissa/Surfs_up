# Surfs_up
## Overview of Analysis
This analysis is to look at weather data for the island of Oahu to see if it is a good place to start a surf board and ice cream shop. This analysis will query a sqlite database to examine temperature and precipitationdata in June and December to determine year-round compatability for this venture.
## Results
### Comparing temperatures for June and December

- Differences in mean temperature:
  - June has a mean temperature of 74.9 
  - December has a mean temperature of 71.04
  
- Differences in standard deviation
  - June has a standard deviation of 3.25
  - December has a standard deviation of 3.74
  
- Differences in minimum temperature
  - June has a minimum temperature of 64
  - December has a minimum temperature of 56
  
- Differences in maximum temperature
  - June has a maximum temperature of 85
  - December has a maximum temperature of 83
  
## Summary
### Temperatures and precipitation in June and December, comparing statistics when filtering for elevation

#### Temperatures
- Although there are some differences between June and December in temperature, they are not large differences. For the sake of opening a surf and shake shop, the temperature based on the time of year should not affect the success of the shop.

- Some of the stations are located in high elevations. Since we don't want to open a surf and shake shop somewhere far from the ocean, we can remove the two stations that are not located near the ocean. This will make the data more relevant to where we would open our shop.
  - June temperature statistics:
    - The minimum temperature and maximum temperature remained unchanged
    - The mean temperature increased from 74.9 to 75.45
    - ![image](https://user-images.githubusercontent.com/102273449/176588300-1e1adf37-b353-470c-b6b8-8497dbff1736.png)
  - December temperature statistics:
    - The minimum temperature remained unchanged
    - The maximum temperature decreased from 83 to 82
    - The mean increased from 71.04 to 71.3 
    - ![image](https://user-images.githubusercontent.com/102273449/176588360-4617858f-d9aa-4d17-ba92-b1934d9fa4bc.png)
- Filtering out high elevations changed the temperature statistics a little. The most important difference being that the mean temperature increased slightly. This helps build that case that the weather is ideal for surfing and ice cream eating.

#### Precipitation
  - June precipitation statistics:
    - ![image](https://user-images.githubusercontent.com/102273449/176589736-867dda71-b21d-4445-8cca-e2563bb7db56.png)
 
  - December precipitation statistics:
    - ![image](https://user-images.githubusercontent.com/102273449/176589782-e5f1d70a-c74d-4797-b908-bd5107d3cdaa.png)
- You can see that compared to the data of the total precipitation in 2016-2017, the mean precipitation and the maximum precipitation both decreased in both months. 
  - Summary statistics for precipiation in 2016-2017 for comparison
  - ![image](https://user-images.githubusercontent.com/102273449/176590193-515e3140-1e3b-4706-b000-4c322f0d2d19.png)


### What to research next
- Analysing information about tourism, wave sizes, best surfing locations, and locations of competing surf or shake shops can help us get a better picture of where on Oahu to build our shop and when during the year would be the best time to open.

