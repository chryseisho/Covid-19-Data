# Covid-19-Data
Here are remarks of two Coursera lessons:
1. [Analysing Covid-19 Geospatial data with Python](https://www.coursera.org/learn/geospatial-covid19-python/home/welcome)
1. [Python Geospatial Data Analysis](https://www.coursera.org/learn/python-geospatial-data-analysis/home/welcome)

### Applied packages 
numpy, pandas, geopandas, contextily, matplotlib, folium

### Applied database
covid-19 data from 2020-01-22 to 2021-01-31, containing information such as date, country, geolocation, CumulativePositive, CumulativeDeceased, CumulativeRecovered, CurrentlyPositive, etc.

### Aims: 
1. preprocess geospatial data 
1. Perform Spatial join with different datasets 
1. create and visulize maps --- geopandas
1. generate heat map with circular markers --- folium


## Notes of each step
### 1. Reading and Tidying up Data
* get rid of unused rows
* get rid of NA variables??
* tidy up the [data type](https://numpy.org/doc/stable/user/basics.types.html) 

### 2. Creating geodataframe
* eliminate NA values --- [pd.dropna](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dropna.html)
* set a coordinate system to the df to make it into gdf
* [gpd.GeoDataFrame](https://geopandas.org/gallery/create_geopandas_from_pandas.html) (df, crs, geometry=)
* plotting: 
  * [.plot()](https://towardsdatascience.com/what-are-the-plt-and-ax-in-matplotlib-exactly-d2cf4bf164a9) -- gdf.plot(ax=, color='', alpha=, figsize=(12,10)); 
  * [plt.xxx()]() -- plt.plot( ); plt.title( ); plt.show( )

### 3. 







**Have Fun!** :blush::wink::innocent:
