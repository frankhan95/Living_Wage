# Living Wages in the USA

### Description
Living costs vary by region and the minimum wage is not always sufficient. Dr. Amy Glasmeir at MIT has built a living wage model and presented her findings on her website. This visualization uses her data to compare living costs and minimum wages at U.S county levels. 

#### Workflow
1. Create python web scraper [Jupyter Notebook](https://github.com/frankhan95/Living_Wage/blob/master/WebScraper/Wage_Scraper.ipynb)
2. Import [results](https://github.com/frankhan95/Living_Wage/blob/master/WebScraper/Data_Tables/Scraped_USA_Wages.csv) into an [ArcMap Document](https://github.com/frankhan95/Living_Wage/blob/master/WebScraper/Example.mxd)
3. Append FIPS codes to each county.
4. Write [MapBox App](https://github.com/frankhan95/Living_Wage/tree/master/Living_Wage_Mapbox) and bind [county geometries](https://www.census.gov/geo/maps-data/data/cbf/cbf_counties.html).

#### [The MapBox Interactive for the entire USA.](http://students.washington.edu/fhan/living_wage/)
![Mapbox Screenshot](https://github.com/frankhan95/Living_Wage/blob/master/Screenshots/mapbox_ver.png)

### Data Sources
1. [Living Wages](http://livingwage.mit.edu)
2. [County Polygons](https://www.census.gov/geo/maps-data/data/cbf/cbf_counties.html)

