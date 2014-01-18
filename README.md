Documentation
=============

Tools
=============
-Grass <br> -Qgis <br> -OGR/GDAL <br> -Shell Scripting <be> -GeoJSON <br> -Git/GitHub/GitHub Pages <br> -Markdown

Process
=============
-Extract GRASS data using QGis <br> -Convert and reproject to WGS84 lat/lon (EPSG:4326) <br> -Convert shapefiles to GeoJSON in a Test Directory <br> -Automate the conversion with this shell script ... <br>		       for f in *.shp; do ogr2ogr -f "GeoJSON" -s_srs EPSG:2285 -t_srs EPSG:4326  ${f/.shp}_4326.geojson $f; done <br> -Create repo on GitHub <br> -Push data to GitHub 