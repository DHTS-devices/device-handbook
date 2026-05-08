# Varjo XR-3

---

# 1. Overview

- Device name:
  Varjo XR-3

- Device type:
  Professional Mixed Reality Headset / High-Resolution XR Headset / PC XR Headset

- Category:
  XR / VR / AR

- Manufacturer:
  Varjo

- Overview:
  The Varjo XR-3 is a professional mixed reality headset designed for high-end simulation, training, research, design visualization, medical simulation, engineering review, and enterprise XR development.

  Unlike consumer headsets such as Meta Quest or VIVE XR Elite, the XR-3 is mainly designed for professional PC-based workflows. It is not a casual standalone headset. It requires a powerful workstation, Varjo Base software, headset adapters, DisplayPort connections, USB connections, and tracking setup.

  The XR-3 combines:
  - high-resolution VR display
  - video passthrough mixed reality
  - LiDAR depth sensing
  - eye tracking
  - hand tracking
  - SteamVR tracking
  - Varjo Base software

  into one professional XR system.

  The headset is especially known for its very high visual clarity. Varjo describes the XR-3 as having over 70 pixels per degree in the focus area, 115° field of view, dual 12 MP video passthrough cameras, LiDAR-based depth awareness, and 200 Hz eye tracking.

  The XR-3 has been discontinued and replaced by newer Varjo XR-4 models, but it is still an important professional XR headset in many labs and enterprise environments.

- Primary use cases:
  - Mixed reality simulation
  - Professional VR training
  - Medical simulation
  - Flight / driving / vehicle simulation
  - Industrial design review
  - CAD visualization
  - Human factors research
  - Eye tracking studies
  - Unity / Unreal XR development
  - High-fidelity passthrough experiments

- Best for:
  - Professional XR labs
  - Enterprise simulation
  - Research environments
  - High-resolution VR visualization
  - Mixed reality prototyping
  - Eye tracking experiments
  - Applications where visual clarity matters

- Official website:
  https://varjo.com/products/varjo-xr-3/

- Setup guide:
  https://support.varjo.com/hc/en-us/setting-up-xr-3-vr-3

- User guides:
  https://support.varjo.com/hc/en-us/pdf-user-guides-xr-3-vr-3-and-varjo-aero

---

# 2. Important Notes Before Use

- The Varjo XR-3 is NOT a standalone headset.

- It requires:
  - powerful Windows PC
  - Varjo Base software
  - DisplayPort connections
  - USB 3.0 connections
  - headset adapters
  - tracking system

- The XR-3 is mainly for professional / enterprise use.

- It is heavier and more complex than consumer XR headsets.

- It may require a valid Varjo account and subscription depending on the license and institutional setup.

- Before using the headset, always check:
  - workstation GPU
  - Varjo Base status
  - headset connection
  - base station tracking
  - headset firmware
  - eye tracking calibration
  - room safety

---

# 3. License / Account / Subscription

- Is an account required?
  Usually yes for setup through Varjo Account Portal.

- Is a subscription required?
  Depending on institutional license and headset activation.

- What features are available locally?
  - VR display
  - mixed reality passthrough
  - eye tracking
  - hand tracking
  - SteamVR / OpenXR workflows
  - Unity / Unreal development

- What may require account / license access?
  - Varjo Base download
  - headset activation
  - enterprise features
  - support tools
  - software updates

- Notes:
  Varjo’s setup documentation instructs users to log into Varjo Account Portal and download Varjo Base from the account portal.

---

# 4. Classification

- Category_L1:
  XR_VR_AR

- Category_L2:
  Professional_Mixed_Reality_Headset

---

# 5. Hardware Information

- Display system:
  Varjo Bionic Display system

- Focus display:
  High-resolution focus area

- Peripheral display:
  Wider peripheral display area

- Field of view:
  Approximately 115° horizontal field of view

- Refresh rate:
  90 Hz

- Eye tracking:
  200 Hz integrated eye tracking

- Passthrough:
  Dual 12 MP low-latency video passthrough cameras

- Depth sensing:
  LiDAR + RGB fusion

- Depth operating range:
  Approximately 40 cm to 5 m

- Hand tracking:
  Ultraleap hand tracking

- Positional tracking:
  SteamVR Tracking 1.0 or 2.0

- IPD:
  Automatic interpupillary distance adjustment

- PC connections:
  - 2 × DisplayPort
  - 2 × USB-A 3.0 or higher

- Headset connection:
  Uses Varjo headset adapters

- Weight:
  Approximately 594 g headset plus headband system

- Hardware notes:
  The XR-3 uses a PC-based architecture. The headset itself is not running apps like a Quest headset.

  Most graphics rendering happens on the connected workstation GPU.

  The headset also uses external tracking, usually SteamVR base stations, for accurate 6DoF tracking.

---

# 6. What Comes in the Box

Depending on kit and institutional purchase, the package may include:

- Varjo XR-3 headset
- headset adapters
- USB-C headset cables
- power adapters
- cleaning cloth
- face cushions
- user guide

Often required separately:
- SteamVR base stations
- controllers
- compatible PC workstation
- DisplayPort cables / adapters
- mounted tracking setup

---

# 7. What Makes XR-3 Different

Consumer headset workflow:

```text
Headset
↓
Standalone app
↓
Inside-out tracking
```

Varjo XR-3 workflow:

```text
High-end PC
↓
Varjo Base
↓
DisplayPort + USB
↓
SteamVR tracking
↓
Professional XR application
```

The biggest difference is that the XR-3 is designed for:

```text
visual fidelity + professional simulation + mixed reality accuracy
```

rather than:

```text
casual VR gaming
```

---

# 8. Computer Requirements

Typical requirements include:

- Operating system:
  Windows 10 64-bit or compatible Windows workstation

- CPU:
  High-end multi-core processor

- RAM:
  32 GB recommended

- GPU:
  High-end NVIDIA GPU recommended

Examples often associated with XR-3 workflows:
- NVIDIA RTX 3080
- NVIDIA RTX 3070
- NVIDIA RTX 2080 Ti
- NVIDIA RTX A6000
- NVIDIA RTX 6000

- Video output:
  2 × DisplayPort 1.4

- USB:
  2 × USB-A 3.0 / 3.1

- Storage:
  SSD recommended

- Practical note:
  Weak GPUs can cause:
  - low frame rate
  - unstable rendering
  - poor mixed reality performance
  - nausea
  - dropped frames

---

# 9. Required Software

Required:
- Varjo Base

Usually needed:
- SteamVR
- OpenXR runtime
- NVIDIA GPU driver

For development:
- Unity
- Unreal Engine
- Varjo SDK / OpenXR support
- SteamVR plugin if needed

Optional:
- Varjo Lab Tools
- Varjo examples
- eye tracking data tools
- research data logging scripts

---

# 10. STEP-BY-STEP First Setup

---

# STEP 1 — Prepare The Computer

Before connecting the headset:

1. Confirm computer has compatible GPU
2. Confirm 2 DisplayPort outputs are available
3. Confirm 2 USB 3.0 ports are available
4. Update NVIDIA GPU driver
5. Restart computer
6. Make sure Windows is updated

---

# STEP 2 — Create / Confirm Varjo Account

1. Go to Varjo Account Portal
2. Log in with institutional account
3. Confirm headset license or access
4. Download Varjo Base

---

# STEP 3 — Install Varjo Base

1. Run Varjo Base installer
2. Follow installation prompts
3. Allow drivers to install
4. Restart computer if required
5. Launch Varjo Base

---

# STEP 4 — Connect Headset Adapters

The XR-3 usually uses headset adapter boxes.

Connect:

```text
PC DisplayPort → Varjo Adapter
PC USB 3.0 → Varjo Adapter
Power → Varjo Adapter
Adapter → Headset Cable
```

Important:
- use the correct DisplayPort ports
- avoid weak USB hubs
- connect directly to the workstation
- do not mix up adapter cables

---

# STEP 5 — Connect The Headset

1. Connect headset cables to the adapters
2. Make sure all cable connectors are fully seated
3. Confirm adapters have power
4. Open Varjo Base
5. Check device status

If connected correctly, Varjo Base should show the headset as detected.

---

# STEP 6 — Set Up Tracking

The XR-3 normally uses SteamVR tracking.

1. Mount base stations in opposite corners
2. Place them above head height
3. Angle them downward toward play area
4. Power on base stations
5. Open SteamVR
6. Confirm base stations are detected
7. Confirm headset tracking is active

Good base station placement is extremely important.

Bad placement causes:
- tracking loss
- jitter
- headset drift
- unstable controllers

---

# STEP 7 — Run Room Setup

Inside SteamVR:

1. Choose standing or room-scale setup
2. Define floor height
3. Define safe play area
4. Confirm boundary
5. Test tracking by moving headset slowly

---

# STEP 8 — Put On The Headset

1. Loosen head strap
2. Place headset on face
3. Tighten rear adjustment
4. Adjust top strap
5. Make sure headset weight is balanced
6. Confirm image is clear

Do not overtighten.

A poor fit can cause:
- blurry image
- discomfort
- poor eye tracking
- light leakage
- eye strain

---

# STEP 9 — Run Eye Tracking Calibration

Inside Varjo Base:

1. Start eye tracking calibration
2. Follow calibration target
3. Keep head still
4. Move only eyes when instructed
5. Finish calibration
6. Verify gaze tracking quality

Eye tracking calibration is important for:
- foveated rendering
- gaze data collection
- research experiments
- accurate interaction

---

# STEP 10 — Test Mixed Reality Passthrough

Inside Varjo Base or MR demo:

1. Enable video passthrough
2. Look around the room
3. Check image clarity
4. Test occlusion if available
5. Verify lighting conditions

Mixed reality quality depends heavily on:
- room lighting
- camera exposure
- object distance
- calibration
- depth sensing

---

# 11. Understanding Display Quality

The XR-3 uses a special display design:

```text
high-resolution focus area
+
wide peripheral display
```

This means the center of vision is extremely sharp.

This is useful for:
- reading cockpit text
- viewing CAD details
- inspecting dashboards
- simulation training
- medical visualization

Practical note:
The sharpest area is not the entire display. The center focus area is highest resolution, while the peripheral area provides wider field of view.

---

# 12. Understanding Mixed Reality Passthrough

The XR-3 uses video passthrough.

This means:

```text
real world camera feed
+
virtual content
=
mixed reality view
```

Unlike optical AR glasses, the user is not looking directly through transparent glass. The headset shows a camera-based view of the real world.

Advantages:
- virtual objects can appear more solid
- real and virtual content can be blended
- occlusion can be controlled
- lighting and color can be adjusted

Limitations:
- depends on camera quality
- depends on lighting
- small latency may exist
- image may look different from natural eyesight

---

# 13. Understanding LiDAR Depth

The XR-3 includes depth sensing using LiDAR and RGB fusion.

This helps with:
- real-world depth awareness
- occlusion
- spatial reconstruction
- mixed reality object placement

Example:

```text
real table
↓
LiDAR depth map
↓
virtual object appears correctly on table
```

Important:
Depth sensing has a working range. Objects too close or too far may not produce ideal depth data.

---

# 14. Understanding Eye Tracking

The XR-3 includes 200 Hz eye tracking.

Eye tracking can be used for:
- foveated rendering
- gaze interaction
- usability studies
- attention analysis
- training evaluation
- cognitive workload research

Basic workflow:

```text
eye movement
↓
gaze estimation
↓
Varjo software / application
↓
data output or interaction
```

For research, always record:
- calibration quality
- participant ID
- headset fit
- session time
- lighting condition
- software version

---

# 15. Understanding Hand Tracking

The XR-3 supports Ultraleap hand tracking.

This allows:
- controller-free interaction
- hand gestures
- natural manipulation
- training simulations
- virtual UI interaction

Basic workflow:

```text
hands visible to sensors
↓
Ultraleap tracking
↓
hand skeleton data
↓
XR application
```

Hand tracking works best when:
- hands are in front of headset
- lighting is adequate
- hands are not blocked
- movement is not too fast

---

# 16. STEP-BY-STEP Basic VR Workflow

1. Connect headset
2. Start Varjo Base
3. Start SteamVR
4. Confirm tracking
5. Launch VR application
6. Put on headset
7. Check image clarity
8. Begin session
9. Exit application
10. Close SteamVR / Varjo Base after use

---

# 17. STEP-BY-STEP Mixed Reality Workflow

1. Connect headset
2. Start Varjo Base
3. Enable passthrough / MR mode
4. Check room lighting
5. Confirm tracking
6. Launch MR application
7. Test virtual object placement
8. Check occlusion
9. Begin experiment or demo
10. Save logs or recordings

---

# 18. STEP-BY-STEP Eye Tracking Research Workflow

1. Start Varjo Base
2. Fit headset carefully
3. Run eye tracking calibration
4. Record calibration quality
5. Launch research application
6. Start data recording
7. Run participant task
8. Stop recording
9. Export gaze data
10. Save session metadata

Recommended metadata:
- participant ID
- date
- headset model
- Varjo Base version
- application version
- calibration result
- tracking quality
- room lighting
- notes

---

# 19. STEP-BY-STEP Unity Workflow

1. Install Unity LTS
2. Install OpenXR package
3. Install Varjo support if needed
4. Set build target to PC
5. Enable OpenXR
6. Select Varjo-compatible runtime
7. Start Varjo Base
8. Connect headset
9. Press Play in Unity
10. Test headset output

Common Unity uses:
- simulation
- MR prototypes
- gaze interaction
- hand tracking experiments
- training applications

---

# 20. STEP-BY-STEP Unreal Workflow

1. Install Unreal Engine
2. Enable OpenXR plugin
3. Enable Varjo-related plugin if needed
4. Start Varjo Base
5. Start SteamVR if using SteamVR tracking
6. Open Unreal project
7. Run VR Preview
8. Test headset output

Common Unreal uses:
- high-fidelity simulation
- vehicle training
- industrial training
- architecture visualization
- virtual production

---

# 21. STEP-BY-STEP SteamVR Tracking Workflow

1. Power on base stations
2. Open SteamVR
3. Check base station icons
4. Check headset icon
5. Check controller / tracker icons
6. Run room setup if needed
7. Test headset tracking

If tracking is unstable:
- check base station line of sight
- remove reflective surfaces
- improve room lighting
- avoid direct sunlight
- restart SteamVR

---

# 22. STEP-BY-STEP Controller Workflow

Depending on setup, XR-3 may be used with:
- SteamVR controllers
- Vive controllers
- Valve Index controllers
- Vive Trackers

Workflow:

```text
controller / tracker
↓
base stations
↓
SteamVR
↓
Varjo application
```

This is useful for:
- hand input
- object tracking
- body tracking
- simulation controls

---

# 23. STEP-BY-STEP Session Shutdown

1. Save work
2. Stop application
3. Remove headset carefully
4. Close SteamVR
5. Close Varjo Base if finished
6. Power off controllers
7. Leave base stations on or power down based on lab policy
8. Store headset safely
9. Coil cables loosely
10. Clean face cushion if needed

---

# 24. Cleaning & Hygiene

Recommended:
- wipe face cushion after use
- clean lenses with microfiber cloth
- do not spray liquid directly on headset
- avoid alcohol on lenses unless approved
- avoid touching camera lenses
- keep cables off the floor

For shared lab use:
- use replaceable face covers
- clean between users
- log use sessions
- inspect headset before and after use

---

# 25. Cable Management

The XR-3 has more cables than consumer headsets.

Common cable issues:
- tangled headset cable
- cable pulling on headset
- USB disconnects
- DisplayPort signal loss
- adapter strain

Best practices:
- keep cables behind user
- use overhead cable management if possible
- avoid sharp bends
- do not roll chair over cables
- do not pull headset by cable

---

# 26. Recommended Use Log

For lab use, record:

```text
Date:
User:
Project:
Headset serial:
Computer:
Varjo Base version:
SteamVR version:
Application:
Tracking status:
Eye calibration quality:
Issues:
```

This helps troubleshoot repeated problems.

---

# 27. Exportable Data

## 27.1 Data Types

Possible data includes:
- gaze data
- eye tracking calibration data
- headset pose
- controller pose
- hand tracking data
- application logs
- mixed reality recordings
- screenshots
- experiment logs

---

## 27.2 Time Granularity

- real-time tracking
- frame-by-frame rendering
- session-based logging
- application-dependent export

---

## 27.3 Data Format

Possible formats:
- CSV
- JSON
- application logs
- video recordings
- Unity / Unreal logs
- custom research output

---

# 28. Recommended Folder Structure

```text
varjo_xr3_projects/
│
├── unity/
├── unreal/
├── varjo_base_logs/
├── eye_tracking/
├── hand_tracking/
├── mixed_reality/
├── recordings/
├── screenshots/
└── session_logs/
```

Example session name:

```text
2026-05-08_varjo_xr3_mr_test01
```

---

# 29. Common Beginner Mistakes

---

## Mistake 1 — Treating It Like A Standalone Headset

The XR-3 needs a high-end PC.

It does not work like:

```text
Quest → install app → play
```

---

## Mistake 2 — Forgetting Varjo Base

Varjo Base must be running for normal headset setup and management.

---

## Mistake 3 — Wrong Cable Connections

Because the XR-3 uses multiple cables and adapters, connection mistakes are common.

Always check:
- DisplayPort
- USB
- adapter power
- headset cable

---

## Mistake 4 — Weak GPU

The headset has very high resolution.

Weak GPUs cause:
- low FPS
- stutter
- bad user experience
- possible nausea

---

## Mistake 5 — Bad Base Station Placement

SteamVR tracking depends on good base station visibility.

Avoid:
- low placement
- blocked line of sight
- unstable mounts
- reflective rooms

---

## Mistake 6 — Skipping Eye Calibration

Eye tracking quality depends on calibration.

Skipping calibration reduces:
- gaze accuracy
- foveated rendering quality
- research data quality

---

## Mistake 7 — Poor Headset Fit

Bad fit causes:
- blurry image
- eye tracking failure
- discomfort
- light leakage

---

# 30. Troubleshooting

## Headset Not Detected

Possible causes:
- DisplayPort not connected
- USB not connected
- adapter not powered
- Varjo Base not running
- driver issue

Possible solutions:
- reconnect cables
- restart Varjo Base
- restart computer
- check adapter power
- update GPU drivers

---

## No Image In Headset

Possible causes:
- DisplayPort issue
- GPU output issue
- Varjo Base error
- headset adapter issue

Possible solutions:
- check DisplayPort cables
- use direct GPU ports
- avoid docking stations
- restart Varjo Base
- restart PC

---

## Tracking Lost

Possible causes:
- base station blocked
- reflective surface
- sunlight
- SteamVR error

Possible solutions:
- check base stations
- remove mirrors
- restart SteamVR
- redo room setup

---

## Passthrough Looks Poor

Possible causes:
- low room lighting
- overexposed light source
- dirty camera lens
- incorrect MR settings

Possible solutions:
- improve lighting
- clean cameras carefully
- adjust environment
- restart MR application

---

## Eye Tracking Fails

Possible causes:
- poor headset fit
- glasses reflection
- eye calibration failed
- face position shifted

Possible solutions:
- refit headset
- redo calibration
- adjust IPD
- improve lighting

---

## Hand Tracking Unstable

Possible causes:
- hands outside tracking area
- fast hand motion
- poor lighting
- occlusion

Possible solutions:
- keep hands in front
- move slower
- improve lighting
- restart hand tracking service

---

# 31. Practical Advice

The XR-3 works best when:

- PC is powerful
- headset is fitted carefully
- tracking area is clean
- base stations are mounted correctly
- cables are managed well
- Varjo Base is updated
- eye tracking is calibrated every session

It is especially strong for:

- high-fidelity simulation
- mixed reality training
- cockpit and dashboard visualization
- medical and industrial simulation
- eye tracking research
- applications where visual clarity matters

---

# 32. Biggest Advantage

The biggest advantage of the Varjo XR-3 is:

```text
PROFESSIONAL MIXED REALITY WITH VERY HIGH VISUAL CLARITY
```

It is not mainly designed for casual VR.

It is designed for:

```text
simulation
+
training
+
research
+
enterprise XR
+
high-resolution mixed reality
```

That is why the XR-3 is often found in:

- aerospace labs
- medical simulation centers
- automotive design
- military training
- university XR labs
- professional visualization environments
- human factors research

---

# 33. Quick Start Checklist

Before session:

```text
[ ] PC powered on
[ ] Varjo Base installed
[ ] GPU driver updated
[ ] Headset adapters connected
[ ] DisplayPort connected
[ ] USB connected
[ ] Base stations powered
[ ] SteamVR tracking working
[ ] Headset detected in Varjo Base
[ ] Eye tracking calibrated
[ ] Passthrough tested
[ ] Application launched
[ ] Cables safely managed
```

After session:

```text
[ ] Save files
[ ] Stop application
[ ] Close SteamVR if done
[ ] Clean face cushion
[ ] Clean lenses if needed
[ ] Store headset safely
[ ] Log any issues
```
