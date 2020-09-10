# India_climate_map. 
Create a six cluster climate map for India using mean monthly average rainfall and temperature data for last forty years from Copernicus climate data store. 
Steps are as follows.

- Install Geopandas, Rasterio and Rioxarray.
- Import various libraries.
- Load climate data and extract precipitation and temp data as tiff files.
- Mask data based on India Geojason.
- Fomat data suitably for KMeans clustering.
- Run KMeans.
- Reshape labels and visualize.
