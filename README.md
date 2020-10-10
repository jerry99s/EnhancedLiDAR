# EnhancedLiDAR
Enhance LiDAR pointcloud based on stereo image.

## Flow diagram
![flow diagram](https://github.com/jerry99s/EnhancedLiDAR/blob/master/pic/flow_diagram.png)

## Result
### Ground remove
The following picture shows the ground remove results based on iterated RANSAC method we designed and normal RANSAC method.
![ground remove](https://github.com/jerry99s/EnhancedLiDAR/blob/master/pic/ground_remove.png)
The flow diagram of iterated RANSAC is shown below.<br/>
<div align=center>
<img src="https://github.com/jerry99s/EnhancedLiDAR/blob/master/pic/iterated_RANSAC.png" height = "550px">
</div>

### Enhanced LiDAR point cloud
The enhanced LiDAR point cloud with higher density is shown below. The blue points are generated by this method.

<div align=center>
<img src="https://github.com/jerry99s/EnhancedLiDAR/blob/master/pic/enhanced_pointcloud.png" height = "350px">
</div>


## Experiment on 3D object detection
1. Methods used: AVOD and AVOD-FPN
2. Results on val dataset:
![3D detection](https://github.com/jerry99s/EnhancedLiDAR/blob/master/pic/3D_detection.png)
3. PR curves</br>
<div align="center">
&emsp;&emsp;Car_3D &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Car_BEV

<img src="https://github.com/jerry99s/EnhancedLiDAR/blob/master/pic/AP_3D.png" height="280px" ><img src="https://github.com/jerry99s/EnhancedLiDAR/blob/master/pic/AP_BEV.png" height="280px" >
</div>

4. Checkpoints & log file</br>
Download link：https://pan.baidu.com/s/1QcXrRVM3rLc-rh0WbOpOFQ </br>
Key：5vq8
 