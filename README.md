# Quantitative Data Analyst 2021

## Approved Energy | Quantitative Data Analyst | Stamford, CT 

Thank you for applying for the position of Quantitative Data Analyst at Approved Energy. For the next steps, please upload your solution to GitHub and share the repository link as a reply to this email. This task is designed to evaluate your analytical, algorithmic, problem solving and presentation skills. You are welcome to choose any technology stack of your choice. 

The electric grid is critical to fundamentally sustaining the daily needs of the population. Electric Independent System Operators (ISOs) such as NYISO and public utilities such as Con Ed are responsible to ensure the system integrity and financial stability of the grid. One of the key drivers in maintaining system integrity is through accurate load forecast. A major factor affecting load forecast is weather. ISOs typically generate medium to longer term load forecast based on 5-to-30-year average historical weather data also known as normal weather. This process of determining long term load forecast based on normal weather is called weather normalization. 

At a high level, generally, to weather normalize load 

* You will need to develop a model based on actual observations of historical load, weather, and/or other available data such as power settlement prices, inflation, etc.  

* Apply the model to normal weather to produce weather normalized load forecast.  

## Problem Statement 

Please build a model to weather normalize load data for New York City (NYISO – Zone J/N.Y.C.) and present weather normalized annual hourly load data for N.Y.C. 

Data Source	 

* Historical load data. [NYISO reports 5-min interval electric demand data for NYC.](https://www.nyiso.com/custom-reports?report=rt_actual_load) The data set reports information about how much electric demand is being used real-time in 5-min internal. This demand data can be converted to hourly usage data by averaging the demand recordings within the hour. 
* Historical weather data. Please source weather data from NOAA. You can find weather datasets at NOAA’s API [here](https://www.ncdc.noaa.gov/data-access)
* Other Data. Other than historical load and weather, you are encouraged to use other factors in your algorithm such as hourly settlement power prices, population, economic indicators etc. You can source New York settlement market prices [here](https://www.nyiso.com/energy-market-operational-data)

## Output
* The datasets provided to you will also have to be explained in a visualized format, for example graph of historical load, weather normalized load, etc. With all the datasets provided, at your discretion, create plots or graphs for the same. 
* Submission will include the following: code file(s) for the same, extra datasets (in Excel/CSV format) (if any), well summarized explanation for the weather normalization algorithm including input sources, output dataset for annual hourly weather normalized load for N.Y.C. and screenshots of plots or graphs with proper labelling. 

Guidelines
* Please only use N.Y.C. as the geographic location for your analysis.  
* Datasets sourced may be available in different time intervals I.e., monthly, daily, hourly. Please standardize datasets to the resolution at your discretion. 
* The program should be able to fetch any dependency on the go, if not already present on the system. Static data can be saved in program folder (deciding which data sets are to be considered static is at your discretion)
* The test is not about just getting the right answer, but also about creating a scalable and reusable solution that applies to any and every case possible. 
* This test aims to gauge your ability to present the data to others without having to go into explicit detail. Apart from the final forecast curve, it is important to be able to explain how you got to the forecast and explain the entire procedure in simple methods. 
* If you feel other data is required to solve the problem, at your discretion you can choose to add more facilitating data, but those datasets will have to be provided in the solution set. 
* As mentioned above, you’re welcome to choose any technology you think would suit the application best, however, optimization will be a key factor in reviewing your solution. 

Some important definitions: 
* Load – Energy (electricity, in this case) consumption data 
* NOAA – National Oceanic and Atmospheric Administration 
* Con Ed – Consolidated Edison of New York, Inc. 
* NYISO – New York Independent System Operator 
