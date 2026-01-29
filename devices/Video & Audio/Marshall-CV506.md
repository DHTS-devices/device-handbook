## WebLink
https://marshall-usa.com/discontinued/cameras/CV506.php#gsc.tab=0

----------------------------------------# Software Requirements / Device Advantages / Research Applications #-----------------------------------------------

### I. What kind of camera is this, and what is it used for?
The Marshall CV506 is a **professional-grade, fixed-position camera** designed for laboratory, medical, broadcast, and industrial environments.

Its primary purpose is not casual video recording, but to:
- Continuously and reliably output video from a **fixed viewpoint**
- Support **behavioral recording, motion analysis, procedural review, and algorithmic analysis** in research settings

In medical and health-related research, the CV506 is commonly used to:
- Record **participant behavior, posture, or task performance**
- Serve as a **visual reference aligned with wearable devices or physiological sensors**
- Support video-based analysis in rehabilitation, clinical tasks, or simulated procedures

> Key characteristic:  
> **The CV506 does not store data internally; it only outputs live video.**

---

### II. Subscription, Accounts, and Cloud Services
-  No subscription required  
-  No user account required  
-  No dependency on cloud platforms or vendor servers  

All video data:
- Is generated locally
- Is fully controlled and stored by the laboratory

 This is particularly important for **IRB compliance, privacy protection, and long-term studies**.

---

### III. Does this camera require software? (Short answer first)
**The camera itself does not require, and does not include, any recording or preview software.**

- The Marshall CV506 is a **pure hardware-output camera**
- It performs a single function:
 **Outputs live video via HDMI**
- Internally, the camera:
  - Does not record video
  - Does not generate files
  - Does not provide a graphical user interface (GUI)

Whether software is needed depends entirely on **whether the lab wants to view or record the video on a computer**.

---

### IV. Is there official software from the manufacturer? What is it used for?
**There is no official Marshall software for video preview or recording.**

Marshall does not provide:
- A Windows or macOS application for viewing live video
- An official “one-click recording” program for CV506

However, it is important to distinguish the following:

- Marshall has provided **camera control tools or control protocols** for some models
  - Purpose: adjusting camera parameters (e.g., exposure, white balance, menu settings)
  - Typically implemented via hardware control interfaces (e.g., RS-485)
- These tools:
  -  Do not record video
  -  Do not generate video files
  -  Are only used to configure camera settings

In most research workflows, camera parameters are configured during initial setup and **do not require frequent adjustment**.

---

### V. What are third-party software tools used for?
When the CV506 is connected to a **computer**, the typical signal path is:

- HDMI → capture card → computer  
- A computer will **not automatically display the video feed**

At this stage, **third-party software is required**. Its role is to:

- Display the live video feed on the computer
- Record video files (e.g., MP4, MOV)
- Configure:
  - Resolution
  - Frame rate
  - Encoding method
- Manage:
  - File naming
  - Storage location
  - Timestamps

**Common third-party options**
- OBS Studio (most common; free; cross-platform)
- FFmpeg (command-line; suitable for automation)
- Capture-card vendor software (basic functionality)

---

### VI. Is the video feed real-time?
**Yes. The video output is real-time.**

- The CV506 outputs a **live video signal**
- Latency depends on the connection pipeline:
  - Direct monitor connection: near-zero latency
  - Capture card + software: very small latency (typically milliseconds)
- The camera itself:
  - Does not buffer video
  - Does not introduce artificial delay

This level of latency is common and acceptable for **behavioral experiments, clinical observation, and synchronization with physiological signals**.

---

> **One-sentence summary**:  
> The Marshall CV506 is a professional camera that only delivers a stable live image;  
> **whether you view it, record it, or analyze it is entirely determined by the lab’s hardware and software workflow.**

--------------------------------------# Operational Workflow (First-Time Setup) #--------------------------------------------------------

The core logic of this device is simple:  
**the camera only outputs video; whether you view or record it is determined by external hardware and software.**

Below are step-by-step instructions for the three most common use cases.

---

### Scenario A: View Live Video Only (No Recording)
**Use case: Quickly verify the camera is working and check framing**

**Required equipment**
- Marshall CV506
- Power supply
- HDMI cable
- Monitor with HDMI input

**Steps**
1. Connect the camera to power.
2. Connect the camera to the monitor using an HDMI cable.
3. Turn on the monitor.
4. Once the camera is powered, the monitor should immediately display the **live video feed**.

**Result**
- Live video is displayed on the monitor
- No computer required
- No software required
- No video files are created

---

### Scenario B: View Live Video on a Computer (No Recording)
**Use case: Adjust framing, focus, and lighting without saving video**

**Required equipment**
- Marshall CV506
- HDMI cable
- Video capture card (HDMI → USB)
- Computer
- Third-party capture software (e.g., OBS)

**Steps**
1. Connect the camera to power.
2. Connect HDMI from the camera to the capture card.
3. Connect the capture card to the computer via USB.
4. Open the capture software (e.g., OBS).
5. In the software:
   - Add a video input source
   - Select the capture card as the input device
6. The **live video feed** should appear on the computer screen.

**Result**
- Live video can be viewed on the computer
- No recording is created unless recording is started

---

### Scenario C: Record Video on a Computer (Most Common Research Workflow)
**Use case: Experimental recording, behavioral observation, medical/health studies**

**Required equipment**
- Marshall CV506
- HDMI cable
- Video capture card
- Computer
- Third-party capture/recording software (OBS recommended)

**Steps**
1. Complete all connections described in Scenario B.
2. In the capture software, configure:
   - Resolution (e.g., 1920×1080)
   - Frame rate (e.g., 30 fps)
   - Output directory
   - File format (MP4 recommended)
3. Confirm the live video feed and framing are correct.
4. Click **Start Recording**.
5. At the end of the session, click **Stop Recording**.
6. Locate the saved video file in the specified output folder.

**Result**
- Video files are saved locally on the computer
- The camera itself does not store any data

---

### Quick Troubleshooting
- **No video signal**:
  - Check power supply
  - Check HDMI connections
  - Confirm the correct capture device is selected in software
- **Video lag or dropped frames**:
  - Lower resolution or frame rate
  - Check capture card performance and USB bandwidth
- **Cannot find recorded files**:
  - Verify the output directory set in the software

---

### Lab Best Practices
- Standardize on a single capture software (e.g., OBS) and fixed settings
- Pre-test and document:
  - Resolution
  - Frame rate
  - File naming conventions
- Adjust camera angle and focus **before** starting experiments to minimize mid-session changes

-----------------------------------------------------------------# Usage Notes (Device-Level) #------------------------------------------------------------------------------------

- **No on-device data storage**  
  The CV506 does not support local storage or on-device recording. All video capture and saving must be handled by external devices or software; the camera cannot record video by itself.

- **No built-in timestamp or system clock**  
  The camera does not generate or embed time information. Any timestamps associated with recorded video files are determined entirely by the recording device or software, not by the camera itself.

- **Shooting settings and conditions are not automatically recorded**  
  The CV506 does not store information such as resolution, frame rate, or camera position. These parameters must be manually documented by the experimenter as metadata during the recording process.

- **Not suitable for mobile or handheld use**  
  The camera is designed for fixed-position setups and is not intended for handheld recording or scenarios that require frequent repositioning.
