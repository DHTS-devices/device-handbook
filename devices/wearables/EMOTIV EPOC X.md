# EMOTIV EPOC X

---

# 1. Overview

- Device name:
  EMOTIV EPOC X

- Device type:
  EEG Headset / Brain-Computer Interface (BCI) Device / Neurophysiology Research Device

- Category:
  Neurophysiology & EEG Devices

- Manufacturer:
  [EMOTIV](https://www.emotiv.com?utm_source=chatgpt.com)

- Overview:
  The EMOTIV EPOC X is a research-grade wireless EEG headset designed for:

  - EEG research
  - brain-computer interface (BCI)
  - cognitive workload studies
  - XR/VR research
  - neurofeedback
  - emotional response analysis
  - human factors research
  - fatigue monitoring
  - attention and engagement studies

  Compared with:

  ```text
  EMOTIV Insight 2.0
  ```

  the EPOC X is:

  ```text
  MORE RESEARCH-FOCUSED
  +
  MORE EEG CHANNELS
  +
  BETTER BRAIN COVERAGE
  ```

  The biggest difference is:

  ```text
  Insight 2.0
  = 5 channels

  EPOC X
  = 14 channels
  ```

  making EPOC X much stronger for:

  ```text
  RESEARCH
  +
  BCI
  +
  EEG ANALYSIS
  ```

  rather than simple neurofeedback or wellness tracking. EPOC X is considered one of the more accessible portable research EEG systems available. :contentReference[oaicite:1]{index=1}

---

# 2. What Category Should It Be In?

Recommended Github category:

```text
neurophysiology_eeg/
```

Example:

```text
devices/
└── neurophysiology_eeg/
    ├── emotiv_epoc_x/
    ├── emotiv_insight2/
    ├── eeg/
    ├── bci/
    └── neurofeedback/
```

Why?

Because EPOC X mainly:

```text
COLLECTS
BRAIN SIGNALS
(EEG)
```

instead of:

```text
wearable physiology
```

or:

```text
XR display hardware
```

Think of it as:

```text
brain activity
↓
EEG
↓
cognitive analysis
```

---

# 3. Main Features

- 14-channel EEG
- Brain-computer interface (BCI)
- Wireless EEG recording
- Saline sensor system
- Real-time EEG streaming
- Motion sensors
- Cognitive monitoring
- Neurofeedback
- Raw EEG access
- SDK support
- Research-grade signal collection
- EEG export support

The EPOC X supports:

```text
REAL-TIME EEG
```

for:

```text
research
+
BCI
+
cognitive monitoring
```

with significantly more spatial coverage than Insight 2.0. 

---

# 4. Hardware Information

## EEG Channels

The EPOC X includes:

```text
14 EEG channels
```

Electrode locations:

```text
AF3
F7
F3
FC5
T7
P7
O1
O2
P8
T8
FC6
F4
F8
AF4
```

plus:

```text
CMS / DRL references
```

at:

```text
P3 / P4
```

This provides much better:

```text
WHOLE-BRAIN COVERAGE
```

than Insight 2.0. 

---

## Sampling Rate

Sampling rate:

```text
128 Hz
or
256 Hz
```

Internal sampling:

```text
2048 Hz
```

Bandwidth:

```text
0.2–45 Hz
```

Built-in:

```text
50Hz / 60Hz notch filtering
```

to reduce electrical noise. 

---

## Motion Sensors

Includes:

```text
9-axis IMU
```

Measures:

- head movement
- acceleration
- orientation

Useful for:

```text
artifact detection
```

especially during:

```text
XR research
```. 

---

## Battery Life

Battery:

```text
Up to ~9 hours
```

Rechargeable:

```text
LiPo battery
```

Suitable for:

```text
long experiment sessions
```.

---

## Connectivity

Supports:

```text
Bluetooth
2.4GHz wireless
USB
```

Compatible with:

- Windows
- macOS

depending on software workflow.

---

# 5. What Makes It Different

Clinical EEG:

```text
many electrodes
↓
highest precision
```

Insight 2.0:

```text
simple portable EEG
```

EPOC X:

```text
MIDDLE GROUND
```

between:

```text
consumer EEG
```

and:

```text
clinical EEG
```

Compared with Insight:

| Device | Strongest Feature |
|---|---|
| Insight 2.0 | simple portable EEG |
| EPOC X | research EEG + BCI |
| BioSemi EEG | clinical EEG |
| OpenBCI | open-source EEG |

The EPOC X is especially strong for:

```text
REAL RESEARCH
```

without needing:

```text
full clinical EEG setup
```. 

---

# 6. What Signals Does It Collect?

---

## EEG (Very Important)

The EPOC X records:

```text
EEG
(Electroencephalography)
```

which measures:

```text
brain electrical activity
```

Useful for:

- cognitive workload
- attention
- fatigue
- stress
- emotional response
- mental workload
- BCI control

Brainwave bands:

```text
Delta
Theta
Alpha
Beta
Gamma
```

are commonly analyzed in neuroscience studies. 

---

## Cognitive Metrics

EMOTIV software may estimate:

```text
focus
stress
engagement
interest
relaxation
```

Important:

```text
THESE ARE DERIVED SCORES
```

For research:

Prefer:

```text
RAW EEG
```

instead of only dashboard metrics. 

---

## Motion Tracking

The IMU measures:

```text
head motion
```

Useful for:

- artifact removal
- XR tracking
- head movement analysis

Especially helpful when participants move during:

```text
VR/XR experiments
```. 

---

# 7. What Comes in the Box

Usually included:

- EMOTIV EPOC X headset
- USB receiver
- saline felt sensors
- carrying case
- charging cable

Usually NOT included:

- research subscription
- raw EEG license
- MATLAB/Python workflows

---

# 8. IMPORTANT: Saline Sensors Matter

Unlike Insight 2.0:

```text
semi-dry polymer sensors
```

EPOC X uses:

```text
SALINE FELT SENSORS
```

Before recording:

You MUST wet sensors with:

```text
saline solution
```

Workflow:

```text
felt pad
↓
wet with saline
↓
attach sensor
↓
good EEG contact
```

If too dry:

```text
BAD SIGNAL QUALITY
```

This is one of the biggest beginner mistakes. 

---

# 9. STEP-BY-STEP First Setup

---

## STEP 1 — Charge Headset

Fully charge device.

Battery:

```text
~9 hours
```

---

## STEP 2 — Prepare Saline Sensors

Wet felt pads using:

```text
saline solution
```

Important:

```text
not dripping wet
```

but:

```text
properly moist
```

---

## STEP 3 — Install Software

Install:

```text
EMOTIV Launcher
```

Then:

```text
EMOTIVPRO
```

for recording.

---

## STEP 4 — Wear Headset

Position:

```text
front to back
```

Sensors must touch:

```text
scalp
```

Hair may interfere.

---

## STEP 5 — Check Contact Quality

Open software.

Verify:

```text
green signal quality
```

for electrodes.

Adjust until:

```text
GOOD CONTACT
```

appears.

This matters A LOT.

---

## STEP 6 — Baseline Recording

Recommended:

```text
2–5 minutes
```

before experiment.

Suggested:

```text
eyes open
+
eyes closed
```

for baseline alpha activity.

---

# 10. IMPORTANT RESEARCH SETUP

For research:

DO NOT just put on headset and start.

Create:

```text
STANDARDIZED PROTOCOL
```

---

## Environmental Control

Reduce:

```text
electrical noise
```

Avoid:

- noisy electronics
- participant movement
- unstable Bluetooth

---

## Timestamp Synchronization

If combining:

```text
EPOC X
+
Empatica E4
+
XR headset
```

Always synchronize:

```text
timestamps
```

This matters a LOT.

---

# 11. Research Recommendations For Your Lab

This is actually:

```text
VERY RELEVANT
```

for your XR work.

Because you already use:

```text
Vision Pro
Varjo
VIVE XR Elite
```

Interesting workflow:

## XR + EEG

```text
XR task
+
EPOC X
↓
brain response
```

Research questions:

- cognitive load
- fatigue
- immersion
- motion sickness
- mental workload

Very useful for:

```text
MEDICAL XR RESEARCH
```

---

## EPOC X + Empatica E4

Very strong setup:

```text
EEG
+
EDA
+
BVP
↓
brain
+
autonomic physiology
```

Could study:

```text
stress
emotion
fatigue
workload
```

Very publishable.

---

## Human Factors Research

Example:

```text
hard task
vs
easy task
↓
EEG difference
```

Very good for:

```text
HCI
XR
medical simulation
```

---

# 12. STEP-BY-STEP Data Export

1. Open:

```text
EMOTIVPRO
```

2. Select participant

3. Start recording

4. Export:

```text
CSV
EDF
raw EEG
```

Possible outputs:

```text
14-channel EEG
motion
timestamps
cognitive metrics
```

Raw EEG often requires:

```text
research license
```. 

---

# 13. Common Beginner Mistakes

---

## Dry Sensors

Most common problem.

Causes:

```text
bad EEG signal
```

---

## Hair Blocking Electrodes

Very common.

Especially:

```text
occipital areas
```

such as:

```text
O1
O2
```

---

## Moving Too Much

Movement causes:

```text
EEG artifact
```

---

## Using Dashboard Scores Only

For research:

Prefer:

```text
RAW EEG
```

---

## No Baseline Recording

Very important.

---

# 14. Cleaning & Maintenance

Recommended:

- clean electrodes
- wash felt pads
- dry headset
- store in case

Avoid:

```text
dirty saline sensors
```

because:

```text
signal quality drops
```

---

# 15. Recommended Folder Structure

```text
epocx_projects/
│
├── eeg/
├── xr_research/
├── neurofeedback/
├── cognitive_load/
├── participant_logs/
├── raw_signals/
└── exports/
```

---

# 16. Practical Advice

The EPOC X works best when:

- saline sensors are prepared correctly
- contact quality is verified
- movement is minimized
- timestamps are synchronized

It is especially strong for:

- EEG research
- BCI
- XR cognition studies
- cognitive workload
- attention research
- neurophysiology

---

# 17. Biggest Advantage

The biggest advantage of EPOC X is:

```text
14-CHANNEL
RESEARCH EEG
+
PORTABILITY
```

without needing:

```text
full clinical EEG lab setup
```

For research:

```text
MUCH STRONGER
than Insight 2.0
```

especially for:

```text
XR
+
cognitive neuroscience
+
multimodal physiology
```. 
