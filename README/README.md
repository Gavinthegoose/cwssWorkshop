# CWSS Workshop Saskatoon 2026

## Metadata

  **Author:** Walker Maess; Kwabena Nketia  
  **Email:** walker.maess@usask.ca  
  
## Directories

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
  
### /README

Information about the files contained in this repository

### /documentation

Instructions to complete the workshop prepared for CWSS 2026 hosted in Saskatoon SK.


#### imagery

Screen captured for building the documentation  

### /projects

A directory to place QGIS project files. Not hosted on GitHub, but is a good idea to place in your project root when working on this workshop.  

### /rawData

Not hosted on GitHub, but contains the raw UAV data used to compile rasters found in `workingFiles/raster/goodaleWheat_Kochia`. The R script in `scripts/r` are what convert the raw data to vegetation indiices used in this project.  


#### goodaleWheat_Kochia

Contains the raw imagery on authors local hard disk, not hosted on GitHub.  

### /scripts

Contains R script used to calculate vegetative indices  


#### r

Holds the R scripts  

### /workingFiles

Holds working files created from the manipulation of rawData. Further work in QGIS is saved to this directory. Splits into Vector and Raster for the two data types.  


#### raster

Raster files created during the creation of this project. Great examples of organizing spatial data can be found throughout the directory.  

#### vector

Vector files created during the creation of this project. Excellent examples of organizing a project directory when dealing with Variable Rate Application maps for agriculture equipment is found within this directory. `documentation` describes how each file found within is created. `bounds/` holds the field border of the project. This data was created, hence it is not in `rawData`.  
