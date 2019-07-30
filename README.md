# [geeguide](/README.md)

# Harmonization of Landsat and Sentinel 2 in Google Earth Engine, documentation and scripts

The objective of this work is to document the technical part of my master thesis, named: "Harmonization of Landsat and Sentinel 2 for Crop Monitoring,  a complete stream processing in Google Earth Engine". A complete stream processing entirely in Google Earth Engine is developed to generate seamless surface reflectances of harmonized L7,L8 and Sentinel2.

I will put here many scripts that I have used, either collected from various sources or the ones I developed myself.  Citation is considered seriously. The remote sensing content also will be discussed. 

The scripts are organized not in order of increasing complexity but according to the processing workflow. Also, each script or group of scripts will be described or demonstrated in the way that it can stand independently and can be reused easily for your own purpose. Each session has five parts including Objective, General Instruction, Core Script, Visualisation Checking, and References

Some experiences with GEE are needed. General introduction about GEE and how to use it can be found in many other places.

Table of Contents
1. [Filtering Image Collection](01.Filtering-Image-Collection.md)
2. [Atmospheric correction](02.Atm-correction.md)
3. [Cloud masking](03.cloudmaskTOA.md)
4. [Shadow masking](03.cloudmaskTOA.md)
5. [Topographic correction](04.topo_correction.md)
6. [BRDF correction](04.topo_correction.md)
7. [Reprojection and resampling](07.reprojection.md)
8. [Image registration](08.image_registration.md)
9. [Band adjustment](09.band_adjustment.md)
10. [yearly,monthly,seasonal and dekdal (10 days) time series](10.time_series.md) 
11. Crop mapping 
12. Exporting data


![timeseries](https://user-images.githubusercontent.com/40456844/61792616-76af5f00-ae1d-11e9-8c08-2a43613724eb.png)
