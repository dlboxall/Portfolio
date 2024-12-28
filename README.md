# Portfolio
*work in progress!*
Water Quality Project: Sioux Falls recently noted measurable quantities of "forever chemicals" in the water supply. In investigating a water quality data set for the Sioux Falls area, I noticed that the average pH of the surface water was significantly above the expected pH of 7.4. Even if the contributions to overall alkalinity from the rock types found in the Big Sioux River Basin, an average alkalinity of ~8.5 is roughly 10 times that expected for surface water (pH = 7.4). Further data exploration revealed that there are a significant number of outliers present and that the outliers are not uniformly distributed around the interquartile range.
Update 12/2024: Tried numerous types of fitting to find a relationship between pH and the other features in the dataset.  The only fit that did not result in negative R^2 values was an elastic fit model.

__Completed:__
1. Generated a Folium map of the sampling locations with possible point sources of water pollution also indicated.
2. Generated a clean(er) version of the Big Sioux River water quality data file (clean_SiouxFalls_water.csv).  An analysis of the relationship between air temperature and water temperature was completed.  The logistic fit was used to fill missing water temperature values. The analysis is available in this repository in the "Replace_Missing_Temp" branch.
3. Determined the mean pH value and standard deviation using pH values for all sampling locations. The outliers were stripped out of the dataframe prior to the determination.
Work that remains to be done: 
-determine a relationship between air temperature and water temperature to fill in ~400 missing water temperature values for the five water sampling stations tracked in the data set.
-determine whether the numerous outliers are due to instrumental error or indicative of local pollution events
