---
# _projects/ros-object-tracking.md

title: "ROS Object Tracking Package"
excerpt: "A ROS2 package for object detection (YOLOv10) and tracking (OpenCV Kalman filter)." # Short description for the card

image: /assets/images/project_assets/ros_tracking_demo.gif # Teaser image for the card. Ensure this path is correct and starts with /
# Consider using a static JPG/PNG for the card teaser if this GIF is large or long, for better page load on the projects list.

github_url: "https://github.com/Jaykumaran/Robotics/tree/main/ros_tracking_package" # Plain URL string here
# live_demo_url: "URL_TO_LIVE_DEMO_IF_ANY" # Uncomment and add URL if you have one

technologies:
  - ROS2
  - Python
  - YOLOv10  # Consistent with excerpt. Please verify if you used v10 or another version.
  - OpenCV
  - Kalman Filter
status: "Completed"
date: 2023-05-26 # Changed to a past date, adjust if needed. Or remove if you don't sort by date.

# --- Standard Jekyll/Minimal Mistakes front matter (often set by defaults in _config.yml) ---
# layout: single # This will likely be set by your defaults in _config.yml for the 'projects' collection
# author_profile: true # Also likely set by defaults
---

## Project Details: ROS Object Tracking

This ROS2 Package (sim_cam_pkg) implements a robust object detection and tracking system. It initiates with a simulated camera feed from a video file, performs object detection utilizing **YOLOv10** (please verify version, was YOLO11 in your original text below), then tracks objects across frames using an OpenCV Kalman filter. Finally, a visualization node displays the results via `rqt_image_viewer`.

To simulate a continuous camera feed from a single video file, a simple loop detection logic is incorporated. Each time the video loops, the tracker IDs are reset to ensure distinct tracking for each pass.

### Demonstration
<img src="/assets/images/project_assets/ros_tracking_demo.gif" alt="ROS Tracking Demo Full" style="width:100%; max-width:700px; margin: auto; display: block;">
<!-- The path for the image here looks correct if it's in your repo -->

### Key Features:
*   **Object Detection:** Utilizes **YOLOv10** (please verify version) for accurate detection.
*   **Object Tracking:** Employs OpenCV's Kalman filter for smooth tracking.
*   **Simulated Environment:** Works with video files as a simulated camera source.
*   **Continuous Loop Simulation:** Handles video looping and tracker ID resets.
*   **Visualization:** Integrates with `rqt_image_viewer`.

---
**[View on GitHub »]({{ page.github_url }})**
<!-- This Liquid tag will correctly use the github_url from the front matter -->
