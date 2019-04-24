# A collection of QGIS expression used in my daily task

- Create X, Y, lat ,long
```
$x , $y , $latitude, $longitude
```

- Extract value from points
```
raster_value('your_raster_data', 1, make_point($x, $y))
```
