Developing a Paper GIS using QGIS
==================================

Mining in Thabazimbi
--------------------

Thabazimbi mine produces primarily high-grade haematite ore (more than 62% iron content).
Current mining activities take place in three pits, using conventional opencast methods.

Start QGIS

Note: screenshots in these notes are from QGIS 2.2 running on Ubuntu Linux. This exercise 
will work on any recent version of QGIS (preferable 2 or greater) on any operating system. 
Some of the icons and other parts of the screen look different on different systems, but 
they all work the same.

GIS work is managed in projects. A project file stores information about the layers you are 
working on, their styles, your work location and other factors.
 
GIS projects normally use large data files. It is faster to work with these files on your 
computer's hard drive rather than on a DVD. If you haven't copied the contents of the DVD onto 
your computer then do so now. Your Desktop is a good place. 

Open the thabazimbi.qgs project. In QGIS, either click on the yellow folder icon in the toolbar 
or use the menu and go to Project->Open.


.. image:: /static/training_manual/paper_gis/qgis1.png
   :align: center 

QGIS will load several layers and zoom into the Thabazimbi area.


.. image:: /static/training_manual/paper_gis/qgis2.png
   :align: center

The layers are listed in the layer panel on the left.
 
The layers with ticks or crosses in them are 'on' and you can see them in the map.
 
Layers draw in the same order they appear. The aerial photographs draw first and the rivers 
draw last so they appear on top.

Exercise
We have all the layers needed for the exercise, plus some extras.

Relief
We have already selected the 1200m contour lines and all those above it. These are drawn in brown. 

Mining layer
Mine excavations and slimes dams are drawn in red. These outlines come from the 1:50000 topographical map data. 
For interest: How do the mines and slimes dams in the mines layer compare to what you can see in the aerial 
photographs?

Problem statement
Imagine Anglo American wished to open another opencast mining operation in the area. Use the layers available, 
find the best location(s) for this new mine. Indicate the new mine on the “mining layer” in black. Note the 
following environmental restrictions.

* Assume that iron ore is only found above 1 200 m. 

* The new mine may not be visible from the town of Thabazimbi.
 
* The new mine may not be within 500m of a stream.
 
* The new mine may not be located in a nature reserve.
 
* The new mine has to be within 3 km of a railway line to be economically viable to transport the iron ore.

Note: a GIS consultant would be able to give Anglo American a number of possible locations in a few minutes 
by automating the following steps in a computerised GIS.

GIS steps
One way to find all areas that are not within 500m of a river is to BUFFER the rivers by 500m

Menu: Vector->Geoprocessing tools->Buffer

Complete the Buffer dialog as follows. Choose a folder and name for your output shapefile.
 
Note: a shapefile is a type of GIS data file. A buffer is a new data set and will be written to a new 
shapefile on your hard drive.


.. image:: /static/training_manual/paper_gis/qgis3.png
   :align: center

The new buffer layer will load into QGIS. Slide it down below the river layer and you will see something 
like this:


.. image:: /static/training_manual/paper_gis/qgis4.png
   :align: center

Now do the same process with the railway lines. We will create a 3km (3000m) buffer.


.. image:: /static/training_manual/paper_gis/qgis5.png
   :align: center

You should see something like this when you draw the railway line above the railway buffer:


.. image:: /static/training_manual/paper_gis/qgis6.png
   :align: center

Now we want to find all areas that are WITHIN the railway buffer and NOT WITHIN the river buffer.

In other words, we want to find the DIFFERENCE between the railway and river buffers. This is one of several 
possible GIS OVERLAY operations. 

Menu: Vector->Geoprocessing tools->Difference


.. image:: /static/training_manual/paper_gis/qgis7.png
   :align: center

You should get something like this:


.. image:: /static/training_manual/paper_gis/qgis8.png
   :align: center

With some more complicated steps we can use the GIS to find areas above 1200m AND out of sight of Thabazimbi. 

But if we turn the contours on we visually estimate these areas:


.. image:: /static/training_manual/paper_gis/qgis9.png
   :align: center















