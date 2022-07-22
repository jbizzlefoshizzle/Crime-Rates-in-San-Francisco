# Crime Rates in San Francisco

### Tasked with visualizing crime rates in San Francisco, I created a choropleth map.
Given a csv file of police department incidents, I had to transform and restructure the data to better format it for a choropleth map.

After performing some data conversion, grouping, and aggregation, I was able to come up with a dataframe that represented the total number of crimes in each of San Fransisco's ten neighborhoods
![dataframe](https://github.com/jbizzlefoshizzle/Crime-Rates-in-San-Francisco/blob/master/Images/df-image.PNG)

### After reading in geojson data and centering around San Francisco's latitude and longitude, I used folium to create a choropleth
![code](https://github.com/jbizzlefoshizzle/Crime-Rates-in-San-Francisco/blob/master/Images/map-code.PNG)

In order to zoom in and out of the choropleth, you have to run the notebook locally.
![map](https://github.com/jbizzlefoshizzle/Crime-Rates-in-San-Francisco/blob/master/Images/map-image.PNG)
