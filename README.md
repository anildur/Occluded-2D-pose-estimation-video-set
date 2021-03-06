# Occluded-2D-pose-estimation-video-set
Human pose estimation is an important task in image and video processing. One problem in pose estimation is the identification and position estimation of occluded human joints or keypoints. This repository is used to develop a Bayesian approach for occluded keypoint estimation, BAKE [1], to estimate the occluded keypoints in a video sequence.
Please cite this paper in your publications if it helps your research:

This repository includes mainly three video sequences with single person acting. Artificial occlusion patterns are added to occlude the upper body, lower body and mid-body of the acting person with black boxes in different severity levels. 2D Ground truth body annotations are given in text files for each sequence. Body annotations are in Openpose's 25 keypoint body format. 

```
@inproceedings{bake,
  author = {A.A. Dursun, T.E. Tuncer},
  title = {Estimation of Partially Occluded 2D Human Joints with a Bayesian Approach},
  booktitle={submitted to Digital Signal Processing},
  year = {2021}
}
```
