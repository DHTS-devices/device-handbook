# OptiTrack V120:Duo and V120:Trio

---

# 1. Overview

- Device names:
  - OptiTrack V120:Duo
  - OptiTrack V120:Trio

- Device type:
  Motion Tracking System / Optical Tracking Bar / 6DoF Tracking Camera System

- Category:
  Vision

- Manufacturer:
  [OptiTrack](https://optitrack.com)

- Overview:
  The OptiTrack V120:Duo and V120:Trio are compact optical motion tracking systems designed for:
  - rigid body tracking
  - VR tracking
  - robotics
  - engineering
  - motion capture
  - research
  - augmented reality
  - object tracking
  - human movement analysis

  Unlike large multi-camera mocap systems that require:
  - room calibration
  - multiple tripods
  - complex setup

  the V120 tracking bars are:
  - pre-calibrated
  - portable
  - self-contained
  - plug-and-play

  out of the box. 

  The biggest difference between the Duo and Trio models is:

| Model | Cameras |
|---|---|
| V120:Duo | 2 cameras |
| V120:Trio | 3 cameras |

  The Trio adds a center camera, improving:
  - tracking redundancy
  - tracking stability
  - AR integration possibilities
  - occlusion handling

  especially in more complicated movement situations. 

  These systems are commonly used for:
  - VR tracking
  - robotics
  - motion capture
  - drone tracking
  - desktop mocap
  - engineering research
  - object tracking
  - HMD tracking

---

# 2. What Makes Them Different

Traditional OptiTrack systems:
```text
Many separate cameras
→ calibration
→ dedicated room
→ complex setup
```

V120 systems:
```text
Single tracking bar
→ USB connection
→ plug-and-play
→ factory calibrated
```

That is the biggest workflow difference.

The V120 series is designed for:
- portability
- quick deployment
- desktop tracking
- engineering applications

rather than full-body Hollywood mocap stages.

---

# 3. Duo vs Trio — Main Difference

| Feature | V120:Duo | V120:Trio |
|---|---|---|
| Cameras | 2 | 3 |
| Tracking Redundancy | Lower | Higher |
| Occlusion Handling | Good | Better |
| AR Possibilities | Limited | Better |
| Complexity | Simpler | Slightly more advanced |
| Weight | Lighter | Heavier |

The Trio is usually better when:
- markers become partially blocked
- tracking is more dynamic
- AR applications are needed

The Duo is often enough for:
- basic rigid body tracking
- desktop tracking
- VR experiments
- simple robotics



---

# 4. Hardware Information

---

# V120:Duo Specifications

- Cameras:
  2 infrared tracking cameras

- Resolution:
  640 × 480 × 2 sensors

- Frame rate:
  120 FPS

- Latency:
  8.3 ms

- Accuracy:
  Approximately ±0.50 mm

- Marker range:
  Approximately 6 meters

- Lens:
  47° × 43° FOV
  3.5 mm lens

- LEDs:
  26 IR LEDs × 2

- Connectivity:
  USB 2.0

- Power:
  12V @ 3A

- Body:
  Aluminum

- Weight:
  Approximately 0.6 kg



---

# V120:Trio Specifications

- Cameras:
  3 infrared tracking cameras

- Resolution:
  640 × 480 × 3 sensors

- Frame rate:
  120 FPS

- Lens:
  47° × 43° FOV

- LEDs:
  26 IR LEDs × 3

- Connectivity:
  USB 2.0

- Power:
  12V @ 3A

- Body:
  Aluminum

- Weight:
  Approximately 1.3 kg



---

# 5. What They Actually Track

These systems track:
```text
REFLECTIVE MARKERS
```

NOT normal objects directly.

You attach reflective markers onto:
- rigid bodies
- helmets
- tools
- robots
- hands
- controllers

Then the cameras detect:
```text
infrared reflections
```

to calculate:
```text
6DoF tracking
```

which means:
- X
- Y
- Z
- pitch
- yaw
- roll

---

# 6. What Comes in the Box

Usually included:

- V120 tracking bar
- USB cable
- power adapter
- Motive:Tracker software license
- rigid body sample
- reflective markers
- marker bases
- quick start guide



---

# 7. STEP-BY-STEP FIRST SETUP

---

# STEP 1 — Mount The Tracking Bar

Options:
- tripod
- monitor mount
- desk mount

The system includes:
```text
1/4"-20 tripod thread
```

Best placement:
- stable
- elevated slightly
- facing tracking area

---

# STEP 2 — Connect Power

1. Connect 12V power supply
2. Verify device powers on

The OLED display should activate.

---

# STEP 3 — Connect USB

1. Connect USB cable to PC
2. Use direct motherboard USB if possible

Avoid:
- cheap USB hubs
- unstable extenders

---

# STEP 4 — Install Motive Software

Download:
```text
Motive:Tracker
```

from OptiTrack support website.

Install:
- drivers
- Motive software



---

# STEP 5 — Open Motive

Launch:
```text
Motive
```

If successful:
you should see:
```text
V120:Duo
or
V120:Trio
```

detected automatically.

---

# 8. Understanding Why No Calibration Is Needed

Normal mocap systems require:
- multi-camera alignment
- wand calibration
- room solving

But V120 systems are:
```text
FACTORY CALIBRATED
```

That means:
the internal camera relationship is already solved.

This is one of the biggest advantages.



---

# 9. STEP-BY-STEP Marker Tracking

---

# STEP 1 — Attach Reflective Markers

Attach markers onto:
- rigid object
- headset
- hand prop
- robot

Markers must remain:
- visible
- rigid
- unmoving relative to each other

---

# STEP 2 — Turn On IR LEDs

The V120 uses:
```text
infrared illumination
```

The reflective markers appear as:
```text
bright white dots
```

inside tracking software.

---

# STEP 3 — Create Rigid Body

Inside Motive:
1. Select visible markers
2. Right click
3. Create rigid body

Now the system tracks:
- position
- rotation

in real time.

---

# 10. STEP-BY-STEP VR Tracking Workflow

Common VR workflow:

```text
Markers on headset
↓
V120 tracking
↓
Position + rotation
↓
VR engine
```

Typical engines:
- Unity
- Unreal Engine
- SteamVR integrations

---

# 11. STEP-BY-STEP Robotics Workflow

Typical robotics workflow:

```text
Markers on robot
↓
V120 tracking
↓
Real-time pose estimation
↓
Robot control system
```

Useful for:
- robot localization
- trajectory analysis
- robotics research

---

# 12. STEP-BY-STEP Unity Workflow

---

# STEP 1 — Install Motive Plugin

Install:
```text
OptiTrack Unity Plugin
```

---

# STEP 2 — Enable Streaming

Inside Motive:
```text
Enable NatNet Streaming
```

---

# STEP 3 — Open Unity

Inside Unity:
1. Import OptiTrack plugin
2. Add OptiTrack client
3. Connect to Motive

Now tracked objects appear live in Unity.

---

# 13. STEP-BY-STEP Unreal Workflow

Very similar to Unity.

Workflow:
```text
Motive
↓
NatNet
↓
Unreal Engine
↓
Live tracking
```

Used for:
- VR
- virtual production
- robotics visualization
- AR systems

---

# 14. Marker Types

---

## Passive Markers

Most common.

They:
```text
reflect IR light
```

No batteries required.

---

## Active Markers

Less common.

They:
```text
emit IR light
```

Need power.

---

# 15. Tracking Accuracy

Typical accuracy:
```text
sub-millimeter
```

under ideal conditions.


Tracking quality depends heavily on:
- marker visibility
- lighting
- occlusion
- distance
- lens setup

---

# 16. Best Real-World Use Distance

Typical best range:
```text
1m–6m
```

Very close:
- can reduce triangulation quality

Very far:
- marker size becomes too small

---

# 17. Occlusion Understanding

This is one of the most important concepts.

Occlusion means:
```text
marker becomes blocked
```

Example:
- hand covers marker
- body rotates away
- object blocks line of sight

The Trio handles occlusion better because:
```text
3 cameras > 2 cameras
```

---

# 18. Why Trio Is Better For AR

The center camera allows:
- additional visual reference
- improved overlap
- stronger tracking consistency

especially when:
- mixing video + tracking
- AR alignment
- partial occlusion



---

# 19. Common Real-World Applications

---

## VR Headset Tracking

Markers attached to:
- HMD
- controllers

Used for:
- room-scale VR
- custom VR systems

---

## Robotics

Tracking:
- robot arms
- drones
- autonomous systems

---

## Sports Science

Tracking:
- body movement
- tools
- biomechanics

---

## Engineering

Tracking:
- mechanical systems
- prototypes
- industrial movement

---

# 20. Recommended Software Ecosystem

| Software | Purpose |
|---|---|
| Motive | Main tracking |
| Unity | VR/AR |
| Unreal Engine | Simulation |
| ROS | Robotics |
| MATLAB | Analysis |
| Python | Data processing |
| NatNet | Data streaming |

---

# 21. Common Beginner Mistakes

---

## Mistake 1 — Using Reflective Environment

Reflective surfaces create:
```text
false markers
```

Avoid:
- mirrors
- shiny metal
- glossy surfaces

---

## Mistake 2 — Markers Too Small

Small markers become difficult to track at distance.

---

## Mistake 3 — Occlusion

Blocked markers break rigid body solving.

---

## Mistake 4 — Weak Marker Geometry

Markers too close together reduce tracking stability.

---

# 22. Practical Advice

The Duo is usually enough for:
- basic rigid body tracking
- desktop VR
- engineering experiments

The Trio is better for:
- more reliable tracking
- AR workflows
- more difficult movement
- partial occlusion situations

---

# 23. Biggest Advantage of V120 Series

The biggest advantage is:
```text
FAST SETUP
```

Compared to full mocap systems:
- portable
- pre-calibrated
- compact
- quick deployment
- engineering-friendly

This is why many labs use them for:
- quick experiments
- robotics
- desktop mocap
- VR prototyping

instead of building full multi-camera rooms.

