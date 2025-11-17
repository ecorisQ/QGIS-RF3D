This QGIS plugin facilitates the data preparation for the rockfall simulation model Rockyfor3D. Based on a digital elevation model (DEM) and a polygon or line input (terrain / forest / rockfall nets), the plugin rasterizes the attributes from the vector layer, ensuring alignment of all output rasters with the DEM grid, and the correct output format of all data (ASCII grid). 

The tool includes internal checks for invalid geometries, mismatched coordinate reference systems (CRS), and missing values. In addition, attributes are validated against predefined type and value constraints that reflect the expectations of the Rockyfor3D model. The user is informed if any values fall outside expected ranges or if data types do not match. 

The tool performs an additional check to identify values in the two outer rows or columns of the ROCKDENSITY raster, which will not be considered in the Rockyfor3D simulation.

A geopackage template for the terrain / forest / rockfall nets data can be downloaded under https://www.ecorisq.org/publications/various/117-rf3d-vector-templates/file.

### Installation
The plugin ("Rockyfor3D Input Rasters") is available in the official QGIS Plugin repository and can be installed in QGIS via Plugins > Manage and Install Plugins.
Once installed, the plugin is accessible in QGIS from the plugin menu, the processing toolbox or directly from the toolbar.

### Get Rockyfor3D (free for ecorisQ members)
https://www.ecorisq.org/ecorisq-tools
