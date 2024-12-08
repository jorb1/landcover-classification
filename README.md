# An R Analysis of Landcover Classification using Decision Trees
### Author: "Bailey Jørgensen"
https://github.com/jorb1

In this analysis, I am using a form of supervised classification – a decision tree classifier. I will create a land cover classification for southern Santa Barbara County based on multi-spectral imagery and data on the location of 4 land cover types.

![SB Coast Pic](https://amaryroad.com/wp-content/uploads/2020/06/santa-barbara-1024x640.jpeg

## Data

All of the data used in this study were accessed on November 25th, 2024.

To conduct this analysis, I will use the Landsat 5 Thematic Mapper data. More information about these data can be found at this link: https://www.usgs.gov/landsat-missions/landsat-5. 

Specifically, I will be using 1 scene from September 25, 2007 (my birthday!), on bands 1,2, 3, 4, 5, 7, with collection 2 surface reflectance product. 


I will be using a polygon representing southern Santa Barbara county, and a data file with polygons representing sites with training data. These shape files were provided by Ruth Oliver as part of the EDS 223 Geospatial Analysis class at the University of California Santa Barbara, Masters of Environmental Data Science Program. 

## Repository Structure

```bash
├── landcover-classification
│   ├── landcover-classification.Rproj
│   ├── landcover-class.html
│   ├── landcover-class.qmd
│   ├── README.md
│   └── .gitignore
├── data
│   ├── SB_county_south.cpg
│   ├── SB_county_south.dbf
│   ├── SB_county_south.prj
│   ├── SB_county_south.sbn
│   ├── SB_county_south.sbx
│   ├── SB_county_south.shp
│   ├── SB_county_south.shx
│   ├── trainingdata.cpg
│   ├── trainingdata.dbf
│   ├── trainingdata.prj
│   ├── trainingdata.qpj
│   ├── trainingdata.shp
│   └── trainingdata.shx
│   └── landsat-data
```

## Citations:

R. Oliver, EDS 223 - Geospatial Analysis and Remote Sensing, Course Notes. 2024. [Online]. Available: https://eds-223-geospatial.github.io/

U.S. Geological Survey. (n.d.). Landsat 5. Retrieved December 7, 2024, from https://www.usgs.gov/landsat-missions/landsat-5

