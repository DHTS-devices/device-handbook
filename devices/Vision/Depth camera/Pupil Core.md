# Pupil Core

---

# 1. Overview

- Device name:
  Pupil Core

- Device type:
  Wearable Eye Tracking System / Mobile Eye Tracker / Gaze Tracking Headset

- Category:
  Vision

- Manufacturer:
  [Pupil Labs](https://pupil-labs.com/products/core)

- Overview:
  Pupil Core is an open-source wearable eye tracking platform designed for:
  - gaze tracking
  - eye movement analysis
  - human behavior research
  - VR/AR studies
  - usability testing
  - psychology experiments
  - neuroscience
  - human-computer interaction
  - robotics research

  Unlike traditional desktop eye trackers that require:
  - fixed monitors
  - chin rests
  - stationary users

  Pupil Core is:
  - wearable
  - mobile
  - lightweight
  - modular
  - open-source

  and works like a pair of smart glasses with integrated eye tracking cameras. 

  The system captures:
  - eye movement
  - gaze position
  - pupil diameter
  - scene video
  - gaze direction

  simultaneously in real time.

  One of the biggest reasons Pupil Core became extremely popular in research is:
  ```text
  OPEN SOURCE + RESEARCH FLEXIBILITY
  ```

  Researchers can:
  - modify software
  - write plugins
  - access raw gaze data
  - integrate custom devices
  - synchronize sensors
  - build custom experiments

  unlike many closed commercial eye trackers. 

---

# 2. What Makes It Different

Traditional eye tracker:
```text
Closed ecosystem
+
fixed monitor
+
limited access
```

Pupil Core:
```text
Open source
+
wearable
+
programmable
+
mobile
```

The system behaves more like:
```text
A RESEARCH PLATFORM
```

instead of:
```text
just a commercial eye tracker
```

---

# 3. Main Use Cases

Pupil Core is commonly used for:

- Human behavior research
- Attention analysis
- VR/AR research
- Human-computer interaction
- Usability testing
- Cognitive science
- Neuroscience
- Reading studies
- Driving research
- Sports research
- Robotics
- Mobile gaze tracking
- Human factors engineering
- Consumer behavior research

---

# 4. Hardware Information

- Eye tracking method:
  Dark pupil tracking + 3D eye model 

- Tracking type:
  - monocular
  - binocular

- Eye cameras:
  2 × infrared eye cameras 

- Eye camera resolution:
  ```text
  192 × 192
  ```

- Eye camera sampling rate:
  ```text
  200 Hz
  ```

  depending on configuration.

- Scene/world camera:
  First-person scene camera

- Scene camera modes:
  - 1080p @ 30Hz
  - 720p @ 60Hz
  - 480p @ 120Hz

- Accuracy:
  Approximately:
  ```text
  0.6°
  ```

  with proper calibration. 

- Precision:
  Approximately:
  ```text
  0.02°
  ```

- Connectivity:
  USB-C

- Weight:
  Approximately:
  ```text
  22.75 g
  ```


- Frame material:
  PA12 nylon 

- Computing requirements:
  External computer required:
  - laptop
  - desktop

  Recommended:
  - Intel i7+
  - 8GB+ RAM

---

# 5. What Comes in the Box

Usually included:
- Pupil Core headset
- USB-C cable
- eye camera extenders
- silicone nose pads
- additional world camera lenses
- carrying accessories


---

# 6. Understanding How It Actually Works

The workflow is:

```text
Eye cameras
+
Scene camera
↓
Pupil Capture software
↓
Real-time gaze estimation
↓
Recording / streaming / analysis
```

The system tracks:
```text
WHERE THE USER IS LOOKING
```

relative to:
```text
THE REAL WORLD SCENE
```

captured by the world camera.

---

# 7. Understanding The Cameras

---

# Eye Cameras

The inward-facing IR cameras track:
- pupil center
- eye movement
- pupil size

These are infrared cameras.

You normally do NOT directly look at these recordings during experiments.

---

# World Camera

The outward-facing camera records:
- environment
- first-person view
- scene video

Gaze points are later overlaid onto this video.

---

# Example

If user looks at:
- screen
- object
- person

The software estimates:
```text
GAZE LOCATION
```

inside the scene video.

---

# 8. STEP-BY-STEP FIRST SETUP

---

# STEP 1 — Install Pupil Software

Download:
```text
Pupil Capture
Pupil Player
```

from:
```text
https://docs.pupil-labs.com/
```


---

# STEP 2 — Connect Headset

1. Connect USB-C cable
2. Plug into laptop/desktop
3. Launch:
```text
Pupil Capture
```

If successful:
you should see:
- world camera
- eye cameras

activate.

---

# STEP 3 — Wear The Headset

Wear like:
```text
GLASSES
```

Adjust:
- nose pads
- eye camera arms
- world camera angle

for comfort and visibility.

---

# STEP 4 — Adjust Eye Cameras

This is one of the MOST IMPORTANT steps.

Each eye camera must clearly see:
```text
THE PUPIL
```

You adjust:
- arm position
- angle
- distance

using the movable camera arms. 

---

# STEP 5 — Verify Pupil Detection

Inside Pupil Capture:
you should see:
- pupil ellipse
- pupil detection confidence

If detection is poor:
adjust:
- lighting
- camera angle
- headset fit

---

# 9. STEP-BY-STEP World Camera Alignment

The world camera records:
```text
USER'S VIEW
```

Adjust it so:
- horizon is level
- forward view matches user vision

The camera can rotate vertically.

---

# 10. Understanding Calibration

Calibration teaches the system:
```text
HOW EYE POSITION
=
GAZE DIRECTION
```

Without calibration:
tracking accuracy is poor.

---

# 11. STEP-BY-STEP Calibration Workflow

---

# STEP 1 — Start Calibration

Inside Pupil Capture:
```text
Calibration
```

---

# STEP 2 — Use Calibration Marker

Usually:
- moving marker
- screen target
- printed marker

---

# STEP 3 — Look At Targets

User follows targets with eyes.

The system learns:
```text
eye movement → gaze mapping
```

---

# STEP 4 — Verify Accuracy

After calibration:
gaze cursor should follow:
```text
where user looks
```

---

# 12. Calibration Types

Supported methods include:
- 5-point calibration
- screen marker calibration
- manual marker calibration
- natural features calibration


---

# 13. STEP-BY-STEP Recording Workflow

---

# STEP 1 — Start Recording

Inside Pupil Capture:
```text
Record
```

---

# STEP 2 — Perform Task

Examples:
- reading
- walking
- VR interaction
- usability study
- driving simulation

---

# STEP 3 — Stop Recording

Data saved includes:
- scene video
- eye video
- gaze positions
- pupil diameter
- timestamps

---

# 14. Understanding The Data

Pupil Core records:
- gaze coordinates
- pupil size
- timestamps
- blink events
- fixation events
- scene video
- eye camera video

---

# Example Data

```text
timestamp
gaze_x
gaze_y
pupil_diameter
confidence
```

---

# 15. STEP-BY-STEP Playback Workflow

Use:
```text
Pupil Player
```

Workflow:
1. Open recording
2. Replay session
3. See gaze overlay
4. Analyze fixations
5. Export data


---

# 16. Understanding Gaze Overlay

The software draws:
```text
DOTS / CURSORS
```

onto scene video.

This shows:
```text
WHERE USER LOOKED
```

throughout recording.

---

# 17. STEP-BY-STEP Fixation Analysis

The software can automatically estimate:
- fixations
- saccades
- blinks

Fixation:
```text
eyes relatively stable
```

Saccade:
```text
rapid eye movement
```

Blink:
```text
temporary eye closure
```


---

# 18. STEP-BY-STEP Pupil Diameter Analysis

The system estimates:
```text
PUPIL SIZE
```

in real time.

Useful for:
- cognitive load
- stress research
- emotional response
- fatigue studies

---

# 19. STEP-BY-STEP Real-Time Streaming

Pupil Core supports:
```text
REAL-TIME NETWORK API
```

You can stream:
- gaze data
- pupil data
- timestamps
- videos

over:
- LAN
- localhost
- custom pipelines


---

# 20. STEP-BY-STEP Python Plugin Workflow

One major advantage:
```text
PYTHON PLUGINS
```

You can:
- add custom analysis
- create custom events
- integrate sensors
- modify workflows

---

# Example Workflow

```text
Pupil Core
↓
Python Plugin
↓
Custom experiment
```

---

# 21. STEP-BY-STEP VR Workflow

Common VR workflow:

```text
Pupil Core
↓
VR headset integration
↓
Gaze tracking
↓
Behavior analysis
```

Used for:
- VR attention
- XR research
- immersive interaction

---

# 22. STEP-BY-STEP Multi-Sensor Workflow

Researchers often synchronize:
- EEG
- motion capture
- physiological sensors
- VR systems
- robotics

with gaze data.

Example:

```text
Pupil Core
+
EEG
+
Motion Capture
↓
Synchronized analysis
```

---

# 23. STEP-BY-STEP Motion Capture Integration

Common workflow:

```text
Pupil Core
↓
Mocap system
↓
Head position
+
Gaze direction
↓
3D attention mapping
```

This is heavily used in:
- XR
- robotics
- neuroscience

---

# 24. STEP-BY-STEP Export Workflow

Data export options:
- CSV
- gaze data
- timestamps
- videos
- fixation data
- pupil diameter

Useful for:
- Python
- MATLAB
- R
- machine learning

---

# 25. Understanding Slippage

One major problem in wearable eye tracking:
```text
HEADSET MOVEMENT
```

called:
```text
slippage
```

Pupil Core compensates using:
```text
3D eye model
```

---

# 26. STEP-BY-STEP Focus Adjustment

---

# World Camera Focus

Some world cameras require manual focus.

Rotate lens slowly until:
```text
scene becomes sharp
```

---

# Eye Camera Focus

Important:
```text
200Hz eye cameras DO NOT NEED FOCUSING
```

Do NOT rotate glued lenses. 

---

# 27. Common Real-World Applications

---

## Usability Research

Tracking:
- UI attention
- website usability
- software interaction

---

## Psychology

Studying:
- attention
- cognition
- reading
- memory

---

## Sports Science

Tracking:
- gaze behavior
- reaction patterns
- visual attention

---

## Driving Research

Studying:
- driver attention
- hazard detection
- fatigue

---

## Robotics

Human gaze used for:
- robot interaction
- intention analysis

---

# 28. Common Beginner Mistakes

---

## Mistake 1 — Poor Eye Camera Position

The pupil must remain:
```text
CLEARLY VISIBLE
```

---

## Mistake 2 — Bad Calibration

Poor calibration destroys:
- gaze accuracy
- fixation analysis

---

## Mistake 3 — Reflective Glasses

Strong reflections reduce:
- pupil detection quality

---

## Mistake 4 — Loose Headset

Movement causes:
```text
slippage
```

---

## Mistake 5 — Poor Lighting

Very dark or reflective environments reduce tracking quality.

---

# 29. Recommended Software Ecosystem

| Software | Purpose |
|---|---|
| Pupil Capture | Live recording |
| Pupil Player | Playback/analysis |
| Python | Custom analysis |
| OpenCV | Vision integration |
| Unity | XR workflows |
| ROS | Robotics |
| MATLAB | Research analysis |

---

# 30. Recommended Folder Structure

```text
pupil_core_projects/
│
├── recordings/
├── exports/
├── plugins/
├── python/
├── fixation_analysis/
├── pupil_diameter/
└── experiments/
```

---

# 31. Cleaning & Maintenance

Important:
The headset contains:
- cameras
- electronics
- optics

Do NOT:
- rinse with water
- soak
- spray directly

Recommended:
- microfiber cloth
- alcohol wipes
- gentle cleaning


---

# 32. Practical Advice

Pupil Core works best when:
- headset fits securely
- calibration is done carefully
- lighting is stable
- eye cameras clearly see pupils
- scene camera is aligned properly

It is especially strong for:
- research flexibility
- open-source development
- wearable eye tracking
- VR/XR research
- behavioral science
- multimodal experiments

---

# 33. Biggest Advantage

The biggest advantage of Pupil Core is:

```text
OPEN RESEARCH FLEXIBILITY
```

The system is not just:
```text
an eye tracker
```

It is:
```text
a programmable eye tracking research platform
```

That is why it became extremely popular in:
- academia
- neuroscience
- XR
- robotics
- cognitive science
- HCI research
- behavioral analytics
