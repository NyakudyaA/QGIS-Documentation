GIS For CAPS
================================================= 

* 1. Concept of GIS.

* 2. Reasons for development.

* 3. Different types of data used in a GIS.

* 4. Capturing different types of data.

* 5. Data standardisation, data sharing and data security.

* 6. Data manipulation.

Concept of GIS
-------------------------------------------------------------------------------

Geographic Information Systems (GIS) 

A GIS is a map-based system that integrates map features with information about map 
features, for example when a map is used with a guidebook that refers to the map. A 
map feature is any feature on the earth that is represented on a map, usually as a 
symbol (conventional signs). A computerised GIS links map features to data about the
map features in a digital form.

* In a GIS, a feature represents, or 'models', something in space ('space' in this 
context usually being the surface of the Earth).

* Many different types of data can put into a GIS. For example, spatial data and 
attribute data.

* Vector and raster data are examples of spatial data.

* A GIS is used to gather and organise spatial data using computer software so that it
can be displayed and analysed. 

* Projected data consists of coordinates that are in a planar coordinate reference system
(cartesian plane) instead of latitude and longitude (angular measurements).





Understanding how the components of a GIS work together
........................................................

.. image:: /static/training_manual/foreword/gis1.png
   :align: center

* A GIS helps people to better see patterns, relationships and trends and thereby make 
informed decisions.

* The hardware includes the computer, network and peripheral devices such as printers, 
GPS’s, mobile devices, scanners and digitisers.

* The software provides the functions and tools users need to store, analyse and display 
geographic information. Today there are both proprietary and open GIS software packages 
that are available for all computer operating systems.

* The most important component of a GIS is the data and it must be accurate. The different 
data types include vector, raster and attribute data.

* Methods in a GIS refer to the rules or procedures that determine how the technology
is applied.

* People may include managers, programmers, analysts, cartographers, end users and 
consumers. In South Africa, GIS professionals are known as ‘GISc’ professionals 
(Geoinformation Science) and can be GISc Technicians, Technologists or Professional 
Practitioners.



Understanding projected data
..........................................

* A projection is a mathematical formula by which the curved surface of the earth is 
displayed on a flat surface.

* All maps are projected and therefore all are distorted to some degree from what they 
represent in reality.

* Projected coordinates are transformed from latitude and longitude angular measurements 
to x, y planar coordinates using map projections.

* Maps cannot be overlaid in a GIS if the data are not in the same coordinate reference 
system. Understanding projections is a vital component of a GIS.



Reasons for development 
-----------------------------

* The Father of GIS is said to be Roger Tomlinson. In 1962 he developed a computer system 
to manage Canadian land use. The speed of modelling was so impressive that it meant that 
similar systems were adopted elsewhere to solve spatial problems.

* Prior to the computerisation of maps, geographic data was manually overlaid onto other 
printed maps to help answer spatial questions. Computers enabled geographers to speed up 
this process of overlaying information and so the field of Geographic Information Systems 
was born.

* Today you would be hard-pressed to find an industry that does not use GIS to help solve 
problems. Time is money for many industries and so GIS specialists are now sought-after 
professionals.

.. image:: /static/training_manual/foreword/gis2.png
   :align: center


Different types of data used in a GIS 
--------------------------------------

There are two main types of data that can be put into a GIS, namely attribute data and spatial 
data. The extra, non-spatial information about map features is called attribute data. The most 
common examples of spatial data are raster and vector.

Key concepts
..............

* Data is any collection of related facts arranged in a particular format that are produced, 
stored or processed by a computer.

* A GIS data-base includes data about the spatial locations and shapes of geographic features 
and shape of geographic features recorded as points, lines, areas, pixels, grid cells or TINs 
as well as their attributes.

* Spatially referenced data are often referred to as georeferenced data. This means any data 
that can be put into a GIS and given a coordinate or a latitude and longitude reference pointer
, or any data that can be mapped.

* Attributes are also known as 'fields' or 'columns'. The attributes that make up a record in a 
GIS, describe a feature.

Spatial and attribute data
............................

Spatial data

* Spatial data, also called geographic data, is information describing the location and geometry 
of things.

* Spatial data is stored, managed and passed around in various formats. Some formats are 
software-specific or 'proprietary' and others formats are open and standards-compliant.

Attribute data

* Attribute data is tabular or textual data describing the geographic characteristics or non-spatial 
information of features. 
 
* Examples of attribute data for a river might be the name of the river, length, stream order, drainage
basin name, sediment load and discharge.

* Attribute data is linked in a table in a database by a unique identifier.

* Attribute data can be in either be vector data (rivers) or raster data (satellite image).


Identifying the ways vector data are displayed as points, lines, nodes and areas
....................................................................................

* A point feature is a map feature that has no length or area, such as a city on a world map or a building 
on a city map.

* A line feature, also known as an edge, is a map feature that has length but not area, such as a river on 
a world map or a contour on a topographic map.

* Nodes are the beginning or ending points of an edge or one of the three corners of a triangle as shown in 
the diagram below:

* Areas or polygons are features on a map that have a closed, two-dimensional shape defined by its boundary.

* A coordinated-based data model that represents points, lines and polygons is called vector data.

Linking remote sensing to raster data 
......................................

* Satellite and airborne sensors generally generate raster data, consisting of pixels. 

* Pixels are the smallest unit in which raster data is stored and make up a regular grid of cells that are 
referenced in rows and columns. If you keep zooming in to a digital image you would eventually only see squares
; these are pixels.

* Pixels can also be referred to as cell units.

* Raster data can also represent any phenomenon or value in its pixels. A very common and very useful application 
of raster data is in DEMs or Digital Elevation Models, in which each pixel represents elevation.


* In raster data the resolution is the pixel size of the data in the units of the distance they represent in the 
real world, e.g. ‘25cm’. 

DEM illustrating relief

.. image:: /static/training_manual/foreword/gis3.png
   :align: center

Capturing different types of data
--------------------------------------

Data capture

Data capture refers to any operation that converts GIS data into computer-readable form. There are two main types 
of data capture, primary and secondary data capture. Capturing data is the most time consuming, tedious and expensive 
part of a GIS project. Today crowd sourcing and community data capture are used to capture data quickly and cheaply. 
Rescue and response teams used community GPS tracks to help coordinate teams in the Haiti earthquake disaster.

* Preparation of data involves obtaining data, redrafting poor-quality map sources, editing scanned map images, 
removing noise, setting up appropriate GIS hardware and software systems to accept data. 

* Digitising and transfer are the stages where the majority of the effort will be expended when capturing data. 

* Editing captured data covers many techniques designed to validate data, as well as correct errors and improve quality.

Describing primary data capture 
......................................

* Primary data sources that are those collected in digital format specifically for use in a GIS project.

* The advantages of capturing raster data are consistency of the data, availability of systematic global 
coverage and regular repeat cycles (temporal resolution).  

* The disadvantage of capturing raster data resolution is often too coarse and many sensors are restricted 
by cloud cover.

* Vector data capture is mainly done by ground surveying and GPS (Global Positioning System).

.. image:: /static/training_manual/foreword/gis4.png
   :align: center 

Describing secondary data capture
......................................

* Secondary sources that are datasets that were originally captured for another purpose and need to be converted
into a suitable digital format for use in a GIS project.

* Secondary raster data capture involves using scanners to scan in maps, aerial photographs and images.

* Scanned in secondary data is then georeferenced so that it provides geographic context for other data.

* Documents are scanned to reduce wear and tear, improve access, provide integrated database storage, and 
to index them geographically.

* Secondary vector data capture involves digitizing vector objects from maps and other geographic data sources.
 
* Capturing attribute data: It be entered by direct data loggers, manual keyboard entry, optical character recognition
(OCR) or, increasingly, voice recognition.
 
* Much data is also generated as a result of analysis and geoprocessing of other primary and secondary data sources.

Identifying new trends in data capture
......................................

* Citizen-centric web-based data collection describes how a raft of new Web 2.0 technologies has enabled organisations 
and individual projects to use citizens to collect data across a wide variety of thematic and geographic areas For 
example, OpenStreetMap and Tracks4Africa.

* Social media such as Facebook, Twitter and other crowd-sourcing platforms can be used to capture data.

* Geo-tagging is a popular phenomenon. This involves capturing a position and applying it to photographs, tweets, 
news articles and other information.

* Sensors or probes automatically capture spatial data. For example cell phone companies provide live data of 
the positions of the cell phones on their network to navigation companies, so you can get live traffic information 
in your car GPS.


Data standardisation, data sharing and data security
----------------------------------------------------

* In the forty or so years since GIS started, different data formats and communication protocols have thrived. It 
used to be very difficult to share data because of this. Nowadays, any good GIS software can read and write multiple 
different formats. This means that data must be standardised. 

* It is very costly to capture and maintain high quality data. GIS practitioners would never get their work done if 
they had to capture all the data they need. Therefore it makes economic sense to share data.

* Data security is required, of course, to prevent vindictive changes or deletion of the data.

Key concepts

* Interoperability is a situation where diverse organisations and systems can share data and work together seamlessly
, now and into the future. An electrical plug from a foreign country that does not fit into a local socket is an example 
of two things that are not interoperable.

.. image:: /static/training_manual/foreword/gis5.png
   :align: center 

* Systems are interoperable if they can work easily together and can be shared.

* Metadata is 'data about data'.

* A metadata catalogue or clearinghouse is a standards-based way of publishing metadata about spatial data sets so that 
users can browse and search for data over a network. This helps data to be standardised, shared and secure.

Understanding why data should be standardised
..............................................

* The South African Government Minimum Interoperability Standards (MIOS) states that for spatial data, the 
standard is GML (Geography Markup Language). The specifications for GML are determined by the Open Geospatial 
Consortium, which is a global standards-generating body for the GIS industry. 

* Thus, to be interoperable with Government and for Government departments to be interoperable with each other 
(which is a requirement of the South African Constitution), whenever GIS vector data is exchanged it must be as GML.

Identifying how and why data is shared
.......................................
* For the various South African Government departments to work efficiently, departments need to share data. For example
, there isn't a department that doesn't need the demographic data generated by the Census.
 
* Statistics South Africa, which falls under the Minister of Finance, runs the Census and is the custodian of the Census 
data, yet all other departments and indeed the public, do share those data.

* To be able to share data successfully the data have to meet certain criteria.
 
They must be:
 * Listed somewhere so you can find them
 * In a location where you can fetch them.
 * well described so you can understand them.
 * in a format you can use.

* GIS data can be shared in a number of ways:
 * In a shared folder or directory if you're on the same network
 * In an Internet or 'cloud' location. 
 * Email is easy to use but is limited to relatively small files. 
 * Web services are the modern, standards-based way to obtain spatial data or map layers. 
 * Via a database connection. 
 * Via an API (application programming interface). 

* A map composed of data that comes from several sources is known as a mashup. 

Understanding the importance of data security    
----------------------------------------------

* Government data such as census data is freely available to the public. Access to these data sets does not therefore need 
to be protected by much security.
 
* Private companies might want to protect their data, in which case they need to implement security measures. How an 
organisation implements security depends on its requirements.

* Data security can also be implemented to various degrees. If there is a danger of data being changed, then high security 
and read-only access may be implemented.

Data manipulation
-----------------

To build up a GIS project, one of the first steps is to identify and acquire the data and map layers that you need. Once you 
have the data and map layers, the next step is to implement a number of processes to manipulate the data in a GIS in order to 
find solutions and model spatial problems.  

Key concepts

* Data integration, buffering, querying and statistical analysis are examples of how data can be manipulated.

* Data manipulation involves all the components of a GIS.

* Other data manipulation processes include:
  * simplifying or generalising data
  * adding or removing fields (attributes)
  * joining or merging data sets
  * editing geometry such as digitising or adding new features, moving features and changing features.

Describing data integration processes
.......................................

* Data integration means 'putting together' data and map layers.
 
* Some important considerations when integrating data include data format, data cleaning and quality control.

*Data layers need to be at the same projection and coordinate reference system CRS when integrated.
 
* A very important consideration for integrating spatial data sets and map layers is that they overlay correctly.

.. image:: /static/training_manual/foreword/gis6.png
   :align: center 
 
Describing what a buffering process is.
.......................................

* A buffer is a zone around a map feature measured in units of distance or time.

* A buffer zone will generate a new feature whose boundaries are a specified distance from the original feature's edge..

* A buffer is useful for proximity analysis (how close is a map feature to another feature).
 
* (Grade 12) In Settlement Geography a ‘sphere of influence’ could be seen as a type of buffer zone.

* Buffering a vector feature always results in a polygon. That polygon can then be use in cartography (as part of a map) 
or to perform queries.


The centre of Paarl showing roads with the Berg River buffered by 25m and various points of interest buffered by varying 
amounts determined by values of one of their attributes.

.. image:: /static/training_manual/foreword/gis7.png
   :align: center

Identifying how data can be queried.
.......................................

* Querying, or selecting, is a very powerful capability of GIS.

* Text searches on the Internet are a type of query.
 
* You can do the same type of query in a GIS. These are known as attribute queries and they give you the same power as working 
in a conventional spreadsheet or database.
  
* What makes GIS especially powerful is the ability to perform spatial queries, or queries based on location.

Attribute query. All roads with length less than 100m have been selected (orange in the table, yellow on the map)

.. image:: /static/training_manual/foreword/gis8.png
   :align: center

Understanding the uses of statistical analysis.
...............................................

* An attribute or field in a spatial data set is the same as a spreadsheet or database field. So, you can do the same types 
of statistics and use the same functions and operations in a GIS as in a spreadsheet or database.
 
* Examples of statistical analysis done on spatial data include distribution, classification, patterns and aggregation.

* A fundamental concept in geography is that 'the closer things are to each other, the more similar they are'. Various spatial 
statistics, such as interpolation, depend on this phenomenon.
 
* A heat map is an example of statistical analysis, see image xx illustrating population density.

* A statistic called spatial autocorrelation measures the degree to which things are similar in relation to their distance apart. 

* (For Grade 12s studying Advanced Program Mathematics) Spatial data geometry is two or three dimensional, unlike conventional 
attribute data which is one-dimensional. For example, you can't test the relationship between two variables (e.g. yield and 
nutrient concentration over a wheat field) using linear regression. 

Data manipulation exam practice questions:
(Grade 12)
Refer to the topographic map of Port Elizabeth 

* 1.	List three important considerations when integrating data in a GIS.		(6)

* 2.	What possible query would you apply to the spatial database in a GIS project looking at flooding of coastal areas in 
Port Elizabeth.			(4)

* 3.	Locate the Coega SDI on the map.
  * a) Describe how buffering can be used in a GIS project involving a study of the sphere of influence of Coega SDI.	(6)
  
  * b) Outline how an economic study of the SDI of Coega and the location of labour can use statistical analysis in a GIS. (6)








 



  










































 





    
 




















































 
  




















