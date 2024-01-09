# Energy-Load-Forecasting
This notebook contains the following:

Project Description, Data Sources and other references:
1.Importing libraries
2.Interpreting Dataset
3.Exploratory Data Analysis
4.Feature Engineering
5.Model Creation and Evaluation (Multiple Linear Regression, Random Forest and XG Boost)

The EnergyDemand_dataset.xlsx contains hourly Real-Time (RT) energy demand and weather data for the ISO New England Control Area (ISO NE CA). ISO New England Control area consist of MA, VT, CT, NH , ME , RI states.
The dataset is sourced from https://www.iso-ne.com/isoexpress/web/reports/load-and-demand/-/tree/zone-info and spans a four-year period (2016-2019) containing 35064 records. The primary objective is to utilize this real dataset to forecast energy consumption and evaluating the machine model performance.


Key Columns:
1.Date: Represents the calendar date of the provided data.

2.Hr_End:Indicates the hour of the observation, following the hour-ending and 24-hour convention.

3.RT_Demand: Represents Real-Time Demand in megawatts (MW). It corresponds to Non-PTF Demand for wholesale market settlement and is derived from revenue quality metering. It is defined as the sum of non-dispatchable load assets, station service load assets, and unmetered load assets.

4.Dry_Bulb_Temp: Indicates the dry-bulb temperature in Fahrenheit (°F) for the weather station corresponding to the load zone or Trading Hub. The temperature is categorized into summer (June-September) and winter (October-May) periods.

5.Dew_Point_Temp:Represents the dewpoint temperature in Fahrenheit (°F) for the weather station corresponding to the load zone or Trading Hub. Similar to dry-bulb temperature, it is categorized into summer (June-September) and winter (October-May) periods.

The dataset is comprehensive, covering various aspects of Real-Time demand and weather conditions, and will be utilized for predicting energy forecasts based on the provided information.

Ref:This implementation is motivated from "Electric load forecasting with recency effect: A big data approach" Research Paper
