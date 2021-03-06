# Google Earth Engine - IUCN Red List

Tools for the [IUCN Red List of Ecosystems](https://iucnrle.org) and [IUCN Red List of Threatened Species](https://www.iucnredlist.org) in Google Earth Engine. Feel free to contribute to growing this module, with all contributions recognised accordingly. Get in contact with <nicholas.murray@jcu.edu.au>

Functionality includes:

* Compute Area of Occupancy 
* Compute Area of Occupancy occupied by >1% of ecosystem (red list of ecosystems)
* Compute Extent of Occurrence
* Calculate areas of rasters
* Export a red list report
* Climatic and topographic summaries of ecosystems

Please also see the R package [Redlistr](https://cran.r-project.org/package=redlistr)

## Instructions

This is a [Google Earth Engine](https://earthengine.google.com/) module. 
1. Copy to your earth engine scripts and call it rleFunctions
2. Import into a script and correct the path:
```
var rleFunctions = require('users/murrnick/IUCN-RLE:Modules/rleFunctions');
print('Time now:', rleFunctions.getTime); // call an RLE function
```

## Contributors:

Please feel free to contribute! 

* Nicholas Murray - James Cook University - [Website](https://www.murrayensis.org)
* John Wilshire - Yale University
* Adam Duncan - Wildlife Conservation Society
* Calvin Lee - Deakin University

## Cite as:
Murray N.J., Wilshire, J., Duncan, A., Lee, C. (2020) GEE-redlist: Tools for the [IUCN Red List of Ecosystems](https://iucnrle.org) and [IUCN Red List of Threatened Species](https://www.iucnredlist.org) in Google Earth Engine. Version 0.0.1
