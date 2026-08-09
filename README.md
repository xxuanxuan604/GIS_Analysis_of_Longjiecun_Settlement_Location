# GIS Data and Analytical Outputs for Human–Environment Interaction and Settlement Location in Dian Culture: GIS Evidence from the Longjiecun Site

## Description

This repository contains GIS datasets, spatial analyses, and analytical outputs used in the study of human–environment interaction and settlement location at the Longjiecun site, a settlement site associated with Dian Culture.
The dataset includes original spatial data, preprocessed GIS layers, settlement environment analyses, hydrological modelling outputs, and landscape visibility analyses.
All files are provided to support research transparency and reproducibility of GIS-based archaeological analysis.

## Software

QGIS version 3.44

## Coordinate System

All spatial datasets were standardized using:
WGS 84 / UTM Zone 48N (EPSG:32648)

## Repository Structure

### 01_Input_Data

This folder contains original datasets collected from external sources, including:
- Yuxi_Urban_Area_DEM: original 5 m resolution DEM data covering the Yuxi urban area.
- Coordinates_of_Sites_and_Cemeteries_Latitude_and_Longitude: geographic coordinates of the Longjiecun settlement and Lijiashan cemetery.
- Yunnan_Province_water_bodies: water body datasets of Yunnan Province, including Xingyun Lake and Fuxian Lake.
- Annual_Average_Precipitation_Data: annual average precipitation data.
- Jiangcheng_Town_Satellite_Imagery_and_Regional_KML: satellite imagery and regional KML data used for spatial reference.

### 02_Prepare

This folder contains preprocessed spatial datasets prepared for subsequent GIS analyses, including projection transformation, spatial clipping, raster preparation, and basic terrain derivatives.
Contents include:
- BaseMap
- Dem_cut: clipped DEM prepared for spatial analysis.
- Equal_high: contour data derived from DEM.
- Hillshade: terrain visualization data.
- Slope: slope map.
- LiJiaShan_cemetery and LongJieCun_site: projected archaeological location points.

### 03_Settlement_Analysis

This folder contains GIS analyses related to settlement location and environmental context.
The analyses include:
- Eight-direction aspect analysis.
- r.geomorphon classification.
- Topographic Position Index (TPI) analysis.
These analyses aim to characterize the topographic and geomorphological contexts of the Longjiecun settlement and Lijiashan cemetery.

### 04_Hydrology

This folder contains hydrological analyses used to investigate the relationship between settlement location and water environments.
The processing workflow includes:
- Drainage basin delineation.
- DEM filling (Filled_DEM).
- Flow direction analysis.
- Flow accumulation analysis.
The analytical outputs include:
- Wet-season and dry-season river vector datasets.
- Stream extraction results.
- Strahler stream order classification.
- Buffer analysis.
- Shortest distance analysis between the settlement and seasonal water systems.

### 05_Landscape_Analysis

This folder contains visibility and landscape analyses examining spatial relationships between the Longjiecun settlement and surrounding landscape features.
Contents include:
- Viewshed analysis.
- Visibility analysis.
- Intervisibility analysis.
- Least-cost path analysis.

### QGIS Project

The QGIS project file integrates all spatial layers and analytical outputs used in this study.
File name:
Longjiecun_Settlement_Choice.qgz

## Reproducibility

This repository provides GIS project files, spatial datasets, processing records, and analytical outputs to facilitate research reproducibility.
The shared materials allow users to review the spatial data, analytical workflows, and GIS-based interpretations presented in this study.
