Landsat Satellite and Applications in QGIS  
===============================================================================

Landsat satellites are a joint collaboration between NASA and USSG. These satellites
orbit (circle) the earth continuously collecting images about aspects of the earth.
There are different Landsat satellites and some of them have been decommissioned and
are no longer operational but the most recent one is Landsat 8.

These satellites are equipped with a variety of remote sensing equipment which record radiation
from the surface of the earth in the different bands of the electromagnetic spectrum.

In order to understand the images that are produced there is a need to understand 
what each band is used to capture and how best to show the information. 



Brief Description of Landsat Satellite
------------------------------------------

Sensors record the amount of reflected radiation and they are able to represent these 
digitally as numbers. For each number it represents a characteristic feature on the ground.
Satellite images are composed of pixels which indicate the amount of reflected radiation from
an area. Each band of a Landsat image represent a measurement of reflected radiation that correspond
to that specific wavelength. Humans eyes are sensitive to the visible portion of the electromagnetic
spectrum so in order to visualise the other portions of the spectrum that our eyes can not detect we
combine these bands with Red,Green and Blue so as to have an understanding of the features that occur.


Understanding Landsat Bands
------------------------------------------

Landsat 8 collects 11 bands which measure reflected radiation from that waveleght.The following
are a brief description of what wavelength each band covers and what it is used to measure.
(svs.gsfc.nasa.gov, 2014)

.. image:: static/training_manual/remote_sensing/rs_bands.png
   :align: center

    
* Band 1  is primarily used to sense deep blues and violets. Blue portion is susceptible to 
  scattering and absorption. Band 1 has coastal/aerosol band which is primarily used for imaging
  shallow water and tracking fine particles like dust and smoke.

* Band 2 covers the visible blue

* Band 3 Covers green

* Band 4 Covers red

* Band 5 covers the Near Infra-red (NIR) which is used mainly in vegetation mapping. It allows for
  the distinction of the red edge which indicates healthy versus non health vegetation. Healthy
  plants reflect NIR and the water in the leaves scatter the wavelength back into the atmosphere.
  Using this band we are able to find define vegetation indexes for monitoring vegetation.

* Band 6 and Band 7 measure radiation from the SWIR which is useful for differentiating wet earth
  from dry earth. Geology,rocks and soils have a high contrast in this region.

* Band 8 is the panchromatic band and has the highest resolution of 15m.

* Band 9 is used to detect clouds mainly cirrus clouds

* Band 10 and 11 record radiation in the TIR. They are used for detecting the temperature of the 
  earth rather than measuring the temperature of the atmosphere.


Landsat Colour composites
-------------------------------------------------------------------------------
The following are the band combinations in Landsat 8

::

   Landsat Band Information:

   
    Composite              | Bands (RGB)          
    Colour Infra-red       | 543                 
    Natural colour         | 432               
    False colour           | 654              
    False colour           | 764               
    Colour Infra-red       | 753               
   



|basic| |FA| Adding Landsat Image into QGIS and doing basic Analysis
-------------------------------------------------------------------------------

* Start a new empty map in QGIS.
* Open the Browser by clicking the :guilabel:`Browser` tab at the bottom of the
  *Layer Panel*
* Open the Raster portion of the tree and you should navigate to the location where
  the satellite is archived.








