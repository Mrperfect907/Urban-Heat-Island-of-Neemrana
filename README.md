# Urban Heat Island of Neemrana

This repository contains a QGIS project and associated spatial data for analyzing the Urban Heat Island (UHI) effect in Neemrana.

## Project Contents

- **`UHA of Neemrana.qgz`**: The main QGIS project file containing the map composition, layers, and styling for the Urban Heat Assessment/Analysis of Neemrana.
- **`clip band 4.tif`**: Clipped raster dataset for Band 4 (Red) from satellite imagery (typically Landsat 8).
- **`clip band 5.tif`**: Clipped raster dataset for Band 5 (Near-Infrared / NIR). This is commonly combined with Band 4 to calculate the Normalized Difference Vegetation Index (NDVI) for assessing vegetation cover.
- **`clip band 10.tif`**: Clipped raster dataset for Band 10 (Thermal Infrared). This is used to derive Land Surface Temperature (LST), which is critical for identifying heat islands.
- **`*.tif.aux.xml`**: Auxiliary files that store spatial reference and metadata for the TIFF images.

## Methodology Overview

The provided datasets indicate a standard remote sensing workflow for Urban Heat Island mapping, typically utilizing Landsat 8 imagery:
1. **Vegetation Analysis**: Using Bands 4 and 5 to calculate NDVI, helping distinguish between vegetated areas (which have a cooling effect) and built-up urban surfaces.
2. **Surface Temperature Mapping**: Utilizing the thermal Band 10 to calculate the Land Surface Temperature (LST) and identify localized hot spots or urban heat islands.

## How to Use

1. Clone or download this repository to your local machine.
2. Ensure you have [QGIS](https://qgis.org/) installed.
3. Open the **`UHA of Neemrana.qgz`** project file in QGIS to view the layers, analysis, and map composition.
