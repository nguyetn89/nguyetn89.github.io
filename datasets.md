---
layout: default
title: Datasets
permalink: /datasets.html
weight: 3
---

There are two principal datasets employed in my PhD project on gait analysis:

## DIRO walking gaits

This dataset has been established to enable comparative studies on gait analysis, especially the problems of gait index estimation and abnormal gait detection.
The dataset includes 9 gaits that are normal (symmetric) walking gait and 8 simulated abnormal (asymmetric) ones.
Since the dataset contains 3 synchronized data types (point cloud, skeleton, frontal silhouette), this is appropriate for assessment on many gait-related methods.  
Description and the download links of this dataset are provided [here](http://www-labs.iro.umontreal.ca/~labimage/GaitDataset/).

## Gaits adapted from CMU and SFU databases

These datasets were created by adapting some mocap data sampled from [CMU](http://mocap.cs.cmu.edu/) and [SFU](http://mocap.cs.sfu.ca/) databases.
The mocap data provide a collection of 3D joints forming 3D skeletons having the same structure as Microsoft Kinect 2.
Besides, these mocap data were converted to point clouds by fitting a 3D model (created with [MakeHuman](http://www.makehumancommunity.org/)) and using the set of 3D vertices as the point clouds.
These Kinect skeletons and 3D point clouds are appropriate for researchers working on gait analysis with features extracted from  joint coordinates and/or point clouds.  
Description and the download links of these datasets are provided [here](http://www-labs.iro.umontreal.ca/~labimage/AdditionalGaitSets/).
