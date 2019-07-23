------------------------------------------------------------------------------------------------
# Objective:
Filtering image collection based on: 
- Time of interest
- Area of interest
- Metadata (cloud cover, path, row, etc.)

#Core script
```
var start = '2018-01-01';
var end   = '2018-12-31';
var L8_col = ee.ImageCollection('LANDSAT/LC08/C01/T1_TOA')
                .filterBounds(geometry)
                .filterDate(start,end)
                .filter(ee.Filter.eq('WRS_PATH',124))
                .filter(ee.Filter.eq('WRS_ROW',51))
                .filter(ee.Filter.lt('CLOUD_COVER',95))
                .sort('CLOUD_COVER') //first image will be the less cloudy image in the collection

```
------------------------------------------------------------------------------------------------
#Visualization and Checking
```
print(L8_col.size(),'L8_col size')  //.size() is the number of images
print(L8_col.first(),'first image') //first image will be the less cloudy image
```
