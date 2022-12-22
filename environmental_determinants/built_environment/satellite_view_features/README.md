# Satellite View Features

We collect satellite view images through [Esri World Imagery](https://www.arcgis.com/home/item.html?id=10df2279f9684e4a9f6a7f08febac2a9%2F) and use [LoveDA](https://github.com/Junjue-Wang/LoveDA) pretained state-of-the-art semantic segmentation model [ViT-Adapter](https://github.com/czczup/vit-adapter) to extract the pixel-level classification of the satellite view image as the community pattern.

Specifically, we collect the satellite view images in 0.6m resolution. Then we use the pretrained model to inference these images and calculate the percentage of each categores in the image, and aggregate them in MSOA or city level.