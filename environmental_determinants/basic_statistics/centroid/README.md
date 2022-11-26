# Centroid Data

The population weighted centroid data for MSOA is collected from [ONS Geography](https://geoportal.statistics.gov.uk/datasets/ons::middle-layer-super-output-areas-december-2011-population-weighted-centroids/about).

The geographical centroid data is obtained by calculating the geographical centroid of city or MSOA boundary using Python packet __shapely__.

The coordinate is in WGS84.

An example of reading the centroid file in Python is as follows:

```python
import geopandas as gpd
from shapely.geometry import Point, Polygon
boundary = gpd.read_file('./population_weighted_centroid_msoa.geojson', driver='geojson')
print(boundary.iloc[0,-1])  
```