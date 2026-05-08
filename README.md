This is a simple Jupyter notebook Python script that searches EarthData for NISAR observations over a given region of interest (in this case the Gainesville area).

It then makes a simple optical image of the location and then subsets the hdf5 file for a specified region and makes some simple images.  Among these image types are the radar cross-section, co- and cross-polarized from the available time-series.

A color-composite is then made from the time-series median values (on a per pixel basis) of the median co-polarized (HHHH, red), cross-polarized (HVHV, green), and co-polarized standard deviation (HHHH std., blue).

Finally, the data from the composite image are explorted into GeoTIFF format that can be easily imported into tools like ArcGIS, QGIS and GoogleEarth.

This notebook is available both as a downloadable pdf as well as its native format .ipynb
