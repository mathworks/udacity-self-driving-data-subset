# Udacity Self-Driving Car Data Subset
This repository contains a subset of data from the [Udacity Self-Driving Car dataset](https://github.com/udacity/self-driving-car/tree/master/datasets) used in Automated Driving Toolbox examples provided by MathWorks.

The data is saved in MAT-files and represents approximately 100 seconds of lidar, GPS, and IMU readings. These MAT-files can be loaded into the MATLAB workspace using the [`load`](https://www.mathworks.com/help/matlab/ref/load.html) function. Each MAT-file contains a [`timetable`](https://www.mathworks.com/help/matlab/ref/timetable.html), with a row representing readings recorded at a single time. 

* __lidarPointClouds.mat__: Each row contains a [`pointCloud`](https://www.mathworks.com/help/vision/ref/pointcloud.html) corresponding to the lidar scan.
* __gpsSequence.mat__: Each row contains a latitude, longitude and altitude reading.
* __imuOrientations.mat__: Each row contains the IMU orientation specified as a 4-by-1 numeric vector describing a quaternion.

