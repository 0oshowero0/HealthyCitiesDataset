# Street View Features

We collect street view images through [Google Map](https://www.google.com/maps) and use [CityScapes](https://www.cityscapes-dataset.com/dataset-overview/) pretained state-of-the-art semantic segmentation model [ViT-Adapter](https://github.com/czczup/vit-adapter) to extract the pixel-level classification of the street view image as the community pattern.

Specifically, we collect the street view images in 100m x 100m grid, where 360 degree images are used to represent the grid points. Then we use the pretrained model to inference these images and calculate the percentage of each categores in the image, and aggregate them in MSOA or city level.