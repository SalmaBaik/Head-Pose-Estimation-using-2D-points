# Head-Pose-Estimation-using-2D-points
## Project sections:
1. Problem definition.
2. Dataset.
3. Tools.
4. Output.
----
## Problem Definition
Given a video, the model needs to extract face features from it and use its 2D points extracted from the facemesh to predict the yaw, pitch, and roll to plot the x,y,z axes on the nose depending on the face angle.

## Dataset
Worked on ___AFLW2000-3D___ and excluded the third dimension.<br/>
Dataset can be downloaded through this [link](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip "Named link title").

## Tools
* numpy
* pandas
* scipy
* openCV
* mediapipe

##Output<br/>
![gif](https://user-images.githubusercontent.com/50074808/224492547-d9cbabc2-35f1-4ab5-81e3-23f91c50feef.mp4)
