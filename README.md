# Tropical-storm-damage-detection
The goal of the challenge is to develop a machine learning model to identify and detect “damaged” and “un-damaged” coastal infrastructure (residential and commercial buildings), which have been impacted by natural calamities such as hurricanes, cyclones, etc.
given pre- and post-cyclone satellite images of a site impacted by Hurricane Maria in 2017 and build a machine learning model, designed to detect four different objects in a satellite image of a cyclone impacted area:

·      Undamaged residential building

·      Damaged residential building

·      Undamaged commercial building

·      Damaged commercial building

Dataset Used:

Mandatory dataset:

·      High-resolution panchromatic satellite images before and after a tropical cyclone: Maxar GeoEye-1 (optical)

Optional datasets:

·      Moderate-resolution satellite data: Sentinel-2 (optical), Landsat (optical)

Data Description
Mandatory dataset:

Participants are given pre- and post-cyclone satellite images of a specific area in the US territory of Puerto Rico, affected by Hurricane Maria in 2017. Participants can find the data set here:

·      Pre-Event Image – The image prior to the event was secured by the Maxar GeoEye-1 (optical) satellite on [29th Aug’17] and it's accessible here.

·      Post-Event Image – The image after the event was obtained by the Maxar GeoEye-1 (optical) satellite on [12th Oct’17] and it's available here.

Optional datasets:

Although Maxar GeoEye-1 high resolution images are good enough to build the machine learning model, but participants may also leverage moderate-resolution satellite dataset like Landsat, Sentinel-2 etc for building the solution. These datasets can be accessed from Microsoft Planetary Computers Catalog.

In addition to satellite data, participants are provided with building footprint data over the region of interest. This data can be used to filter the large analysis region to find areas where there is a mix of residential and commercial buildings.

Sample Model Notebook

A sample Jupyter notebook (sample model) with an initial mAP (Mean Average Precision) score of 0.34 is provided for the participants to get started and can be found here.

Supplementary Notebooks

Participants are provided with Supplementary Notebooks explaining the extraction of Sentinel-2 and Landsat data from Microsoft Planetary Computer catalog and can be found here.

Tips and Tricks

This video will guide you through a range of useful tips and strategies that can boost your performance and land you a top spot on the leader board.

https://challenge.ey.com/
