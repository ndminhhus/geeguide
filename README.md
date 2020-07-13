# [geeguide](/README.md)

# Harmonization of Landsat and Sentinel 2 in Google Earth Engine, documentation and scripts

The objective of this work is to document the technical part of my master thesis, named: "Harmonization of Landsat and Sentinel 2 for Crop Monitoring,  a complete stream processing in Google Earth Engine". A complete stream processing entirely in Google Earth Engine is developed to generate seamless surface reflectances of harmonized L7,L8 and Sentinel2.

To inspect the result of the hamonized dataset via NDVI time series and the cropland classification in Ninh Thuan, Vietnam please go to this [GEE App](https://ndminhhus.users.earthengine.app/view/cropninhthuan2019)

I am glad to announce that this work has been peer reviewed and now published on the Journal of Remote sensing: [Minh et al., 2020](https://doi.org/10.3390/rs12020281). We were also invited to speak about this work at the 6 th International Conference on Satellite & Space Missions on July 15-16, 2020 in London, UK. [More information](https://satellite.insightconferences.com) 

I will put here many scripts that I have used, either collected from various sources or the ones I developed myself.  Citation is considered seriously. The remote sensing content also will be discussed. 

The scripts are organized not in order of increasing complexity but according to the processing workflow. Also, the scripts can be used separately or in combination depending on user-specific applications. Each session has five parts including Objective, General Instruction, Core Script, Visualisation Checking, and References

Some experiences with GEE are needed. General introduction about GEE and how to use it can be found in many other places.

Table of Contents
Part 1: Preprocessing and Data analysis.
1. [Filtering Image Collection](01.Filtering-Image-Collection.md)
2. [Atmospheric correction](02.Atm-correction.md)
3. [Cloud masking](03.cloudmaskTOA.md)
3A. [Cloud masking improved](https://medium.com/eelab/improve-cloud-detection-and-removal-with-machine-learning-in-google-earth-engine-ac0a2f759022)
4. [Shadow masking](03.cloudmaskTOA.md)
5. [Topographic correction](04.topo_correction.md)
6. [BRDF correction](04.topo_correction.md)
7. [Reprojection and resampling](07.reprojection.md)
8. [Image registration](08.image_registration.md)
9. [Band adjustment](09.band_adjustment.md)
10. [Composite time series](10.time_series.md) 
11. Exporting data
12. Crop mapping with spectral signature & temporal signature

![fig3](https://user-images.githubusercontent.com/40456844/65582427-9ee74580-dfa7-11e9-9eae-0dd0a3cdc6bb.jpg)
![timeseries](https://user-images.githubusercontent.com/40456844/61792616-76af5f00-ae1d-11e9-8c08-2a43613724eb.png)

