# Extracting-Canopy-Height-and-Elevation-from-LiDAR-Based-GEDI-Data-Products

is Python Notebook utilizes the GEDI L2A V001 from May 2020 (before California's catastrophic wildfire events of summer 2020) covering the August Complex Fire from Northern California. The script will show you how to employ Python 3.8 to:

- Find granules that contain data within the users's region of interest (ROI) using GEDI Finder tool
- Acquire the user selected granules using Curl in Mac using NASA Earthdata login credentials
- Read and process the dataset
- Filter the dataset by ROI, quality of observations, and Science Dataset (SDS) Layers
- Visualize the spatial footprint of the GEDI using representative observations
- Visualize Canopy Height and Elevation for the single day from May 2020
- Converting the Geopandas GeoDataFrame to Google Earth Engine (GEE) Feature Collections
- Export the Feature Collections to the Asset in GEE for further analysis
