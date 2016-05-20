# Web Mapping and Analysis (ENVS456) - University of Liverpool

## Aims

The module has two main aims. First, it seeks to to provide hands-on experience and training in the design and generation of web-based mapping and geographical information tools. Second, it seeks to provide hands-on experience and training in the use of software to access, analyse and visualize web-based geographical information.

## Assignments

There are two assignments for this module; both with a 50% weighting.

Assignment 1: Using R and the Police.UK API, create maps for Liverpool that illustrate how the geography of crime has changed over a 12 month period. For this assignment you will need to submit your R code as an Rmarkdown file alongside an HTML created output. Additional credit will be given if an interactive map is created using Leaflet. Your Rmarkdown and HTML document should provide a description of the design choices taken. Due the start of Week 8

Assignment 2: Using either CartoDB or Mapbox Studio, create an Index of Multiple Deprivation (IMD) Map for Liverpool. This should graphically illustrate the overall IMD decile that each Lower Layer Super Output Area (LSOA) is assigned, and provide additional information about the LSOA using a rollover. Due the end of Week 12

## Content

### Week 1

**Lecture: An Introduction to Web Mapping and Analysis**

* Module structure, delivery and context
* Background / history of the Geoweb

**Practical: An Introduction to the R Language**

* Language basics
* Basic data wrangling

**Reading and Resources:**

* Field, A., Miles, J., Field, Z. (2012) Discovering statistics using R. London: Sage.
* Haklay, M., Singleton, A., and Parker, C. (2008). Web Mapping 2.0: The Neogeography of the GeoWeb. Geography Compass, 2(6):2011-2039.
* Chapter 10 - "The Geoweb" in Longley, P., Goodchild, M., Maguire, D., Rhind, D. (2015) Geographic Information Science and Systems. Hoboken, NJ: Wiley.
* Chapter 2 - "Data and Plots" in Brunsdon, C., Comber, L. (2015) An Introduction to R for Spatial Analysis and Mapping. London: Sage.

* Code School
	* R: https://www.codeschool.com/courses/try-r

**Files:**

* Presentation: [Lecture 1](/Lectures/Lecture_1.pdf)
* Lab: HTML
* Lab Files (Zip): Download

### Week 2

**Lecture: R for Mapping**

* An example of R for mapping
* R as a GIS
* Basic R for making maps
* R Studio

**Practical: Using R for Mapping and Vizualization**

* Graphs in ggplot
* Importing spatial data
* Creating maps with points, lines and polygons
Reading and Resources:

Chapter 5 - â€œRepresenting Geographyâ€ in Longley, P., Goodchild, M., Maguire, D., Rhind, D. (2015) Geographic Information Science and Systems. Hoboken, NJ: Wiley.
Chapter 3 - â€œHandling Spatial Data in Râ€ in Brunsdon, C., Comber, L. (2015) An Introduction to R for Spatial Analysis and Mapping. London: Sage.
Chapter 1 - â€œSpatial Data Visualization in Râ€ in Brunsdon, C., Singleton, A.D. Geocomputation: A Practical Primer. London: Sage.
Files:

Presentation: Lecture 2
Lab: HTML
Lab Files (Zip): Download
Week 3

Lecture: The Anatomy and Social Science of the Internet

Internet infrastructure
Servers
Communication protocols - HTTP etc; authentication - oa auth
Broadband speeds and constraints
Social context - use and engagement
Practical: Linking R to the Web (Mapping and Analysis)

R Google maps
ggmap
geocoding
Google Routing
Reading and Resources:

Dodge, M., Kitchin, R. (2001) Atlas of Cyberspace. Boston: Pearson.
Kurose, J.F., Ross,K.W. (2013) Computer networking: a top-down approach. Boston: Pearson.
Riddlesden, D. and Singleton, A. (2014). Broadband speed equity: A new digital divide?. Applied Geography, 52, 25-33.
Files:

Presentation: Lecture 3
Lab: HTML
Lab Files (Zip): Download
Week 4

The Internet as a Geographic Data Source

Passive V Active Data Collection
Sensors
People
Environment
Volunteered Geographic Information (VGI)
OpenStreetMap
Bias
Data formats
CSV
XML / JSON etc
Web API
Practical: Linking R to the Web (Data)

Reading CSV from the web
Police.uk - https://data.police.uk/data/
Department for Education
Rcurl
API examples
Wikipedia
Twitter
Functions
Reading and Resources:

Kitchin, R. (2014) The Data Revolution: Big Data, Open Data, Data Infrastructures & Their Consequences. London: Sage.
Goodchild, M.F. (2007) Citizens as sensors: the world of volunteered geography. GeoJournal 69 (4): 211-221.
Hacklay, M, Weber, P. (2008) OpenStreetMap: User-Generated Street Maps Pervasive Computing, IEEE (Volume:7, Issue: 4) Available from http://discovery.ucl.ac.uk/13849/1/13849.pdf
Russell, M.A. (2013) Mining the Social Web. Second Edition. Sebastopol, CA: Oâ€™Reilly Media.
Files:

Presentation: Lecture 4
Lab: HTML
Lab Files (Zip): Noneâ€¦
Week 5:

Lecture: Coding Basic Web Pages

HTML
CSS
Bootstrap (and other frameworks)
Interactivity
Javascript and frameworks
PHP
Node.js
Practical: Interactive Mapping in R Pt 1

Creating basic Leaflet spatial data interfaces
Reading and Resources:

Ducket,J. (2011) HTML & CSS. Indianapolis, USA: Wiley.
Leaflet (2015) API Reference. Available from: http://leafletjs.com/reference.html
Ducket, J. (2014) JavaScript & jQuery : interactive front-end web development. Indianapolis, USA: Wiley.
Code School

JQuery: https://www.codeschool.com/courses/try-jquery
SQL: https://www.codeschool.com/courses/try-sql
Files:

Presentation: Lecture 5
Lab: HTML
Lab Files (Zip): Download
Week 6:

Lecture: Web Mapping Interfaces

Overview of Web Mapping Stack
What are â€œslippy mapsâ€?
Interfaces
OpenLayers
Leaflet
D3
Leaflet Example
Practical: Interactive Mapping in R Pt 2

Creating basic Leaflet spatial data interfaces
Reading and Resources:

Leaflet - http://leafletjs.com/
Files:

Presentation: Lecture 6
Lab: See week 5â€¦
Week 7:

Lecture: Web Mapping Back End: Spatial Databases

What are databases?
Examples
MYSQL
PostgreSQL
SQL
Spatial Databases
PostGIS (and other spatial databases)
Spatial Query
Practical: Assignment 1 Clinic

An optional clinic for assistance with assignment 1.
Reading and Resources:

Boundless (2015) Introduction to Geoserver. Available here: http://workshops.boundlessgeo.com/geoserver-intro/
Boundless (2015) An Introduction to PostGIS - http://workshops.boundlessgeo.com/postgis-intro/
Mapbox (2015) Mapbox Studio Classic source quickstart. Available from: https://www.mapbox.com/guides/source-quickstart/
CartoDB (2015) CartoDB Tutorials. Available from: http://docs.cartodb.com/tutorials/
Files:

Presentation: Lecture 7
Lab: HTML
Lab Files (Zip): Download
Week 8

Lecture / Practical : Web Mapping Back End: Tiles & An Introduction to Cartodb

What are tilesâ€¦
Servers
Web server
Tile server - e.g.Â tilestache
Web mapping Standards
WMS / TMS etc
Tile Creation
Geoserver
Mapnik
Mapbox Studio
An extended example of Cartodbâ€¦
Files:

Presentation: Lecture 8
Lab: PDF
Lab File 1 (Zip): Download
Lab File 2 (Zip): Download
Lab File 3 (CSV): Download
Lab File 4 (HTML): Download
Week 9:

Lecture: Cartography and Web Mapping

Purpose of a map
Different types of map
Components of a map
Practical: An Introduction to Mapbox Studio

Custom OpenStreetMap Styling and CartoCSS
Reading and Resources:

Krygier, J, Wood, D. (2011) Making Maps. A Visual Guide to Design for GIS. New York: Guilford Press.
Singleton, A. and Brunsdon, C. (2014) Escaping the pushpin paradigm in geographic information science: (re)presenting national crime data. Area, 46(3), 294-304.
Tufte, E. (2001) The Visual Display of Quantitative Information. Second Edition. Connecticut: Graphics Press.
Yau, N. (2011) Visualize This: The Flowing Data Guide to Design, Visualization and Statistics. New York: Wiley.
Blogs / Websites

Stamen Blog (http://content.stamen.com/)
Mapbox Blog (https://www.mapbox.com/blog/)
ArcGIS Book - http://learn.arcgis.com/en/arcgis-book/
Files:

Presentation (PowerPoint): Lecture 9
Lab: PDF
Week 10

Lecture: A Gallery of Web Mapping and Analysis Applications

This lecture presents a range of web mapping and analysis applications.

Practical: Assignment 2 Clinic

An optional clinic for assistance with assignment 1.
Files:

Presentation (PowerPoint): Lecture 10

