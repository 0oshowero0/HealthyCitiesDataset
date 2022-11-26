# Building Density Data

This data is collected from [OpenStreetMap](https://www.openstreetmap.org/), through which we collect the regional dataset through [Geofabrik](https://download.geofabrik.de/europe/great-britain/england.html).

We mannually determine the OpenStreetMap regions that contain selected cities, then using Python packet __pyrosm__ to filter and extract the building information.

We calculate the number of buildings in each MSOA or city, and provide the #buildings / area as the building density indicator. Here the unit of area is km2.