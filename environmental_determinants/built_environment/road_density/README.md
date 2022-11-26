# Road Density Data

This data is collected from [OpenStreetMap](https://www.openstreetmap.org/), through which we collect the regional dataset through [Geofabrik](https://download.geofabrik.de/europe/great-britain/england.html).

We mannually determine the OpenStreetMap regions that contain selected cities, then using Python packet __pyrosm__ to filter and extract the road network information.

Specifically, we extract driving road, cycling road and walking road in each MSOA or city, then calculate the total road length in these regions. We provide the total road length / area as the building density indicator. Here the unit of road length and area are km and km2, respectively.