# A collection of QGIS expression used in my daily task

- Create X, Y, lat ,long
```
$x , $y , $latitude, $longitude
```

- Extract value from a point
```
raster_value('your_raster_data', 1, make_point($x, $y))
```

- Extract raster value by points from vector data
```
raster_value('your_raster_data',1,point_on_surface($geometry))
```

- Extract statistics from points
```
raster_statistic('your_raster_data',1,'avg') # min, max, avg, stdev, range, sum
```
