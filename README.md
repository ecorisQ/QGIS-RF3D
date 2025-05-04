Based on a digital elevation model (DEM) and a polygon or line input (terrain / forest / rockfall nets), this plugin rasterizes the attributes from the vector layer, ensuring alignment of all output rasters with the DEM grid, and the correct output format of all data (ASCII grid). 

The tool includes internal checks for invalid geometries, mismatched coordinate reference systems (CRS), and missing values. In addition, attributes are validated against predefined type and value constraints that reflect the expectations of the Rockyfor3D model. The user is informed if any values fall outside expected ranges or if data types do not match. 

The tool performs an additional check to identify values in the two outer rows or columns of the ROCKDENSITY raster, which will not be considered in the Rockyfor3D simulation.

### Installation
1. Save the zipped(!) code folder somewhere on your computer.
2. Open QGIS, go to Plugins > Manage and Install Plugins > Install from ZIP.
3. Click on the 3 dots, browse to the zipped folder and then click on Install Plugin.

The plugin ("Create Rockyfor3D Input Rasters") is available in QGIS from the plugin menu, the processing toolbox or directly from the toolbar.

### Get Rockyfor3D (free for ecorisQ members)
https://www.ecorisq.org/ecorisq-tools
