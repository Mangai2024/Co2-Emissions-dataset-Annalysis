
**CO2 Emissions Dataset Analysis**
**Overview**
This project involves analyzing the co2.csv dataset, which contains information about vehicle emissions and related attributes. The analysis includes inspecting the data, applying filtering criteria, and deriving meaningful insights using Python and Pandas.

**Dataset Details**
The dataset includes the following key columns:

**CO2 Emissions(g/km):** The amount of CO2 emitted by the vehicle, measured in grams per kilometer.
**Cylinders:** The number of cylinders in the vehicle's engine.
**Fuel Consumption Comb (L/100 km):** The combined fuel consumption of the vehicle, measured in liters per 100 kilometers.
**Vehicle Class:** The classification of the vehicle (e.g., SUV, Sedan).
**Key Operations**
1. Data Inspection
Display column names, data types, and a preview of the dataset.
Check for null values and clean the data if necessary.
2. Conditional Filtering
Filter rows where CO2 Emissions(g/km) is greater than 200 and Cylinders are greater than 4.
Identify the number of rows and columns affected by the condition.
3. Data Aggregation
Group data by Vehicle Class and calculate average CO2 Emissions(g/km) for each class.
Sort the results to identify the highest-emission vehicle classes.
4. Creating New Columns
Add a column named Emission Category to classify vehicles into 'High' and 'Low' emitters based on their CO2 emissions.
**5. Visualization**
Create a bar plot to visualize the top 5 vehicle models with the highest combined fuel consumption.
