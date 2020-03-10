# Gait Analysis

This project uses OpenPose to capture the gait information from a video stream. PyCharm provide some useful tools to make development easier.

1. Make sure Python 3 is installed
2. Download `caffemodel` from [link to caffemodel](https://github.com/foss-for-synopsys-dwc-arc-processors/synopsys-caffe-models/blob/master/caffe_models/openpose/caffe_model/pose_iter_440000.caffemodel?raw=true "here") and place in models folder
3. Open the project folder and run `pip3 install -r requirements.txt`
4. Try running `poseDetectVideo.py` or `poseTrailVideo.py`
5. The UI thread is blocked while the pose detection is performed. This should be improved and the data from the pose detection should be captured for machine learning.

![caleb_gait](https://github.com/weeksseth/gait_analysis/blob/master/results/caleb_gait.png)
