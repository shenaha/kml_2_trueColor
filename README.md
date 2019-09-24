## Sentinel 2
A binder consisting of the above code.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2Fshenaha%2Fkml_to_sen2/master)

## About binder

[![Documentation Status](https://readthedocs.org/projects/mybinder/badge/?version=latest)](https://mybinder.readthedocs.io/en/latest/?badge=latest)
[![Join the chat at https://gitter.im/jupyterhub/binder](https://badges.gitter.im/jupyterhub/binder.svg)](https://gitter.im/jupyterhub/binder?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Binder is a tool that lets other people easily launch an interactive copy of your Jupyter notebooks. This repository contains the documentation and usage instructions for the mybinder.org service.

## WorkFlow

* Input : .kml
* Convert KML to GeoJSON
* Download sentinel-2 images with GeoJSON
* Get Sentinel-2 .jp2 bands
* Create True or False colour composites
* Output : .tif
* Future : (NDWI , NDVI etc or band calculation code snippet can be added)


## References
1. stackoverflow
2. gis.stackexchange
3. sentinelsat – using Python to search and download Sentinel 2 data - http://www.acgeospatial.co.uk/sentinelsat_demo/
4. acgeospatial - https://github.com/acgeospatial/Satellite_Imagery_Python/blob/master/SentinelSat_Demo.ipynb
