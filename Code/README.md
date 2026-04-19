# Code Documentation
This folder contains Python programs developed for Team CyberBots’s WRO 2026 Future Engineers project, specifically designed to implement the robot’s autonomous navigation system, vision processing algorithms, and movement control logic.

## 🤖Autonomous Navigation Software Architecture(Open Challenge)

The CyberBots robot uses a vision-based autonomous navigation system implemented in Python using the OpenCV library and executed on a Raspberry Pi 5 computing platform. The algorithm enables real-time environment perception and adaptive steering control without external infrastructure.

The navigation logic is based on continuous camera frame analysis divided into three independent Regions of Interest (ROI):

left region (left boundary detection)
right region (right boundary detection)
center region (forward obstacle detection)

Each region is processed separately using grayscale thresholding to estimate the presence of walls or free space relative to the robot’s position inside the track.

To improve stability and reduce noise influence from camera input, an exponential smoothing filter is applied to the detected wall signals:

This filtering method prevents sudden steering oscillations and ensures smoother trajectory correction during motion.

Steering control is implemented using proportional error-based correction between left and right boundary detection signals. The difference between detected wall intensities determines the steering angle adjustment applied to the servo motor:

This allows continuous real-time trajectory alignment while maintaining forward motion stability.

Additionally, adaptive brightness compensation is implemented inside the forward detection region. When high illumination conditions are detected, the obstacle detection sensitivity is automatically adjusted to maintain reliable perception accuracy under varying lighting conditions during competition runs.

When the algorithm detects sufficient open space in front of the robot, a controlled turning procedure is activated. During this maneuver, the robot monitors frame-to-frame grayscale changes to determine when environmental motion stabilizes. This visual stabilization logic prevents premature steering reset and ensures accurate completion of the turning sequence.

The integration of region-based perception, signal smoothing, proportional steering correction, and adaptive brightness handling results in a reliable and computationally efficient autonomous navigation system optimized for the WRO Future Engineers competition environment.
