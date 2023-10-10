# Exploratory Data Analysis (EDA) of UFO Sightings around the World.

## Introduction
In our EDA we are reviewing the data of UFO sightings. We will decipher the distribution of Unidentified Flying Objects(UFOs) around the world and look for patterns. 

We want to know if the truth is really out there! And what is that truth? 

Are UFOs consistent throughout the world? Is there a time or area where they appear more often?  What are UFOs interested in? 

Reviewing this data will helps us figure out if we should be afraid. VERY AFRAID!!!

![UFOs](https://media.npr.org/assets/img/2023/01/13/pentagon-uap-ufo-photo-aliens-26a98619ba43fb08d5fc0a36dfb12283b4b9b8ec-s1600-c85.webp)

## Dataset

NUFORC geolocated and time standardized ufo reports for close to a century of data. 80,000 plus reports. 

We appreciate NUFORC for consolidating and setting up this data set. 

We gathered our dataset from kaggle.com at https://www.kaggle.com/datasets/NUFORC/ufo-sightings.

The dataset has 12 columns with 80332 entries.

The data is a mixture of numerical values (representing location and time) and categorical values( UFO shape, name of country/city).


## Tools and Technologies

- **Programming Languages:** Python
- **Data Manipulation Libraries:** Pandas, NumPy
- **Data Visualization Libraries:** Matplotlib, Seaborn, Plotly Express, Plotly Graph Objects
- **Interactive Widgets:** ipywidgets
- **Mapping and Geospatial Libraries:** Folium
- **Additional Libraries:** Folium MarkerCluster 


## EDA Process
We start with Data Cleansing where we complete any gaps in the data left by NUFORC. 

We performed basic visualizations to determine what and where the UFOs are located. We attempt to decipher if certain timezones, areas, 
weather patterns or shapes are more prevalent.  

## Conclusion

Our exploratory data analysis of UFO sightings around the world revealed some interesting insights:

- UFO sightings do not exhibit any significant patterns based on shape, time, location, or season.
- The peak observations are occurring at 8-10 PM(2-3 hours after sunset during the seasons), can be attributed to human fatigue and may not necessarily indicate real UFO observations.
- There are more sighting where population density is higher. 

While our analysis did not uncover conclusive evidence of extraterrestrial activity, it provides valuable insights into the distribution and patterns of UFO sightings.


**Acknowledgment**

This dataset was scraped, geolocated, and time standardized from NUFORC data by [Sigmond Axel](https://github.com/planetsig/ufo-reports/blob/master/README.md). (Replace "URL" with the actual URL where readers can find more information about Sigmond Axel's work.)




