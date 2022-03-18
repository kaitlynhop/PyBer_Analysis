# PyBer Analysis Overview
Ride sharing data from company, PyBer, was organized, sorted, and analyzed statistically according to type: "Urban", "Suburban", and "Rural". Initial analysis,performed in [PyBer.ipynb](/PyBer.ipynb) includes the following data: 
  1. [Bubble Chart](/analysis/Fig1.png) plotting the total number of rides per city against the average fare in dollars according to city type with bubble size corresponding to the number of drivers in the city 
  2. [Total Rides Box Plot](/analysis/Fig2.png) corresponding to statistical analysis of the number of rides for each city type 
  3. [Total Fares Box Plot](/analysis/Fig3.png) corresponding to statistical analysis of the fare amounts for each city type 
  4. [Total Drivers Box Plot](/analysis/Fig4.png) corresponding to statistical analysis of the number of drivers for each city type 
  5. [Total Fare Percentage Pie Chart](/analysis/Fig5.png) depicting the distribution of total fares according to city type 
  6. [Total Ride Percentage Pie Chart](/analysis/Fig6.png) depicting the distribution of total number of rides according to city type 
  7. [Total Drivers Percentage Pie Chart](/analysis/Fig7.png) depicting the distribution of total number of drivers according to city type 

Upon review of initial analysis, a second analysis was performed in [PyBer_Challenge.ipynb](/PyBer_Challenge.ipynb) that includes:
  1. [PyBer Summary Table](/analysis/PyBer_summary_DF.png) that organizes ride, driver, and fare data according to city type 
  2. [PyBer Weekly Fares](/analysis/PyBer_fare_summary.png), a multi-line chart analizing weekly fares from Jan. 2019 - Apr. 2019 according to city type 

### Purpose
The purpose of this project was to review data from PyBer ride sharing company to assess for patterns relating to revenue and ride availability according to city type.  

### Resources
Data source: [Resources/](/Resources/)
<br>Tools: Python, Jupyter Notebook, PANDAS, Matplotlib, Numpy, Statistics
<br>


## Results
### City Type Summary Analysis

**Table 1: PyBer Summary**
![Pyber_summary](/analysis/PyBer_summary_DF.png "Table 1")
**Table 1.** shows total number of rides, total number of drivers, total sum of fares, average fare per ride, and average fare per driver for each city type for all PyBer data currently available. 
<br>
Upon reviewal, there is clear correlation between values in the dataset among city types. Urban cities show the largest total rides, number of drivers, and fare revenue. Urban cities also have the lowest average ride cost per ride and ride cost per driver. This pattern continues with suburban cities with the second largest number of rides, drivers, and revenue and second smallest ride cost per ride and driver. Rural cities show the lowest number of rides, drivers, and total revenue with the highest ride cost per ride and per driver. 
<br>
From this table, it can be interpreted that the total number of rides, number of drivers available, and total revenue are positively correlated with each other. While the average fare per ride and per driver are negatively correlated, and show spike in values as total drivers, rides, and revenue decrease.

### Weekly Fare Totals Analysis

**Figure 1: PyBer Weekly Fare Totals**
<img src="/analysis/PyBer_fare_summary.png" width="600" height="300"/>
**Figure 1.** shows the total weekly fares from January 2019 to April 2019 for each city type. 
<br>
The figure shows similar results as the table, with urban cities consistently having the highest weekly revenue. This is followed by suburban cities then rural cities. Despite the higher fare averages for suburban and rural cities, the weekly revenue totals remain obeservable lower than urban cities' revenue by about $500 - $1500 weekly.


## Summary
In summary, there is a clear correlation between city types and total revenue. Urban cities maintain highest revenue totals and weekly totals despite having the lowest average cost per ride and per driver. From this it can be inferred that the number of rides taken and number of drivers have the biggest impact on total fares. The average cost per ride and average cost per driver have a negative impact on total fares, as seen in rural city types. To increase ride accessibility and increase total fares I recommend the following: 
  1. Increase the number of drivers available in suburban and rural areas. Understanding the lag from the increase in drivers to the increase in rides, this may involve match compensating new PyBer drivers that are unable to pickup riders due to lack of ride requests.
  2. Decreasing or capping the cost of a ride for underserved areas such as suburban and rural areas. The high price may be due to price gouging, becuase of lack of drivers, or becuase longer average distances traveled in these areas. This may involve compensating drivers for increased gas and mileage without being able to increase the cost per ride. 
  3. Marketing! Providing promotions and advertising are great tools to introduce future customers to PyBer. Generating hype around PyBer may lead to increase rides and ride requests in rural and suburban areas which will help promote the upscale of drivers in the area. This will create a positive feedback loop that will ultimately lead to increase in total fares. 