# Azure Kinect DK

## link:https://azure.microsoft.com/en-us/products/kinect-dk

## Device Overview

- **Device Name**: Microsoft Azure Kinect Developer Kit  
- **Device Category**: Vision / Depth Sensor (Spatial Vision & Depth Sensing)  
- **Positioning**: An external spatial sensing device combining RGB-D and IMU, designed for human motion capture, 3D scene understanding, and behavioral research.

---

## Hardware

| Hardware |  | Description |
|----|----|----|
| USB 3.0 / 3.1 Interface |  | Direct connection to computer |
| Power Adapter |  | Azure Kinect DK requires independent power supply |
| Tripod / Fixed Mount |  | Used to stabilize camera angle and distance |
| Sync Cable (Multi-device) |  | For synchronized capture with multiple Azure Kinect units |

---

## Software

| Software |  | Description |
|----|----|----|
| Azure Kinect Sensor SDK |  | Device drivers and core data acquisition |
| Azure Kinect Viewer |  | Quick inspection of device status and video streams |
| Azure Kinect Recorder |  | Recording raw data in `.mkv` format |
|----|----|----|
| Azure Kinect Body Tracking SDK |  | Real-time / offline human skeleton tracking |
| Python / C++ SDK |  | Custom data processing and analysis |
| Unity Plugin |  | 3D, XR, and interactive applications |

---

## Data Outputs

- RGB color images  
- Depth images  
- Infrared (IR) images  
- Point clouds  
- IMU data (accelerometer, gyroscope)  
- Human skeleton data (3D joints, optional)

---

## Common Data Formats (Depending on Acquisition Method)

- `.mkv` (official Recorder format)  
- `.png / .jpg` (frame-by-frame export)  
- `.ply / .pcd` (point clouds)  
- `.csv / .json` (IMU / skeleton data)

---

## Usage Notes (Common Research Pitfalls)

- Avoid direct sunlight (can interfere with IR and depth sensing)
- Depth accuracy is distance-sensitive; fixed capture distance is recommended
- Insufficient USB bandwidth may cause frame drops
- For multimodal studies, record accurate timestamps for alignment with wearable data

---

## Setup Guide

This section describes the minimal workflow from connecting the device to starting data acquisition.

---

## 1. Hardware Setup

1. Place the **Azure Kinect DK** on a stable surface or tripod  
   - Maintain fixed height and angle  
   - Ensure the capture area is unobstructed  

2. Connect the power supply  
   - Use the original power adapter  
   - **The device cannot operate on USB power alone**

3. Connect the device directly to the computer using a **USB 3.0 / 3.1 cable**  
   - Avoid low-quality USB hubs  
   - Prefer native motherboard USB ports  

4. Turn on the rear power switch  
   - Power indicator light confirms successful power-up

---

## 2. Software Installation

### 2.1 Required Software

Install the following in order:

1. **Azure Kinect Sensor SDK**  
   - Provides device drivers and core acquisition functionality

2. **Azure Kinect Viewer**  
   - Used to verify correct device operation

3. **Azure Kinect Recorder**  
   - Used to record raw sensor data (`.mkv`)

> Viewer and Recorder are typically bundled with the Sensor SDK installation.

---

## II. Creative & Realtime Tools

### Common Integrations

- **TouchDesigner**  
  - Real-time RGB, depth, point cloud, and skeleton data  
  - Interactive installations, visual art, and behavior-driven visualization

- **Unity**  
  - Official and community-supported plugins  
  - 3D scenes, interaction prototypes, and XR applications

- **Unreal Engine**  
  - High-quality real-time rendering  
  - Stage production, immersive displays, virtual production

- **openFrameworks**  
  - C++ creative coding framework  
  - Commonly used for point cloud and depth-based installations

---

## III. Research & Data Analysis Tools

### Programming & Analysis

- **Python (via SDK bindings / wrappers)**  
  - Data parsing, feature extraction, ML pipelines  
  - Alignment with wearables, surveys, and time-series data

- **C++**  
  - Native SDK support  
  - High-performance real-time and offline processing

### 3D / Point Cloud Tools

- **Open3D**  
  - Point cloud processing, visualization, and registration

- **MeshLab**  
  - Point cloud and mesh inspection and cleanup

- **Blender**  
  - 3D scenes and animation  
  - Visualization and post-processing

---

## 3. Device Verification

1. Launch **Azure Kinect Viewer**  
2. Verify that the following streams are displayed correctly:
   - Color (RGB)
   - Depth
   - IR
3. If streams update in real time without significant frame drops:
   - The device, drivers, and USB connection are functioning properly

**Common Troubleshooting:**
- No image: verify USB 3.x connection
- Severe frame drops: replace USB cable or port
- Viewer fails to launch: confirm SDK installation

---

## 4. Recording Data

1. Open **Azure Kinect Recorder**  
2. Configure capture parameters (examples):
   - Color resolution  
   - Depth mode  
   - Frame rate  
3. Start recording to generate a `.mkv` file  
4. Playback using:
   - Recorder Playback  
   - Or Azure Kinect Viewer  

Before each recording session, it is recommended to document:
- Capture distance  
- Lighting conditions  
- Participant ID  
- Acquisition configuration parameters

---

## 5. Skeleton Tracking (Optional: Body Tracking)

If human skeleton data is required:

1. Install **Azure Kinect Body Tracking SDK**
2. Use official samples or custom programs to perform:
   - Real-time skeleton tracking  
   - Offline processing of `.mkv` files  
3. Export:
   - 3D joint coordinates  
   - Confidence values  
   - Timestamps

---

