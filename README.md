## Shapefiles
Shapefile of countries are available at:
https://earthworks.stanford.edu/catalog/stanford-xq035qm8233
Detailed shapefiles of Slovakia
https://www.geoportal.sk/en/zbgis/download/

## Country ISO codes
https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes
	- 2 letter code: Alpha-2 code
	- 3 letter code: Alpha-3 code

## Virtual Environmnet
How to create *dekkenv* for developing python code using Terminal.

1) update conda
```
conda update -n base -c defaults conda
```

2) create *dekkenv* environment using conda (I guess most of the people have python 3.9)
```
conda create -n dekkenv python=3.9
```

3) activate *dekkenv*
```
conda activate dekkenv
```

4.a) install packages using pip3
```
pip3 install pandas
pip3 install geopandas
pip3 install matplotlib
pip3 install mapclassify
pip3 install plotly
pip3 install pyvis
pip3 install jupyterlab
```
4.b) install packages from *requirements.txt*
```
pip3 install -r /path_to/requirements.txt
```

5) start developing in jupyter notebook 
```
jupyter lab --allow-root --ip=0.0.0.0 --no-browser
```
and opening one of the URLs

