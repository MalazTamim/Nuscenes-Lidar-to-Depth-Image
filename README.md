# Nuscenes-Lidar-to-Depth-Image
This repository contains the code for transforming lidar point cloud provided by nuscenes dataset to depth images. Some part of the code are borrowed from [nuscenes-devkit](https://github.com/nutonomy/nuscenes-devkit).



Examples of the output depth images:


Camera image (for reference):

 ![Metrics](images/Image_015-2018-07-24-11-22-45+0800__CAM_BACK_LEFT__1532402930147423.jpg) 
 
RGB depth image of lidar projected on left back camera:
 ![Metrics](images/RGB_015-2018-07-24-11-22-45+0800__CAM_BACK_LEFT__1532402930147423.jpg)
 
Grayscale depth image of lidar projected on left back camera:
 ![Metrics](images/Grayscale_015-2018-07-24-11-22-45+0800__CAM_BACK_LEFT__1532402930147423.jpg)
 
Note: nuscenes/python_sdk folder is the [nuscenes-devkit](https://github.com/nutonomy/nuscenes-devkit) with some extra functions to transform the Lidar point cloud to depth image.
