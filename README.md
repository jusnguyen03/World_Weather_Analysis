# World_Weather_Analysis

## Project Overview
I will be retrieving and analyzing weather data for a hypothetical travel company, PlanMyTrip. During this project, I will be:
  - Performing tasks using new Python libraries and modules.
  - Retreiving and using data from an API "get" request to a server.
  - Use try and except blocks to resolve errors.
  - Write Python functions.
  - Create scatter plots using the Matplotlib library, and apply styles and features to a plot.
  - Perform linear regression, and add regression lines to scatter plots.
  - Create heatmaps, and add markers using the Google Maps API.

## Resources
- Data Source: avg_rain_state.csv, cereal.csv, donors2008.csv, youtube_response.json
- Software: Python 3.6.1, Jupyter Notebook, Matplotlib, OpenWeatherMap API

## Challenge Overview
Jack loves the app. Beta testers love the app. And, with any new product, there are some changes that could take it from a nice app to an awesome app. Your mission, should you choose to accept it, is to implement the feedback from the beta testers, which is listed below.
  1. A weather description to the pop-up markers for customers so that they know what the weather is as they are traveling
  2. A notation in the search criteria to indicate if it is raining or snowing for customers who are making travel decisions in real- time
  3. A map that shows the directions for customers’ travel itinerary

The goals for this challenge are:
  - Use nested try-except blocks.
  - Use Pandas methods and attributes on a DataFrame or Series.
  - Create a new DataFrame from a new API search with new weather parameters.
  - Filter DataFrames based on input and nested decision statements, and logical expressions.
  - Create pop-up markers on a Google map from a filtered Dataframe.
  - Add a directions layer on a Google map between cities in the filtered DataFrame.

## Challenge Summary
Included in the repository are all of the following that was submitted for this challenge
Codes for all 3 parts
  - Weather_Database.ipynb
  - Vacation_Search.ipynb
  - Vacation_Itinerary.ipynb
Located in the "weather_data" folder are the following CSV files and images
  - WeatherPy_challenge.csv
  - WeatherPy_vacation.csv
  - WeatherPy_vacation_map.png
  - WeatherPy_travel_map.png
  - WeatherPy_travel_map_markers.png

### Part 1
#### Get the Weather Description and Amount of Precipitation for Each City
The code for this can be found in the repository under the file "Weather_Database.ipynb".
![](https://github.com/jusnguyen03/World_Weather_Analysis/blob/master/weather_data/Weather_Database_df.png)

#### There are 47 cities that have recorded rain or snow.

### Part 2
#### Have Customers Narrow Their Travel Searches Based on Temperature and Precipitation
The code for this can be found in the repository under the file "Vacation_Search.ipynb".
![](https://github.com/jusnguyen03/World_Weather_Analysis/blob/master/weather_data/WeatherPy_vacation_map.png)

I had a customer want to go somewhere with the mininum temperature being 40 degrees and maximum tempature being 85 degrees. They said it would be ok if it rained, but definitely did not want any snow. Based off of this customer's criteria, we searched 357 possible locations. 


### Part 3
#### Create a Travel Itinerary with a Corresponding Map
The code for this can be found in the repository under the file "Vacation_Itinerary.ipynb".

I created a map (travel itinerary) that displays the route between four cities that my customer chose. The route that makes the most sense is shown below.
![](https://github.com/jusnguyen03/World_Weather_Analysis/blob/master/weather_data/WeatherPy_travel_map.png)

The trip starts in the city of Shuiji, and travels west to Dongsheng, then Enshi, and ending the trip in Huilong.

![](https://github.com/jusnguyen03/World_Weather_Analysis/blob/master/weather_data/WeatherPy_travel_map_markers.png)
