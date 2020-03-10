# Gait Analysis

This project uses OpenPose to capture the gait information from a video stream. PyCharm provide some useful tools to make development easier.

1. Make sure Python 3 is installed
2. Open the project folder and run `pip3 install -r requirements.txt`
3. Try running `poseDetectVideo.py` or `poseTrailVideo.py`
4. The UI thread is blocked while the pose detection is performed. This should be improved and the data from the pose detection should be captured for machine learning.

![caleb_gait](https://github.com/weeksseth/gait_analysis/blob/master/results/caleb_gait.png)
