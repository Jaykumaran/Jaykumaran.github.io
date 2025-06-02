ROS Object Tracking package : [Link](https://github.com/Jaykumaran/Robotics/tree/main/ros_tracking_package)

A ROS2 Package (sim_cam_pkg) which implements object detection and tracking system. It starts with a simulated camera feed from a video file, performs object detection using YOLO11n , then object tracking across frames with OpenCV Kalman filter and finally a visualization node to display results using rqt_image_viewer.

Additionally, to simulate continuous camera feed with a single video file, a simple loop detection logic is included and everytime when the video loops, the tracker IDs are reset back.

<img src="/assets/images/project_assets/ros_tracking_demo.gif" alt="ROS Tracking Demo">
