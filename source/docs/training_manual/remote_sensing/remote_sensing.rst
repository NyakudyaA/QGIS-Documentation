Definition of  Remote sensing
================================================= 


Remote sensing is the science of acquiring information without being in
contact with it. Our eyes are very good examples of it. The satellite images
that are produced by remote sensing techniques are called raster data.
A raster represents geographic features by dividing the world into rectangular
cells laid out on a grid. Each cell has a value that represents a particular 
characteristics of that location.


Introduction to remote sensing
-------------------------------------------------------------------------------

The primary source of remote sensing is the sun. The energy that is produced
by the sun is called electromagnetic radiation. This energy is reflected as it passes
through the atmosphere, the energy that reaches the earth is absorbed and another process
of reflection occurs and as the reflected energy passes through the atmosphere is is 
absorbed for a second time and when it reaches the sensor it is then processed.

There are mainly two types of remote sensing that is mainly Active and Passive remote
sensing.

* Passive remote sensing detects radiation that is produced by the sun, the sensors detect
  radiation that is produced by the sun and reflected by the earth. examples
  of such system include film photography
* Active remote sensing emits radiation that is used to scan objects and a sensor then 
  records the energy that is reflected or backscattered from the objects. Example of such a
  system is RADAR remote sensing.


.. image:: /static/training_manual/remote_sensing/rs_overview.png
   :align: center

Remote sensing workflow
-------------------------------------------------------------------------------


Remote sensing is best explained by the diagrammatic representation below and the main steps
that are involved in remote sensing are mainly:

.. image:: /static/training_manual/remote_sensing/rs_principles.png
   :align: center

* First requirement for remote sensing is to have the energy source which is usually the sun
  for passive remote sensing and for active remote sensing the sensor produces its own energy
  (A).

* The second process is the interaction of radiation (energy from the sun) by the atmosphere 
   (B).

* Interaction of radiation (energy from the sun) by elements on the surface of the earth (C).

* Recording energy by the sensor(D).

* Transmission, reception and processing (E).

* Interpretation and Analysis (F).

* Application (G)

Energy Source
---------------
The sun produces the energy and this energy is called electromagnetic radiation. It is fundamental
to understand the EMS in order to have a firm grip on the concepts of remote sensing as it forms 
the core principle of Remote sensing. Two fundamental principles of electromagnetic radiation are the frequency
and wavelength.

Short wavelength results in high frequency and high wavelength results in lower frequency.

.. image:: /static/training_manual/remote_sensing/rs_em.png
   :align: center

The electromagnetic radiation describes the entire range of light including those not visible to our eyes.
The electromagnetic radiation which is visible to our eyes is called the visible spectrum.

.. image:: /static/training_manual/remote_sensing/rs_vis.png
   :align: center

Some portions of the electromagnetic spectrum does not allow us to carry out remote sensing and thus it is
important to know which parts of the spectrum we can carry out remote sensing in order to aid us in design
of our sensors. The Ultraviolet portion allows us to carry out remote sensing and the blue portion of the
visible spectrum is usually ignored for remote sensing as it is very much susceptible to scattering and 
absorption by the atmosphere.

Interaction with the Atmosphere
----------------------------------

The energy that is produced by the sun interacts with the atmosphere before it reaches the surface of the 
earth by either absorption or scattering. The main cause of this interaction is gas particles in the atmosphere,
dust particles,ozone and carbon dioxide in the atmosphere.

Interaction of energy with the target
--------------------------------------

Energy that is not absorbed or scattered makes it's way to the earth and start to interact with the target.
Depending on the type of target some of the energy is absorbed,transmitted through the target and  some is 
reflected back to the atmosphere where a second interaction with the atmosphere occurs before finally 
reaching the sensor. Various factors affect how the energy interact with the target. The main factors which
affect how the target interacts with the radiation are: type of surface,type of wavelength.

Example Interaction of radiation with Leaves
.................................................

.. image:: /static/training_manual/remote_sensing/rs_tree1.png
   :align: center

All trees have a chemical compound that is called chlorophyll and this is mainly responsible for the colour
changes in leaves during the dry and wet season. Chlorophyll interact with radiation in a different way depending
on the season and type of radiation. The chlorophyll absorbs radiation in the blue and red and reflect radiation
in the green portion and that contributes to the green colour of leaves during the wet season.
During the summer season when chlorophyll is at it's lowest in leaves and this causes more reflection of the 
red and less absorption and this causes the leaves to appear brown to reddish.

.. image:: /static/training_manual/remote_sensing/rs_tree.png
   :align: center

Spectral Response Curves
............................

Target materials have have got different response patterns over a range of wavelength and by plotting these
reflectance values for objects over different wavelength we can identify what type of feature it is and compare
them.

Spectral Response curve of vegetation.

.. image:: /static/training_manual/remote_sensing/rs_sp.png
   :align: center  

Comparison of different spectral response patterns of target material.

.. image:: /static/training_manual/remote_sensing/rs_sp1.png
   :align: center

Image Analysis
-----------------

How much detail one can see on a satellite image depends primarily on the spatial resolution of the sensor that
was used to acquire the image.Spatial Resolution describes the ability of a sensor to identify the smallest possible
feature. A satellite with a courser spatial resolution does not allow one to clearly distinguish the features as they
usually are blurred.

.. image:: /static/training_manual/remote_sensing/rs_reso1.png
   :align: center

A finer spatial resolution has features that are clearly visible.

.. image:: /static/training_manual/remote_sensing/rs_reso.png
   :align: center

In order to help analyse the satellite imagery there are basic elements of visual interpretation that can be 
utilised in order to describe what kind of feature it is.The elements which help in visual interpretation are:tone,size,texture,pattern,shape,shadow and association.

Shape : Man made features have distinct shapes which natural features tend to have irregular shapes. Sharp and straight
edges typically reference man made features.

Shadow: Gives an indication of an object's height.

Pattern: It is the spatial arrangements of objects in the landscape.   







