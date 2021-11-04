# 3D_houses
Creating a 3D representation of real estate using DSM and DTM data provided by geopunt (Flemish goverment).

# Description
Using the data provided to model a building in 3D using DSM and DTM. 

# Installation
For this program you need to use the anaconda file managemer:
- rasterio : 'conda install rasterio'
- shapely : 'conda install shapely'
- plotly: 'conda install plotly'
- numpy: 'conda install numpy'

# Usage
This program is one jupyter-notebook file 
this specific file is meant to be used with just 1 DSM file and 1 DTM file, https://downloadagiv.blob.core.windows.net/dhm-vlaanderen-ii-dsm-raster-1m/DHMVIIDSMRAS1m_k15.zip, https://downloadagiv.blob.core.windows.net/dhm-vlaanderen-ii-dtm-raster-1m/DHMVIIDTMRAS1m_k15.zip

download this files and save it in the same directory as the program-file.
Run the 3d_house file using jupyter-notebook and enjoy the view.
the output should be Centraal Station in Antwerpen.

# Visuals

result after running the program

![newplot](https://user-images.githubusercontent.com/42916343/140353081-f5e77759-181d-4e05-b626-16b25f6d6897.png)

# Improvements
main improvement is doing it for the whole flemish region and not only for 1 area/file.
