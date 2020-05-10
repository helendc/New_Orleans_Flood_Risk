# New_Orleans_Flood_Risk

#### Our group researched historical flooding in New Orleans with the intention of predicting flood risk over time. 
#### We focused on the following factors: precipitation, gage height, tidal levels, sea temperature, hurricane seasons, wind speeds, and land sinkage. 
#### We collected these factors from various databases including NOAA and USGS. Each factor was recorded daily over the span of 2007-2020.
#### Using tools such as pandas, numpy, xarray, matplotlib, and geopandas, we plotted an analyzed each factor in Jupyter Notebooks to better understand its contribution to flood risk. 
#### We compiled all of our data into a single csv file, organized by time, giving us a total of over 4,300 data points taken over 13 years.
#### We then read this csv into a Jupyter Notebook as a pandas dataframe and used One-Hot Encoding techniques to convert our date column into a computer-recognizable format. 
#### We then used scikit learn's built-in structures, such as Random Forest Regression and Train Test Split, to create an 80% training and 20% testing split on our data. 
#### We made gage height our dependent variable, as we were predicting flood levels to determine risk. 
#### Our final model had an accuracy of 78%.
#### Our next steps in this project would be to include location variables, such as elevation and distance from levees, to determine relative risk of specified locations.

#### The coode found in New_Orleans_Flood_Risk/Final_Notebook_Nola_Flooding will run provided with the datasets we used.

### Below are screenshots of the output of the code.
![Capture](https://user-images.githubusercontent.com/46548925/81460999-0046d800-9177-11ea-831f-153e69eb3874.JPG)
![Capture2](https://user-images.githubusercontent.com/46548925/81461008-076de600-9177-11ea-96ed-cac5e08ca0ba.JPG)
![Capture3](https://user-images.githubusercontent.com/46548925/81461011-0c329a00-9177-11ea-97f0-30299578d0c3.JPG)
![Capture4](https://user-images.githubusercontent.com/46548925/81461015-0e94f400-9177-11ea-81ff-8423ef012d20.JPG)
![Capture5](https://user-images.githubusercontent.com/46548925/81461017-12287b00-9177-11ea-8ef4-12e2b9a191b2.JPG)
![Capture6](https://user-images.githubusercontent.com/46548925/81461018-13f23e80-9177-11ea-982a-6656fc0d3948.JPG)
![Capture7](https://user-images.githubusercontent.com/46548925/81461019-15bc0200-9177-11ea-967e-aa173a30e442.JPG)
![Capture8](https://user-images.githubusercontent.com/46548925/81461021-1785c580-9177-11ea-9ac6-e7fbbea6eb51.JPG)
