# NY-CITY-BIKE

1. Import the Citybike_database.csv file.
	import pandas as pd
	import os
	from datetime import datetime
	from pandas import DataFrame

2. Import the Citybike_database.csv file. 
	citibike_tripdata = os.path.join(r"C:/Users/AYOOLA5/Desktop/University of Toronto/MODULE 14/NY-CITY-BIKE/201908-citibike-tripdata.csv")
	# Read the City and Ride Data
	citibike_data_df = pd.read_csv(citibike_tripdata)
3.citibike_data_df
4.citibike_data_df.head()
5.citibike_data_df['tripduration'] = pd.to_datetime(citibike_data_df['tripduration'], errors='ignore',unit = 's')
6.citibike_data_df

Tableau links : https://public.tableau.com/app/profile/adegbenga.olusoji.ayoola/viz/201908-Citibike-Tripdata_Output/NYC_CitibikeStory?publish=yes