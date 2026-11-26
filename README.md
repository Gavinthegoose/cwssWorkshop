# CWSS 2026 Workshop Saskatoon - Kochia

## Metadata

**Author:** Walker Maess; Kwabena Nketia  
**Email:** walker.maess@usask.ca  
**Date:** Tue Nov 24 20:46:44 UTC 2026

## Project Background

This workshop works through how to create an On/Off Variable Rate application map for herbicide products. In this workshop we take on the role of an agronomist, where your client has requested a maVRA map of their field to target areas of high kochia density. The client, located in the Black Soil Zone of Saskatchewan, has indicated that he will be using Edge MicroActiv to treat areas heavily affected by kochia. To achieve the client's wishes we have flown this field with a drone equipped with a multispectral camera. Images have been stitched together using photogrammetry software. Our job is to take this imagery and create a VRA map ready to be imported into the clients JD 4630 display.  


## Directories
```bash
.
├── README
├── documentation
│   └── imagery
├── projects
├── rawData
│   └── goodaleWheat_Kochia
├── scripts
│   └── r
└── workingFiles
    ├── raster
    └── vector

11 directories

```

### /README

README information on the project

### /documentation

Instructions on how to complete this workshop

### /projects

A good place to store QGIS project files. Highly recommended you use this directory to save the `.qgz` from QGIS.

### /rawData

Raw UAV imagery, not stored on Github due to it's size.

### /scripts

R script used to create the vegetation indices used in this project. Meant to be readable and usable for a variety of data.

### /workingFiles

Intermediate files from the processed vegetation indices. Outputs from QGIS functions should be saved here.

#### /raster

Raster files created from this project. It is recommended you use these folder structures for completing this workshop.  

#### /vector

Vector files created during the creation of this project. Excellent examples of organizing a project directory when dealing with Variable Rate Application maps for agriculture equipment is found within this directory. `documentation` describes how each file found within is created. `bounds/` holds the field border of the project. This data was created, hence it is not in `rawData`.  
