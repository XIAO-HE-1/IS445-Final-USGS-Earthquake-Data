# IS445 Data Visualization Final Project
## Team 4
| Name          | NetID |
|:-------------:| :-----:|
| Xiao HE | xiaohe4 |
| Alka Mishra |   alkaam2 |
| Tyler Hicks |   tylerch2 |
| Erick Li |  zhiyuan5 |
| Chien-Ju Chen |  chienju2 |  

The Link to our final project is [here](https://github.com/XIAO-HE-1/IS445-Final-USGS-Earthquake-Data/blob/main/Earthquake_Visualization_IS445_Group4.ipynb). 
Note: Our dashboard will show up correctly after running the code in your environment.

### USGS Earthquake Dataset
<img src="https://github.com/XIAO-HE-1/IS445-Final-USGS-Earthquake-Data/blob/main/usgs_picture.png" width="800">  

* Our data is retrieved from the [US Geological Survey](https://www.usgs.gov/natural-hazards/earthquake-hazards/earthquakes), And here is [download address](https://earthquake.usgs.gov/earthquakes/search/)
* In our visualization report, we used both [historical data](https://github.com/XIAO-HE-1/IS445-Final-USGS-Earthquake-Data/blob/main/EarthquakeData_12092020-12162020.csv) and [real-time data in the last hour](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_hour.geojson)
* The dataset includes time, location information(latitude,longitude, place), earthquake information(magnitude, earthquake type), measurement error(horizontal Error, depth Error) etc.  
  * Explanation of some variables
      * Depth Error: Uncertainty of reported depth of the event in kilometers.
      * Magnitude Error: Uncertainty of reported magnitude of the event. The estimated standard error of the magnitude. The uncertainty corresponds to the specific magnitude type being reported and does not take into account magnitude variations and biases between different magnitude scales. 
      * Horizontal Error: The horizontal location error, in km, defined as the length of the largest projection of the three principal errors on a horizontal plane. The principal errors are the major axes of the error ellipsoid, and are mutually perpendicular. The horizontal and vertical uncertainties in an event's location varies from about 100 m horizontally and 300 meters vertically for the best located events, those in the middle of densely spaced seismograph networks, to 10s of kilometers for global events in many parts of the world. 

### Goal of Project 
* Provide a dashboard that shows audience the earthquakes in the last hour and the last seven days
* Easy access to various earthquake information
* Know the location and the magnitude of the earthquakes

### Structure of our project
* Data Exploration
  * Descriptive statistics
    * Magnitude frequency
    * Earthquake count by date/region
    * Magtype, location source….
  * Geographical display
* Real-time Data Dashboard
* Summary of any stumbling blocks we might have had
