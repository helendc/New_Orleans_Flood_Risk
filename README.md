# New_Orleans_Flood_Risk

### Our group researched historical flooding in New Orleans with the intention of predicting flood risk over time. 
### We focused on the following factors: precipitation, gage height, tidal levels, sea temperature, hurricane seasons, wind speeds, and land sinkage. 
### We collected these factors from various databases including NOAA and USGS, and each factor was recorded daily over the span of 2007-2020.
### We plotted an analyzed each factor to better understand its contribution to flood risk. 
### We compiled all of our data into a csv file, organized by time, giving us a total of over 4,300 data points taken over 13 years.
### We then read this csv into a Jupyter Notebook as a pandas dataframe and used One-Hot Encoding techniques to convert our date column into a computer-recognizable format. 
### We then used built-in structures to create an 80% training and 20% testing split on our data. 
### We made gage height our dependent variable, as we were predicting flood levels to determine risk. 
### Our final model had an accuracy of 78%.
### Our next steps in this project would be taking location into account to determine relative risk of specified locations.
