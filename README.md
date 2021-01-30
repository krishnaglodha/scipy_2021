# Workshop Submission : *Introduction to GIS and Geospatial analysis with Python*
 
### Contributors :
1. Krishna Lodha
2. Aman Tiwari
----
 
## Short Description
This tutorial is an introduction to Geospatial Domain and its analysis using python. Since almost all industries are more or less connected to Location and mapping, it is important to spread awareness and literate developers to understand different aspects of the GIS (Geographic Information System) industry. The first Part of this series focuses on different GIS Data types and how to read them, This includes understanding different data formats such as Shapefiles, GeoJSON, WKT, CSV, TIFF, GeoTIFF, etc. . Users can actually read such files on their computers and be familiar with them. The second part of this series focuses on geospatial analysis with python. Users will first practice working with some core GIS functionalities using GDAL and OGR on the terminal (and later in python). After this, users will be familiarised with the most widely used geospatial python libraries such as pandas, geopandas, fiona, shapely, matplotlib, PySAL, rasterio .

Complete Series is divided into the following subtopics :
1. Introduction to GIS, GIS Data formats
2. Introduction and Installation of all Geospatial libraries in computer and in python environment
3. Working with GDAL and OGR capabilities
4. Spatial Operations and Relationships
5. Vector data analysis and visualization
6. Raster Data analysis and visualization
7. Working with Interactive Map in a python notebook
 
----
## Long Description
 
This tutorial will be helpful to every python developer looking forward to work in a niche field, applications and business logics are getting complex everyday and with huge chunks of data flowing in everyday, geospatial analysis using python will allow developers to automate things pretty easily using spatial techniques
This series will be a brief introduction to the domain as well as advancement of domain in python. Users will learn various libraries such as `pandas, geopandas, fiona, shapely, matplotlib, PySAL, rasterio`.
 
<b>No Previous knowledge on GIS or geospatial field is required, little hands on approach on basic python would be better to have but not compulsion </b>
 
The series will cover the following topics, each of them can either be re-created on Jupyter notebook or in a python file as well, the data used in the workshop will be freely available to download and use.

## 1. Introduction to GIS, GIS Data formats
Before getting our hands dirty by writing python code, we'll go through a brief introduction of the subject matter. It is very important to have a working knowledge of the field so that you can build the logic (and thus, code) easily. We'll see some history, applications, use cases of GIS along with data formats that are used widely by most of the GIS applications

## 2. Setting up the Environment
Attendees will need to download some installable software beforehand, links to which will be provided priorly along with a how-to-do video. Apart from this, attendees can create an env using the environment.yml file provided in the repository.

## 3. Working with GDAL and OGR capabilities
Here, we start coding, but still not in python! We'll spend some time getting comfortable with using the command-line / terminal to perform some basic GIS operations. This section will be a huge time saver for developers in the future where they want to perform some quick actions on data, such as converting data to different formats, changing Coordinate Systems, Getting information about data, etc.

## 4. Spatial Operation and Relations
The real application of GIS is to enable users to perform queries or establish relations between different data sets based on location information. In this section, we'll have an overview of different geospatial operations like :
1. Buffer, Overlaps
2. Contains, Within, Touches
The point in Polygon, Intersection, Crosses Once attendees understand the logic behind these operations in theory, we'll jump in the python
## 5. Vector data analysis and visualization
Vector data is like normal data (JSON, CSV, XML, etc) coupled with location information. In this series, attendees will see how spatial analysis operations can be performed on such data using various libraries like geopandas,shapely,pySAL, and many more. We can see the data not only in just tabular format but also in pictures by visualizing this vector data on a map. This topic will cover how to visualize the data with advanced options as well.

## 6. Raster data analysis and visualization
This is a very important skill to have as most raster files are huge in size. To perform some basic operations such as getting pixel values, fetching metadata, conversion of files libraries like GDAL, Rasterio, Georaster are used.

## 7. Interactive map visualization in python
Attendees will be able to create Interactive maps with additional data, the ability to pan, etc. inside the notebook directly, this skill comes in handy when you want to test your geospatial results directly in python.

 
---
 
In the above outline, both theoretical and hands-on exercises will be covered to make attendees aware of the domain and make them familiarize with the existing libraries for GIS in python.
Attendees will get complete gitHub repo of all notebooks, slides and data used during training.
 
---
## Setup
Softwares, Libraries, Data used throughout the tutorial are available for all major operating systems. Attendees can use :
* Linux (Ubuntu x64)
* Windows 10 (x64)
* Mac OS X (x64)
 
Softwares to be used :
* pyCharm (Optional)
* GDAL/OGR (https://gdal.org/download.html)
* Anaconda Env (Optional) (https://www.anaconda.com/products/individual)
 
Libraries to be used :
* geopandas
* pySal
* rasterio
* georasters
* matplotlib
* shapely
* fiona
