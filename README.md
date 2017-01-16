#Module Overview

#Aims

The module has two main aims. First, it seeks to to provide hands-on experience and training in the design and generation of web-based mapping and geographical information tools. Second, it seeks to provide hands-on experience and training in the use of software to access, analyse and visualize web-based geographical information.

# Locations, Timetable and Staff

##Locations
* Lecture: Tuesdays - 15.00 - 16.00, Room 604 Roxby (building 107, map E2)
* Practical: Wednesdays - 9.00 - 11.00 Room 604 Roxby (building 107, map E2)


## Timetable

| Week | Lecture Session  | Practical Session  | Lecture | Practical |
|------|------------------|--------------------|---------|-----------|
| 1    | 31/01/2017       | 01/02/2017         |  Gavin  | Kostas    |
| 2    | 07/02/2017       | 08/02/2017         |  Kostas | Kostas    |
| 3    | 14/02/2017       | 15/02/2017         |  Hai    | Kostas    |
| 4    | 21/02/2017       | 22/02/2017         | Kostas  | Kostas    |
| 5    | 28/02/2017       | 01/03/2017         | Hai     | Hai       |
| 6    | 07/03/2017       | 08/03/2017         | Hai     | Hai       |
| 7    | 14/03/2017       | 15/03/2017         | Hai   | Kostas (Clinic) |
|      | Break week and EASTER  |               |         |          |
| 8    | 25/04/2017       | 26/04/2017         | Michail  | Michai   |
| 9    | 02/05/2017       | 03/05/2017         |  Kostas  | Michail  |
| 10   | 09/05/2017       | 10/05/2017         | Kostas   | Kostas (Clinic) |


## Staff
The module lead is Gavin Dong who can be contacted at [guanpeng.dong@liverpool.ac.uk](mailto:guanpeng.dong@liverpool.ac.uk) regarding any queries related to the module.  Content is being delivered by a number of other academics within the [Geographic Data Science Lab](http://geographicdatascience.com/) including Hai Nguyen, Kostas Daras and Michail Pavlis.

# Assignments

There are two assignments for this module; both with a 50% weighting.

* **Assignment 1:** Using R and the Police.UK API, create maps for Liverpool that illustrate how the geography of crime has changed over a 12 month period. For this assignment you will need to submit your R code as an Rmarkdown file alongside an HTML created output. Additional credit will be given if an interactive map is created using Leaflet. Your Rmarkdown and HTML document should provide a description of the design choices taken.
*Due the end of Week 7*

* **Assignment 2:** Using either CartoDB or Mapbox Studio, create an Index of Multiple Deprivation (IMD) Map for Liverpool. This should graphically illustrate the overall IMD decile that each Lower Layer Super Output Area (LSOA) is assigned, and provide additional information about the LSOA using a rollover.
*Due the end of Week 12*


# Content

## Week 1
### Lecture: An Introduction to Web Mapping and Analysis
* Module structure, delivery and context
*  Background / history of the Geoweb

### Practical:  An Introduction to the R Language
* Language basics
* Basic data wrangling

### Reading and Resources:
* Field, A., Miles, J., Field, Z. (2012) Discovering statistics using R. London: Sage.
* Haklay, M., Singleton, A., and Parker, C. (2008). Web Mapping 2.0: The Neogeography of the GeoWeb. Geography Compass, 2(6):2011–2039.
* Chapter 10 - "The Geoweb" in Longley, P., Goodchild, M., Maguire, D., Rhind, D. (2015) Geographic Information Science and Systems. Hoboken, NJ: Wiley.
* Chapter 2 - "Data and Plots" in Brunsdon, C., Comber, L. (2015) An Introduction to R for Spatial Analysis and Mapping. London: Sage.

*Code School*

* R: https://www.codeschool.com/courses/try-r

### Files:

* Presentation (PowerPoint): [Lecture 1](/training/WebMapping/Lecture_1.pdf)
* Lab: [HTML](/training/WebMapping/Practical1)
* Lab Files (Zip): [Download](/training/WebMapping/P1.zip)


***

## Week 2
### Lecture: R for Mapping
* An example of R for mapping
* R as a GIS
* Basic R for making maps
* R Studio

### Practical: Using R for Mapping and Vizualization
* Graphs in ggplot
* Importing spatial data
* Creating maps with points, lines and polygons

### Reading and Resources:
* Chapter 5 - "Representing Geography"  in Longley, P., Goodchild, M., Maguire, D., Rhind, D. (2015) Geographic Information Science and Systems. Hoboken, NJ: Wiley.
* Chapter 3 - "Handling Spatial Data in R" in Brunsdon, C., Comber, L. (2015) An Introduction to R for Spatial Analysis and Mapping. London: Sage.
* Chapter 1 - "Spatial Data Visualization in R" in Brunsdon, C., Singleton, A.D. Geocomputation: A Practical Primer. London: Sage.

### Files:

* Presentation (PowerPoint): [Lecture 2](/training/WebMapping/Lecture_2.pdf)
* Lab: [HTML](training/WebMapping/Practical2)
* Lab Files (Zip): [Download](/training/WebMapping/P2.zip)

***

## Week 3
### Lecture: The Anatomy and Social Science of the Internet
* Internet infrastructure
* Servers
* Communication protocols - HTTP etc; authentication - oa auth
* Broadband speeds and constraints
* Social context - use and engagement

### Practical: Linking R to the Web (Mapping and Analysis)
* R Google maps
* ggmap
* geocoding
* Google Routing

### Reading and Resources:
* Dodge, M., Kitchin, R. (2001) Atlas of Cyberspace. Boston: Pearson.
* Kurose, J.F., Ross,K.W. (2013) Computer networking: a top-down approach. Boston: Pearson.
* Riddlesden, D. and Singleton, A. (2014). Broadband speed equity: A new digital divide?. Applied Geography, 52, 25–33.

### Files:

* Presentation (PowerPoint): [Lecture 3](/training/WebMapping/Lecture_3.pdf)
* Lab: [HTML](training/WebMapping/Practical3)
* Lab Files (Zip): [Download](/training/WebMapping/P3.zip)

***

## Week 4
### The Internet as a Geographic Data Source
* Passive V Active Data Collection
	* Sensors
		* People
		* Environment
	* Volunteered Geographic Information (VGI)
	* OpenStreetMap
* Bias
* Data formats
	* CSV
	* XML / JSON etc
* Web API

### Practical: Linking R to the Web (Data)
* Reading CSV from the web
  * Police.uk - https://data.police.uk/data/
  * Department for Education
* Rcurl
* API examples
  * Wikipedia
  * Twitter
* Functions

### Reading and Resources:
* Kitchin, R. (2014) The Data Revolution: Big Data, Open Data, Data Infrastructures & Their Consequences. London: Sage.
* Goodchild, M.F. (2007) Citizens as sensors: the world of volunteered geography. GeoJournal 69 (4): 211–221.
* Hacklay, M, Weber, P. (2008) OpenStreetMap: User-Generated Street Maps Pervasive Computing, IEEE  (Volume:7, Issue: 4) Available from [http://discovery.ucl.ac.uk/13849/1/13849.pdf](http://discovery.ucl.ac.uk/13849/1/13849.pdf)
* Russell, M.A. (2013) Mining the Social Web. Second Edition. Sebastopol, CA: O'Reilly Media.

### Files:

* Presentation (PowerPoint): [Lecture 4](/training/WebMapping/Lecture_4.pdf)
* Lab: [HTML](training/WebMapping/Practical4)
* Lab Files (Zip): None...

***

## Week 5:
### Lecture: Coding Basic Web Pages
* HTML
*  CSS
  * Bootstrap (and other frameworks)
* Interactivity
  * Javascript and frameworks
  * PHP
  * Node.js

### Practical: Interactive Mapping in R Pt 1
* Creating basic Leaflet spatial data interfaces

### Reading and Resources:
* Ducket,J. (2011) HTML & CSS. Indianapolis, USA: Wiley.
* Leaflet (2015) API Reference. Available from: http://leafletjs.com/reference.html
* Ducket, J. (2014) JavaScript & jQuery : interactive front-end web development.  Indianapolis, USA: Wiley.

*Code School*

* JQuery: https://www.codeschool.com/courses/try-jquery
* SQL: https://www.codeschool.com/courses/try-sql

### Files:

* Presentation (PowerPoint): [Lecture 5](/training/WebMapping/Lecture_5.pdf)
* Lab: [HTML](training/WebMapping/Practical5_6)
* Lab Files (Zip): [Download](/training/WebMapping/P5_6.zip)

***

## Week 6:
### Lecture: Web Mapping Interfaces
* Overview of Web Mapping Stack
* What are "slippy maps"?
* Interfaces
	* OpenLayers
	* Leaflet
 	* D3
* Leaflet Example

### Practical: Interactive Mapping in R Pt 2
* Creating basic Leaflet spatial data interfaces

### Reading and Resources:
* Leaflet - http://leafletjs.com/

### Files:

* Presentation (PowerPoint): [Lecture 6](/training/WebMapping/Lecture_6.pdf)
* Lab: See week 5...


***

## Week 7:
###  Lecture: Web Mapping Back End: Spatial Databases
* What are databases?
* Examples
	* MYSQL
 	 * PostgreSQL
* SQL
 * Spatial Databases
	* PostGIS (and other spatial databases)
	* Spatial Query


### Practical: Assignment 1 Clinic
* An optional clinic for assistance with assignment 1.

### Reading and Resources:
* Boundless (2015) Introduction to Geoserver. Available here: http://workshops.boundlessgeo.com/geoserver-intro/
* Boundless (2015) An Introduction to PostGIS - http://workshops.boundlessgeo.com/postgis-intro/
* Mapbox (2015) Mapbox Studio Classic source quickstart. Available from: https://www.mapbox.com/guides/source-quickstart/
* CartoDB (2015) CartoDB Tutorials. Available from: http://docs.cartodb.com/tutorials/

### Files:

* Presentation (PowerPoint): [Lecture 7](/training/WebMapping/Lecture_7.pdf)
* Lab: [HTML](training/WebMapping/Practical7)
* Lab Files (Zip): [Download](/training/WebMapping/P7.zip)

---
**EASTER**
---

## Week 8
###  Lecture / Practical : Web Mapping Back End:  Tiles & An Introduction to Cartodb
* What are tiles...
* Servers
	* Web server
	* Tile server – e.g. tilestache
* Web mapping Standards
	* WMS / TMS etc
* Tile Creation
	* Geoserver
	* Mapnik
	* Mapbox Studio
	* An extended example of Cartodb...

### Files:

* Presentation (PowerPoint): [Lecture 8](#)
* Lab: [HTML](#)
* Lab Files (Zip): [Download](#)

***

## Week 9:
### Lecture: Cartography and Web Mapping
* Purpose of a map
* Different types of map
* Components of a map

### Practical: An Introduction to Mapbox Studio
* Custom OpenStreetMap Styling and CartoCSS

### Reading and Resources:
* Krygier, J, Wood, D. (2011) Making Maps. A Visual Guide to Design for GIS. New York: Guilford Press.
* Singleton, A. and Brunsdon, C. (2014) Escaping the pushpin paradigm in geographic information science: (re)presenting national crime data. Area, 46(3), 294–304.
* Tufte, E. (2001) The Visual Display of Quantitative Information. Second Edition. Connecticut: Graphics Press.
* Yau, N. (2011) Visualize This: The Flowing Data Guide to Design, Visualization and Statistics. New York: Wiley.

*Blogs / Websites*

* Stamen Blog (http://content.stamen.com/)
* Mapbox Blog (https://www.mapbox.com/blog/)
* ArcGIS Book - http://learn.arcgis.com/en/arcgis-book/

### Files:

* Presentation (PowerPoint): [Lecture 9](/training/WebMapping/Lecture_9.pdf)
* Lab: [HTML](#)
* Lab Files (Zip): [Download](#)


***

## Week 10
### Lecture: A Gallery of Web Mapping and Analysis Applications
This lecture presents a range of web mapping and analysis applications.

### Practical: Assignment 2 Clinic
* An optional clinic for assistance with assignment 1.

### Files:

* Presentation (PowerPoint): [Lecture 10](#)
* Lab: [HTML](training/WebMapping/Practical1)
* Lab Files (Zip): [Download](/training/WebMapping/P1.zip)



***

