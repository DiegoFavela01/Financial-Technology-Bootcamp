# Data-Visualization-with-PyViz
## Challenge 6 - University of Berkeley Financial Technology Boot Camp
With this code we analyze the real-estate data for San Francisco to identify viable investment opportunities. The project involves visualization, aggregation, interactive visualizations, and geospatial analysis.

### Part 1: Load and Preprocess Data
- Load the sfo_neighborhoods_census_data.csv file into a DataFrame.
- Remove the null values and any duplicates.
- Group the data by year and neighborhood.
- Calculate the mean of the groups for housing units, sale price per square foot, and gross rent.
- Create a new DataFrame that includes only sale price per square foot and gross rent averages.

### Part 2: Calculate and Plot Housing Units per Year
- Group the data by year.
- Calculate the mean of the groups for housing units.
- Visualize the results as a bar chart using hvPlot.
- Format and style the chart.

### Part 3: Calculate and Plot Average Sale Prices per Square Foot
- Group the data by year.
- Calculate the mean of the groups for sale price per square foot and gross rent.
- Create a new DataFrame that includes only sale price per square foot and gross rent averages.
- Visualize the results as a line plot using hvPlot.
- Format and style the chart.

### Part 4: Compare the Average Sale Prices by Neighborhood
- Group the data by year and neighborhood.
- Calculate the mean of the groups for sale price per square foot and gross rent.
- Create an interactive line plot using hvPlot that visualizes both sale price per square foot and gross rent.
- Set the x-axis parameter to the year and the groupby parameter to create an interactive widget for neighborhood.
- Format and style the chart.

### Part 5: Build an Interactive Neighborhood Map
- Load the neighborhood_coordinates.csv file into a DataFrame.
- Set the index_col of the DataFrame as “Neighborhood”.
- Group the original DataFrame by neighborhood and calculate the mean of the groups for sale price per square foot and gross rent.
- Concatenate the two DataFrames to create a new DataFrame that includes both the location data and the average prices.
- Create an interactive scatter plot using hvPlot with GeoViews enabled that shows the neighborhoods in San Francisco and - their average sale price per square foot and gross rent.
- Format and style the chart.

### Part 6: Compose Your Data Story
- Based on the visualizations created, compare the trend in rental income growth with the trend in sales prices.
- Analyze if this trend holds true for all the neighborhoods across San Francisco.
- Draw conclusions and provide insights to your

## Libraries and Dependencies
This code uses the following libraries:

- Pandas
- Hvplot
- Pathlib
- Warnings
####  To install these libraries
```bash
!pip install pandas 
!pip install hvplot
!pip install warnings
```
pip install pandas hvplot warnings

## Files
The necessary files for this code are found in /Resources
- housing_per_year.csv 
- neighborhoods_coordinates.csv
- sfo_neighborhoods_census_data.csv 
