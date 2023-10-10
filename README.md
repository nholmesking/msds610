# Exploratory Data Analysis (EDA) of UFO Sightings around the World.

## Introduction
In our EDA we review data of UFO sightings and  decipher how the views, the distribution of Unidentified Flying Objects around the world.

We want to know if the truth is really out there! And what is the truth? 

Are UFOs consistent throughout the world? Is there a time or ara where they are clearly interested in? 

Reviewing this data helps us figure out we should be afraid. VERY AFRAID!!!


## Dataset

NUFORC geolocated and time standardized ufo reports for close to a century of data. 80,000 plus reports. 
We appreciate NUFORC for consolidating and setting up this data set. 
We gathered our dataset from kaggle.com at https://www.kaggle.com/datasets/NUFORC/ufo-sightings.


The dataset has 12 columns with 80332 entries.
Data Set breakdown: 
 0   0                     80332 non-null  int64  
 1   datetime              80332 non-null  object 
 2   city                  80332 non-null  object 
 3   state                 77048 non-null  object 
 4   country               80165 non-null  object 
 5   shape                 78400 non-null  object 
 6   duration (seconds)    80332 non-null  object 
 7   duration (hours/min)  80332 non-null  object 
 8   comments              80317 non-null  object 
 9   date posted           80332 non-null  object 
 10  latitude              80332 non-null  object 
 11  longitude             80332 non-null  float64



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





