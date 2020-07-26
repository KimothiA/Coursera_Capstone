# Battle Of The Neighborhoods
Capstone project in the applied data science course on Coursera

# Toronto Neighborhood Clustering

The objective of the exercise is to group similar neighborhoods (PoIs identified via postal codes) basis the type of establishments in their vicinity. The neighborhood information is retrieved using the FourSquare places search API. 

There are three notebooks that have been used for this project  - 
1. Scraping_Wikipedia.ipynb - This notebook scrapes the Postal Codes in Toronto, Ontario and the respective Boroughs and Neighborhoods from Wikipedia.

2. ExtractingLocations.ipynb - This notebook appends the latitude and longitude information to the PoIs using geocoder and geolocator apis. However, the data was finally extracted using the geospatial data at  http://cocl.us/Geospatial_data

3. NeighborhoodClustering.ipynb - This notebook uses the lat/long data for all PoIs to extract neighborhood information via the FourSquare places API. Subsequently, it uses K-means clustering to group PoIs with similar category of venues in their vicinity.

Note that this is a basic exercise in data extraction and clustering. Appending more data and refining the clustering will provide better results