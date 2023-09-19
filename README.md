# ArUco-Pose-Estimation

# Drone Pose Estimation from ArUco Marker

## Overview

This project focuses on the precise pose estimation of a drone using ArUco markers in conjunction with an overhead camera. The primary objective is to accurately determine both the position and orientation of the drone in a controlled environment. This capability is crucial for applications in robotics and autonomous systems, where spatial awareness is fundamental.

## Features

- **Overhead Camera**: An overhead camera serves as the primary sensor, capturing images of the arena in which the drone operates. These images are the basis for the subsequent pose estimation process.

- **Camera Calibration**: To ensure accurate pose estimation, camera calibration is performed to obtain the intrinsic parameters of the camera. Calibration is a critical step that corrects for lens distortion and other optical properties.

- **Frame of Reference Conversion**: Converting the frame of reference from the camera's view to a global or world frame is an essential step in the pose estimation process. This transformation allows us to relate the detected markers to real-world coordinates accurately.

- **Marker Detection**: We leverage the power of OpenCV libraries for marker detection within the captured images. ArUco markers are known for their ease of detection and are widely used in computer vision tasks.

- **Pose Estimation**: Once the markers are detected, the project employs pose estimation techniques to precisely determine the drone's position and orientation in 3D space. This information is vital for the drone's navigation and control.

- **Localization**: Achieving accurate localization of the drone within the arena is a significant milestone of this project. This localization data contributes to the drone's autonomous navigation and enhances its ability to operate safely in dynamic environments.

## Contribution

This project represents a valuable contribution to the broader context of robotics and autonomous systems. The work undertaken here was part of the Inter IIT Tech Meet project, which aimed to develop a reliable and accurate system for drone pose estimation. The successful implementation of this technology has wide-ranging applications, from autonomous drones to surveillance systems and more.

## Dependencies

- Python
- OpenCV
