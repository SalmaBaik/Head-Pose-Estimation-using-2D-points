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
![gif](https://user-images.githubusercontent.com/50074808/224492361-f5db6efa-83ca-4266-b88c-0d975aaf5c5b.mp4)
