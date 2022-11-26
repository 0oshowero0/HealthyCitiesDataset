# Boundary Data

The city boundary data is collected from [ONS Geography: Major Towns and Cities](https://geoportal.statistics.gov.uk/datasets/ons::major-towns-and-cities-december-2015-boundaries-v2/about), and MSOA boundary is collected from [ONS Geography: MSOA Boundaries](https://geoportal.statistics.gov.uk/datasets/ons::middle-layer-super-output-areas-december-2011-boundaries-generalised-clipped-bgc-ew-v3/about). They are the offical defination of city and MSOA boundaries, which contain the area size information.

The coordinate is in WGS84.

An example of reading this boundary file in Python is as follows:

```python
import geopandas as gpd
from shapely.geometry import Point, Polygon
boundary = gpd.read_file('./boundary_city.geojson', driver='geojson')
print(boundary.iloc[0,-1].contains(Point(-1.9030677,52.4803097)))   # the city is Birmingham, and the location is Birmingham Museum & Art Gallery
```