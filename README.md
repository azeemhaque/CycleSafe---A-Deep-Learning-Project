# CycleSafe-A-Deep-Learning-Project

Aim
The aim of this project was to use imagery to estimate safety on the roads of London, from a cyclist’s perspective. After a brief introduction to the most important road safety indicators, a ranked list with several risk factors was compiled. Risk factors were obtained from Google StreetView (GSV) imagery dataset using the object detection YOLOv5 (released in June 2020 by Glenn Jocher) and image segmentation PSPNet101 (Pyramid Scene Parsing Network) (released in July 2017 by Hengshuang Zhao et al.).

Imagery dataset contains 518 350 images of greater London, distributed across 4833 boroughs. Each image is labeled in accordance to the LSOA it belongs. Images are organized in sets of 4 which corresponds to 4 90º angles from a total of 129 588 points.

Both YOLOv5 and PSPNet101 were benchmarked and validated using a set of 1 image per LSOA from the dataset.

Data was storage and processed in the secure High Performance Cluster from Imperial College London.

GSV Dataset
Description
Along this project, it was used a Google StreetView imagery dataset from Greater London. It includes, approximately, 1/2 million images distributed across all LSOAs. For each data point there are 4 images ranging from 0º to 360º. These images were previously pre-processed (not as part of this project) to guarantee uniformity across them. More details are provided below.

Number of Images per LSOA in Greater London
Knowing the number of available images per LSOA allows us to normalize the objects counting in each area.
