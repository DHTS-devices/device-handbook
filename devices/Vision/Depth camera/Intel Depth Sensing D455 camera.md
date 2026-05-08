# Intel RealSense Depth Camera D455

---

# 1. Overview

- Device name:
  Intel RealSense Depth Camera D455

- Device type:
  RGB-D Depth Camera / Stereo Depth Camera / Spatial Vision Camera

- Category:
  Vision

- Manufacturer:
  [Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)

- Overview:
  The Intel RealSense D455 is a stereo depth camera designed for:
  - robotics
  - computer vision
  - depth sensing
  - 3D perception
  - spatial mapping
  - SLAM
  - object detection
  - human tracking
  - autonomous systems

  Unlike a normal webcam that captures only RGB images, the D455 captures:
  - RGB video
  - infrared stereo images
  - depth maps
  - IMU motion data

  simultaneously.

  The D455 belongs to Intel’s D400 series and is considered one of the longer-range and more accurate stereo depth cameras in the RealSense lineup. ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:0]{index=0}

  One of the major improvements of the D455 compared to earlier models like the D435 is the larger 95 mm stereo baseline between depth sensors. This significantly improves depth accuracy at longer distances. Intel states the D455 achieves depth error below 2% at 4 meters

  The camera uses:
  - active infrared stereo depth sensing
  - global shutter sensors
  - onboard vision processing
  - integrated IMU

  making it suitable for:
  - robotics
  - drones
  - autonomous navigation
  - obstacle avoidance
  - 3D scanning
  - indoor mapping

  The D455 is widely used in:
  - ROS robotics environments
  - NVIDIA Jetson projects
  - SLAM research
  - AI perception systems
  - academic robotics labs
  - industrial automation

- Primary use cases:
  - Robotics navigation
  - Depth perception
  - SLAM
  - Obstacle avoidance
  - 3D reconstruction
  - Human tracking
  - Object detection
  - Spatial AI systems

- Best for:
  - Robotics developers
  - AI vision systems
  - ROS workflows
  - Long-range stereo depth sensing
  - Autonomous systems
  - Spatial computing

- Official website:
  [Intel RealSense D455 Official Page](https://www.intelrealsense.com/depth-camera-d455/?utm_source=chatgpt.com)

- SDK:
  [Intel RealSense SDK 2.0 GitHub](https://github.com/IntelRealSense/librealsense?utm_source=chatgpt.com)

- Documentation:
  [Intel D455 Specifications](https://www.intel.com/content/www/us/en/products/sku/205847/intel-realsense-depth-camera-d455/specifications.html?utm_source=chatgpt.com)

---

# 2. License / Account / Subscription

- Is an account required?
  No

- Is a subscription required?
  No

- What features are available without subscription?
  - Depth sensing
  - RGB streaming
  - IMU streaming
  - SDK access
  - ROS integration
  - Depth recording
  - Point cloud generation

- What features require subscription?
  None

- Notes:
  The D455 works entirely locally and does not require cloud services.

  Most workflows are built around:
  - local processing
  - ROS
  - Python
  - C++
  - OpenCV
  - NVIDIA Jetson systems

---

# 3. Classification

- Category_L1:
  Vision

- Category_L2:
  Stereo_Depth_Camera

---

# 4. Hardware Information

- Depth technology:
  Active infrared stereo depth sensing ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:5]{index=5}

- Stereo baseline:
  95 mm ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:6]{index=6}

- RGB sensor:
  Global shutter RGB camera ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:7]{index=7}

- RGB resolution:
  Up to 1280 × 800 ([Intel Specs](https://www.intel.com/content/www/us/en/products/sku/205847/intel-realsense-depth-camera-d455/specifications.html)) :contentReference[oaicite:8]{index=8}

- Depth resolution:
  Up to 1280 × 720 ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:9]{index=9}

- Maximum depth frame rate:
  Up to 90 FPS ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:10]{index=10}

- Depth field of view:
  87° × 58° ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:11]{index=11}

- RGB field of view:
  90° × 65° ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:12]{index=12}

- Minimum depth distance:
  Approximately 52 cm ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:13]{index=13}

- Recommended operating range:
  Approximately 0.6 m to 6 m ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:14]{index=14}

- IMU:
  Bosch BMI055 IMU ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:15]{index=15}

- Connectivity:
  USB-C USB 3.1 Gen 1 ([Intel Specs](https://www.intel.com/content/www/us/en/products/sku/205847/intel-realsense-depth-camera-d455/specifications.html)) :contentReference[oaicite:16]{index=16}

- Dimensions:
  124 mm × 26 mm × 29 mm ([Intel Specs](https://www.intel.com/content/www/us/en/products/sku/205847/intel-realsense-depth-camera-d455/specifications.html)) :contentReference[oaicite:17]{index=17}

- Mounting:
  - tripod mount
  - M4 mounting points ([Intel RealSense](https://www.intelrealsense.com/depth-camera-d455/)) :contentReference[oaicite:18]{index=18}

- Hardware notes:
  The D455 is NOT a standalone device.

  It must remain connected to:
  - PC
  - Jetson
  - embedded computer
  - robotics platform

  during operation.

  Unlike LiDAR systems, the D455 uses stereo infrared depth estimation, meaning:
  - texture
  - lighting
  - reflective surfaces
  - sunlight

  can influence depth quality.

---

# 5. Main Features

- Stereo depth sensing
- RGB + depth synchronization
- IMU integration
- Point cloud generation
- Real-time depth streaming
- Global shutter imaging
- ROS support
- SDK support
- Multi-camera synchronization
- OpenCV integration
- SLAM compatibility

- Feature notes:
  One of the biggest strengths of the D455 is long-range stereo depth performance.

  Compared to earlier D435 models:
  - improved depth accuracy
  - larger stereo baseline
  - better outdoor performance
  - improved RGB-depth alignment

  are major improvements. :contentReference[oaicite:19]{index=19}

- Important practical note:
  Stereo depth cameras work differently from LiDAR.

  Common limitations include:
  - reflective surfaces
  - transparent surfaces
  - bright sunlight
  - low-texture scenes
  - dark environments

  These conditions can reduce depth accuracy.

---

# 6. Exportable Data

## 6.1 Data Types

Available data includes:
- RGB frames
- Depth maps
- Infrared frames
- Point clouds
- IMU data
- Timestamp streams
- Skeleton tracking inputs
- SLAM input streams

---

## 6.2 Time Granularity

- Real-time streaming
- Frame-by-frame capture
- Continuous recording

---

## 6.3 Data Availability

- Available during active streaming
- Exportable through SDK

---

## 6.4 Data Format

Possible formats:
- ROS bag
- PNG
- JPG
- CSV
- PLY point cloud
- depth matrices
- NumPy arrays

- Notes:
  The RealSense SDK allows exporting:
  - synchronized streams
  - aligned depth maps
  - point cloud data
  - IMU telemetry

---

# 7. Setup & Workflow

## 7.1 Requirements

Required:
- D455 camera
- USB 3.x connection
- Computer or embedded device

Recommended:
- NVIDIA GPU
- SSD storage
- ROS environment
- Python or C++ development setup

Optional:
- Tripod
- Jetson device
- robot platform
- external power for embedded systems

---

# 7.2 First-Time Setup

1. Connect D455 through USB 3.x
2. Install RealSense SDK
3. Install camera drivers
4. Open RealSense Viewer
5. Verify RGB stream
6. Verify depth stream
7. Verify IMU stream
8. Test point cloud generation

- Notes:
  USB 2.0 may severely reduce:
  - bandwidth
  - frame rate
  - resolution

---

# 7.3 RealSense Viewer Workflow

The RealSense Viewer is the primary debugging tool.

Workflow:
1. Open Viewer
2. Select D455
3. Enable:
   - RGB
   - depth
   - IR
4. Adjust presets
5. Verify depth quality
6. Test alignment

Useful for:
- debugging
- calibration
- testing FPS
- checking exposure
- validating USB performance

---

# 7.4 Depth Streaming Workflow

Typical workflow:
1. Start SDK pipeline
2. Enable RGB + depth
3. Capture synchronized frames
4. Align depth to RGB
5. Process depth maps
6. Export or analyze results

Common outputs:
- obstacle distance
- segmentation
- point clouds
- AI input

---

# 7.5 ROS Workflow

The D455 is extremely common in ROS robotics systems.

Typical ROS workflow:
1. Install RealSense ROS package
2. Launch camera node
3. Publish:
   - RGB topics
   - depth topics
   - point cloud topics
   - IMU topics
4. Subscribe from SLAM or navigation stack

Common robotics applications:
- autonomous navigation
- obstacle avoidance
- robot localization
- manipulation

---

# 7.6 SLAM Workflow

Typical SLAM workflow:
1. Enable IMU + depth
2. Feed synchronized data into SLAM system
3. Generate:
   - map
   - localization
   - pose estimation

Common frameworks:
- RTAB-Map
- ORB-SLAM
- ROS SLAM systems

- Important practical note:
  IMU calibration and synchronization matter heavily for stable SLAM performance.

---

# 7.7 Multi-Camera Workflow

Multiple D455 cameras can be used together.

Typical uses:
- volumetric capture
- room scanning
- full-body tracking
- occlusion reduction

Important considerations:
- USB bandwidth
- synchronization
- interference
- CPU/GPU load

Intel notes multi-camera support is available. :contentReference[oaicite:20]{index=20}

---

# 7.8 Outdoor Usage Notes

The D455 performs better outdoors than earlier RealSense models because of:
- improved stereo baseline
- global shutter RGB sensor

However, strong sunlight still affects infrared stereo systems.

Best practices:
- avoid direct harsh sunlight
- increase texture in scene
- test IR exposure carefully

---

# 8. Data Export

## 8.1 Point Cloud Export

Typical workflow:
1. Capture depth frames
2. Generate point cloud
3. Export:
   - PLY
   - OBJ
   - point cloud stream

Common use cases:
- room reconstruction
- robotics
- object scanning
- obstacle mapping

---

## 8.2 ROS Bag Recording

Workflow:
1. Start ROS nodes
2. Record bag file
3. Save synchronized streams
4. Replay later for debugging

Useful for:
- SLAM testing
- robotics debugging
- AI dataset generation

---

## 8.3 Recommended Folder Structure

```text
realsense_projects/
│
├── rgb/
├── depth/
├── pointclouds/
├── rosbags/
└── calibration/
```

Example naming:

```text
2026-05-08_lab_mapping_test01.bag
```

---

# 9. Additional Software / Environment

Recommended software:
- RealSense SDK 2.0
- ROS / ROS2
- OpenCV
- Python
- C++
- RViz
- RTAB-Map

Recommended hardware:
- NVIDIA Jetson
- Linux robotics systems
- GPU-enabled workstation

- Software notes:
  The RealSense SDK supports:
  - Windows
  - Linux
  - macOS
  - Android

  and includes wrappers for:
  - Python
  - C++
  - Unity
  - ROS

  according to Intel documentation. :contentReference[oaicite:21]{index=21}

---

# 10. Battery & Maintenance

- Battery:
  No internal battery

- Power source:
  USB powered

- Maintenance recommendations:
  - Keep lenses clean
  - Avoid scratches
  - Protect USB-C connector
  - Avoid cable strain
  - Recalibrate if needed

- Important practical note:
  Fingerprints or dust on the infrared sensors can significantly reduce depth quality.

---

# 11. Troubleshooting

## No Depth Data

Possible causes:
- USB bandwidth issue
- SDK mismatch
- sensor blocked

Possible solutions:
- use USB 3.x
- update firmware
- reconnect camera
- clean sensors

---

## Poor Depth Accuracy

Possible causes:
- reflective surfaces
- strong sunlight
- low-texture scene
- bad calibration

Possible solutions:
- improve scene texture
- reduce sunlight
- recalibrate camera

---

## Frame Drops

Possible causes:
- insufficient USB bandwidth
- CPU overload
- multiple cameras

Possible solutions:
- reduce resolution
- lower FPS
- use dedicated USB controller

---

## SLAM Instability

Possible causes:
- poor IMU synchronization
- rapid motion
- feature-poor environment

Possible solutions:
- recalibrate IMU
- improve lighting
- reduce motion blur

---

## Multi-Camera Interference

Possible causes:
- overlapping infrared projectors
- synchronization issues

Possible solutions:
- adjust camera angles
- reduce overlap
- synchronize carefully

---

# 12. Notes

- The D455 is one of the most widely used RGB-D cameras in robotics and computer vision research.

- Compared to webcams:
  - provides depth
  - spatial perception
  - point clouds
  - IMU data

- Compared to LiDAR:
  - cheaper
  - denser close-range depth
  - more compact
  - more affected by lighting conditions

- Compared to earlier D435:
  - longer range
  - improved depth accuracy
  - larger baseline
  - improved RGB-depth alignment

- Research comparing RGB-D cameras found the D455 performs especially well at longer distances compared to D435, while D435 may still perform better in close tabletop scenarios. :contentReference[oaicite:22]{index=22}

- Common beginner mistakes:
  - using USB 2.0
  - ignoring calibration
  - expecting LiDAR-like outdoor performance
  - misunderstanding reflective surface limitations

- Practical advice:
  The D455 works best when:
  - lighting is controlled
  - scenes contain texture
  - USB bandwidth is stable
  - synchronization is configured correctly
  - depth is validated visually before deployment

- The D455 is especially strong for:
  - robotics
  - SLAM
  - autonomous navigation
  - AI perception
  - 3D mapping
  - computer vision research
  - embedded spatial AI systems
```
::contentReference[oaicite:23]{index=23}
