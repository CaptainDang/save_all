# save_all
This script is an official QGIS plugin. It can be found on the official plugin repository here: https://plugins.qgis.org/plugins/SaveAllScript/

The plugin automatically detects the file type of each layer and saves the layers as their original file type if supported, otherwise, it saves as GPKG. Any temporary layers are made permanent. Currently supported vector layer file types: GPKG, SHP, KMZ/KML, CSV. Currently supported raster layer file types: TIF. Any layers without geometry are saved as CSV files. 

While the script was developed for version 3.30 ‘s-Hertogenbosch, it also works in 3.32 Lima. The script has also been successfully used in version 3.16 Hanover, but it is not guaranteed to work in all other versions prior to 3.30.

