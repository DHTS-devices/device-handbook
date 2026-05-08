# Marshall Electronics CV506 Mini HD Camera (3G/HD-SDI, HDMI)

---

# 1. Overview

- Device name:
  Marshall Electronics CV506 Mini HD Camera

- Device type:
  Miniature Broadcast Camera / POV Camera / Compact HD Camera

- Category:
  Vision

- Manufacturer:
  Marshall Electronics

- Overview:
  The Marshall CV506 is a compact professional broadcast-style miniature camera designed for:
  - live production
  - broadcasting
  - sports capture
  - POV filming
  - robotics
  - industrial video
  - hidden camera angles
  - stage production
  - streaming systems

  Unlike consumer webcams or action cameras, the CV506 is designed for professional video pipelines using:
  - 3G-SDI
  - HDMI
  - RS485 control
  - broadcast monitoring systems

  The camera is extremely small but outputs professional Full-HD video with very low latency. 

  One of the biggest reasons these cameras are used in professional environments is because they can be mounted in places where large cameras cannot fit:
  - race cars
  - concert stages
  - robot arms
  - VR rigs
  - machinery
  - ceilings
  - medical systems

  The CV506 supports simultaneous:
  - HDMI output
  - 3G-SDI output

  allowing integration into:
  - switchers
  - capture cards
  - recorders
  - broadcast systems
  - livestream setups

  at the same time. 
---

# 2. What Makes This Camera Different

This is NOT:
- a webcam
- a USB camera
- a consumer camera

This IS:
- a professional video signal camera

It outputs:
```text
HDMI
AND
3G-SDI
```

instead of USB video.

That means:
you normally connect it to:
- capture cards
- switchers
- broadcast systems
- Blackmagic devices
- recorders
- streaming encoders

NOT directly into Zoom like a webcam.

---

# 3. Main Use Cases

The CV506 is commonly used for:

- Broadcast production
- Concert filming
- Sports POV cameras
- Robotics vision
- Industrial inspection
- Surgery/medical systems
- Stage cameras
- Drone systems
- Hidden angle cameras
- Streaming studios

---

# 4. Hardware Information

- Sensor:
  2.5MP 1/2.86-inch sensor

- Video outputs:
  - 3G-SDI
  - HDMI
  Simultaneous output supported 

- Resolution:
  - 1920×1080p
  - 1920×1080i
  - 1280×720p

- Maximum frame rate:
  Up to 60fps 

- Lens mount:
  M12 interchangeable lens mount 

- Included lens:
  Usually:
  - 3.6mm or 4mm M12 lens
  depending on package version 

- Audio:
  3.5mm audio input embedded into SDI stream 

- Control:
  - RS485
  - OSD joystick menu 

- Power:
  12V DC input 

- Body:
  Aluminum miniature housing

- Hardware notes:
  The camera is extremely lightweight and compact.

  It is designed to remain:
  - mounted
  - wired
  - externally powered

  during operation.

---

# 5. Understanding SDI vs HDMI

---

## HDMI

Good for:
- monitors
- capture cards
- simple setups

Common workflow:
```text
CV506 → HDMI → Capture Card → OBS
```

---

## 3G-SDI

Professional broadcast connection.

Advantages:
- longer cable distance
- locking connector
- reliable signal
- broadcast workflow

Common workflow:
```text
CV506 → SDI → Switcher → Streaming System
```

---

# 6. What You Need Before Starting

## Basic Setup

You need:

Required:
- CV506 camera
- 12V power supply
- HDMI or SDI cable
- monitor or capture system

Optional:
- SDI capture card
- Blackmagic switcher
- OBS Studio
- tripod
- M12 lenses

---

# 7. STEP-BY-STEP BASIC HDMI SETUP

---

# STEP 1 — Connect Power

1. Plug 12V DC adapter into camera
2. Verify camera powers on

Usually:
- small LED activates

---

# STEP 2 — Connect HDMI

1. Plug HDMI cable into CV506
2. Plug other side into:
   - monitor
   - capture card
   - recorder

---

# STEP 3 — Verify Video

You should now see:
```text
LIVE HD VIDEO
```

on screen.

If no image:
check:
- resolution compatibility
- power
- cable
- monitor input

---

# STEP 4 — Open OSD Menu

The camera includes:
- joystick controller

through breakout cable.

You can adjust:
- exposure
- white balance
- gain
- gamma
- color

---

# 8. STEP-BY-STEP SDI SETUP

---

# STEP 1 — Connect BNC SDI Cable

1. Connect SDI cable to:
```text
3G-SDI OUT
```

2. Connect other side to:
- SDI monitor
- Blackmagic switcher
- SDI recorder
- SDI capture card

---

# STEP 2 — Verify SDI Signal

If successful:
video appears instantly.

Important:
SDI is NOT the same as coax TV cable.

You need:
```text
75-ohm SDI cable
```

---

# STEP 3 — OBS Streaming Workflow

Typical streaming setup:

```text
CV506
   ↓
Blackmagic Capture Card
   ↓
OBS Studio
   ↓
YouTube / Twitch
```

---

# 9. STEP-BY-STEP Lens Changing

The CV506 uses:
```text
M12 lenses
```

This is important because you can customize:
- field of view
- zoom
- perspective

---

## Common Lens Types

| Lens | Result |
|---|---|
| 2.1mm | Ultra wide |
| 3.6mm | Wide |
| 6mm | Medium |
| 12mm | Zoomed/narrow |

---

## Changing Lens

1. Power off camera
2. Unscrew current lens
3. Install new M12 lens
4. Adjust focus manually
5. Lock focus ring

Important:
M12 lenses are manually focused.

---

# 10. STEP-BY-STEP Focus Adjustment

The lens must be manually focused.

Workflow:
1. Connect monitor
2. Point camera at target
3. Rotate lens slowly
4. Watch image sharpness
5. Stop when sharp

---

# 11. STEP-BY-STEP OBS Streaming Workflow

This is one of the most common real-world workflows.

---

## Required

You need:
- CV506
- HDMI or SDI capture card
- OBS Studio

---

## Workflow

```text
CV506
   ↓
Capture Card
   ↓
OBS
   ↓
Livestream
```

---

## Steps

1. Connect camera to capture card
2. Open OBS
3. Add:
```text
Video Capture Device
```

4. Select capture card
5. Video appears in OBS

Now camera works like livestream source.

---

# 12. STEP-BY-STEP Blackmagic Workflow

Professional broadcast workflow:

```text
CV506
   ↓
SDI
   ↓
ATEM Switcher
   ↓
Streaming / Recording
```

Useful for:
- concerts
- esports
- churches
- stage production
- sports

---

# 13. Robotics Workflow

The CV506 is often used on:
- robots
- drones
- industrial systems

because:
- tiny size
- low latency
- lightweight
- reliable SDI output

Typical workflow:
```text
CV506
   ↓
Capture Device
   ↓
OpenCV / AI
```

---

# 14. Low-Light Usage

The CV506 performs reasonably well for:
- stage lighting
- indoor production
- controlled environments

But it is NOT:
- cinema low-light camera
- night vision camera

Large cinema cameras still outperform it heavily in dark scenes.

---

# 15. Color Adjustment Workflow

The OSD menu allows adjustment of:
- white balance
- gain
- gamma
- black level
- sharpness
- exposure
- paint controls

:contentReference[oaicite:11]{index=11}

Useful for:
- camera matching
- multi-camera broadcast setups

---

# 16. Audio Workflow

The camera supports:
```text
3.5mm audio input
```

Audio can be embedded into:
```text
SDI stream
```

Useful for:
- synchronized recording
- production pipelines



---

# 17. Common Real-World Uses

---

## Sports POV

Mounted:
- inside race cars
- helmets
- bikes
- stadiums

because:
- tiny
- durable
- low latency

---

## Stage Production

Mounted:
- ceilings
- backstage
- instruments
- stage corners

for unique camera angles.

---

## Medical Systems

Used in:
- surgical systems
- microscopes
- medical recording

because:
- small size
- HD signal
- reliable output

---

## Robotics

Used for:
- robot vision
- inspection systems
- industrial AI

---

# 18. Recommended Workflow Ecosystem

Most common tools:

| Tool | Purpose |
|---|---|
| OBS | Streaming |
| Blackmagic ATEM | Switching |
| SDI Monitor | Monitoring |
| Capture Card | PC input |
| OpenCV | AI vision |
| vMix | Production |
| Wirecast | Streaming |

---

# 19. Recommended Folder Structure

```text
cv506_projects/
│
├── recordings/
├── obs_profiles/
├── calibration/
├── screenshots/
└── livestream/
```

---

# 20. Common Beginner Mistakes

---

## Mistake 1 — Thinking It Is USB

The CV506 is NOT USB.

You need:
- HDMI
or
- SDI

capture workflow.

---

## Mistake 2 — Using Cheap SDI Cable

Bad SDI cable causes:
- signal drop
- flicker
- no image

Use proper:
```text
75-ohm SDI cable
```

---

## Mistake 3 — Forgetting Manual Focus

M12 lenses require:
```text
manual focus adjustment
```

---

## Mistake 4 — Wrong Power Supply

The camera needs:
```text
12V DC
```

Wrong voltage may damage camera.

---

# 21. Practical Advice

The CV506 works best when:
- mounted permanently
- connected to broadcast systems
- used in low-latency workflows
- integrated into SDI pipelines

It is especially strong for:
- livestreaming
- broadcast
- robotics
- industrial video
- hidden camera angles
- POV systems
- professional production

---

# 22. Key Difference Between This and Consumer Cameras

Consumer cameras:
```text
Camera → SD card
```

CV506:
```text
Camera → Live signal pipeline
```

That is the biggest mindset difference.

This is primarily:
- a LIVE VIDEO SYSTEM camera

not a consumer recording camera.
