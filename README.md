# AZ-correctional-facilities

A personal project in the Redistricting Data Hub that involves collecting, processing and visualizing data on correctional facilities in the state of Arizona. 

Raw data sources include: 
* List of correctional facilities in the US as of 1/1/2020 
  * Source: [TIGERweb](https://tigerweb.geo.census.gov/tigerwebmain/Files/bvp20/tigerweb_bvp20_prisons_us.html) 
  * Last accessed: 8/13/2020
* Arizona block-level shapefile as of 2010 Census
  * Source: [Census Bureau](https://catalog.data.gov/dataset/tiger-line-shapefile-2017-2010-state-arizona-2010-census-block-state-based)
  *	Last accessed: 8/13/2020
*	Group quarters data as of 2010 Census 
  *	Source: [2010 Census Summary File 1](https://api.census.gov/data/2010/dec/sf1?), tables P42 and PCT20<br/>
    [Technical Documentation](https://www2.census.gov/programs-surveys/decennial/2010/technical-documentation/complete-tech-docs/summary-file/sf1.pdf?)<br/>
    [Variable List](https://api.census.gov/data/2010/dec/sf1/variables.html)
  * Last accessed: 8/13/2020
  
Processing steps can be found in file `processing.ipynb` and datasets can be found in folder `data` (put your API key in `key.txt`).
