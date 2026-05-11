# DSI-24

---

# 1. Overview

- Device name:
  DSI-24

- Full name:
  Dry Sensor Interface-24 (DSI-24)

- Device type:
  Wireless Dry EEG Headset / Brain-Computer Interface (BCI) Device / Neurophysiology Research System

- Category:
  Neurophysiology & EEG Devices

- Manufacturer:
  Wearable Sensing

- Overview:
  The DSI-24 is a research-grade wireless EEG headset designed for:

  - EEG research
  - brain-computer interface (BCI)
  - XR/VR cognitive monitoring
  - neuroergonomics
  - cognitive workload studies
  - stress monitoring
  - neurofeedback
  - human factors research
  - mobile neuroscience

  Unlike traditional EEG systems that require:

  ```text
  conductive gel
  skin preparation
  long setup
  ```

  the DSI-24 uses:

  ```text
  ACTIVE DRY ELECTRODES
  ```

  meaning:

  ```text
  NO GEL
  +
  FAST SETUP
  +
  MOBILE EEG
  ```

  One of its biggest advantages is:

  ```text
  UNDER 5-MINUTE SETUP
  ```

  while maintaining:

  ```text
  RESEARCH-GRADE EEG QUALITY
  ```

  making it very suitable for:

  ```text
  REAL-WORLD EXPERIMENTS
  ```

  instead of only laboratory environments. 

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
    ├── dsi_24/
    ├── emotiv_epoc_x/
    ├── emotiv_insight2/
    ├── bci/
    ├── eeg/
    └── cognitive_monitoring/
```

Why?

Because DSI-24 mainly:

```text
COLLECTS
HIGH-QUALITY EEG SIGNALS
```

instead of:

```text
consumer wellness
```

or:

```text
XR display hardware
```

Think of it as:

```text
brain activity
↓
research EEG
↓
cognitive analysis
```

---

# 3. Main Features

- 19 dry EEG electrodes
- 2 earclip reference electrodes
- 3 auxiliary physiological inputs
- Wireless EEG recording
- Active dry electrode system
- Continuous impedance monitoring
- Real-time streaming
- Motion-resistant design
- Trigger synchronization
- Long-duration recording
- BCI compatibility
- SDK/API support
- VR/XR integration
- Mobile EEG research

The DSI-24 is especially strong because it supports:

```text
MULTIMODAL PHYSIOLOGY
```

through:

```text
AUX INPUTS
```

including:

```text
ECG
EMG
EOG
GSR
RESP
TEMP
```

which can synchronize directly with EEG. 

---

# 4. Hardware Information

## EEG Channels

The DSI-24 includes:

```text
21 sensors total
```

including:

```text
19 scalp EEG electrodes
+
2 ear references
```

Electrode locations follow the:

```text
10–20 EEG system
```

This gives:

```text
FULL HEAD COVERAGE
```

which is much broader than devices like:

```text
EMOTIV Insight 2.0
```

and closer to a research EEG setup. 

---

## Sampling Rate

Standard:

```text
300 Hz
```

Optional:

```text
600 Hz
```

Internal digitization:

```text
16-bit
```

Bandwidth:

```text
0.003–150 Hz
```

This is strong enough for:

```text
ERP
BCI
attention
stress
cognitive workload
```

research. 

---

## Dry Electrode Technology

The DSI-24 uses:

```text
ACTIVE DRY ELECTRODES
```

Advantages:

```text
NO GEL
NO PASTE
FAST SETUP
```

This is especially helpful when:

```text
many participants
```

need testing.

Traditional EEG:

```text
20–45 min setup
```

DSI-24:

```text
<5 minutes
```

for most users. 

---

## Battery & Wireless

Supports:

```text
Bluetooth
```

Wireless range:

```text
~10 meters
```

Battery system:

```text
hot-swappable batteries
```

Meaning:

```text
continuous recording possible
```

without stopping experiment. 

---

# 5. What Makes It Different

Clinical EEG:

```text
highest precision
↓
long setup
```

EMOTIV:

```text
portable
↓
consumer/research hybrid
```

DSI-24:

```text
MOBILE
RESEARCH EEG
```

Compared with other EEG devices:

| Device | Strongest Feature |
|---|---|
| EMOTIV Insight 2.0 | fast/simple EEG |
| EMOTIV EPOC X | portable research EEG |
| DSI-24 | high-quality dry EEG |
| BioSemi | clinical wet EEG |
| OpenBCI | open-source flexibility |

Biggest advantage:

```text
DRY EEG
+
RESEARCH QUALITY
+
FAST SETUP
```

without:

```text
wet electrodes
```. 

---

# 6. What Signals Does It Collect?

---

## EEG (Very Important)

Main signal:

```text
EEG
(Electroencephalography)
```

Measures:

```text
brain electrical activity
```

Useful for:

- cognitive workload
- attention
- fatigue
- stress
- immersion
- focus
- emotional response
- neurofeedback
- BCI

Brainwave bands:

```text
Delta
Theta
Alpha
Beta
Gamma
```

commonly analyzed in neuroscience.

---

## Auxiliary Sensors (VERY IMPORTANT)

One major strength of DSI-24.

Supports:

```text
3 AUX INPUTS
```

Can integrate:

```text
ECG
EMG
EOG
RESP
GSR
TEMP
```

Meaning:

```text
MULTI-MODAL PHYSIOLOGY
```

For example:

```text
EEG
+
heart activity
+
skin conductance
```

at the:

```text
same timestamp
```

This is VERY powerful for research. 

---

## Trigger Synchronization

Supports:

```text
8-bit trigger input
```

Useful for:

```text
stimulus timing
```

Examples:

```text
VR events
video stimuli
task timing
button press
```

This is critical for:

```text
ERP studies
```

and:

```text
XR experiments
```. 

---

# 7. What Comes in the Box

Usually included:

- DSI-24 headset
- dry electrodes
- ear clips
- Bluetooth adapter
- battery charger
- batteries
- DSI-Streamer software
- accessories kit

Sometimes included:

```text
SDK/API
```

depending on license. 

---

# 8. IMPORTANT: Sensor Contact Matters

This is VERY important.

Even though:

```text
DRY ELECTRODES
```

are easier than gel EEG,

You STILL need:

```text
GOOD SENSOR CONTACT
```

Before recording:

Always check:

```text
impedance quality
```

inside software.

Bad contact causes:

```text
EEG noise
signal dropout
poor data
```. 

---

# 9. STEP-BY-STEP First Setup

---

## STEP 1 — Charge Batteries

Fully charge batteries.

Recommended:

```text
extra batteries ready
```

for long sessions.

---

## STEP 2 — Install Software

Install:

```text
DSI-Streamer
```

Main acquisition software.

Can also integrate with:

```text
LSL
TCP/IP
SDK
```.

---

## STEP 3 — Connect Bluetooth Adapter

IMPORTANT:

Use:

```text
Wearable Sensing Bluetooth adapter
```

not random Bluetooth.

Windows sometimes requires:

```text
disable default Intel Bluetooth
```

for stable connection.

---

## STEP 4 — Wear Headset

Position:

```text
centered on scalp
```

Adjust sensors:

```text
one-by-one
```

until:

```text
good contact
```

Especially:

```text
hair-heavy areas
```

may need adjustment.

---

## STEP 5 — Verify Signal Quality

Open:

```text
DSI-Streamer
```

Check:

```text
all channels
```

Make sure:

```text
signal quality
=
good
```

before starting.

---

## STEP 6 — Baseline Recording

Recommended:

```text
2–5 minute baseline
```

Before experiment.

Example:

```text
eyes open
+
eyes closed
```

for normalization.

---

# 10. IMPORTANT RESEARCH SETUP

For research:

DO NOT just wear and record.

Create:

```text
STANDARDIZED PROTOCOL
```

---

## Same Head Placement

Keep:

```text
same headset placement
```

for every participant.

---

## Timestamp Synchronization

If combining:

```text
DSI-24
+
Empatica E4
+
XR headset
```

Always synchronize:

```text
timestamps
```

VERY important.

---

## Motion Environment

The DSI-24 is:

```text
more motion resistant
```

than many EEG systems,

but still avoid:

```text
large head movement
```

when possible. 

---

# 11. Research Recommendations For Your Lab

This actually fits your lab VERY well.

Because you already do:

```text
XR
physiology
medical applications
```

---

## XR + EEG

Very strong workflow:

```text
Varjo / Vision Pro
+
DSI-24
↓
brain response
```

Research questions:

- cognitive workload
- fatigue
- immersion
- stress
- usability

---

## EEG + Empatica E4

Very strong combination:

```text
EEG
+
EDA
+
BVP
```

Could study:

```text
stress
attention
emotion
physiological arousal
```

Very publishable.

---

## Human Factors Research

Example:

```text
easy task
vs
hard task
↓
EEG differences
```

Very useful for:

```text
medical XR
HCI
training simulation
```

---

# 12. STEP-BY-STEP Data Export

1. Open:

```text
DSI-Streamer
```

2. Connect headset

3. Start recording

4. Export:

```text
CSV
LSL
real-time stream
```

Possible outputs:

```text
EEG
AUX physiology
timestamps
trigger signals
```.

---

# 13. Common Beginner Mistakes

---

## Bad Sensor Contact

Most common issue.

Causes:

```text
bad EEG quality
```

---

## Ignoring Hair Position

Very common problem.

Especially:

```text
occipital regions
```

---

## No Baseline Recording

Very important.

---

## Wrong Bluetooth Adapter

Can cause:

```text
connection issues
```

---

## No Timestamp Sync

Huge issue for multimodal research.

---

# 14. Cleaning & Maintenance

Recommended:

- wipe dry electrodes
- clean headset
- store carefully
- charge batteries

Avoid:

```text
dirty sensor tips
```

because:

```text
signal quality drops
```

---

# 15. Recommended Folder Structure

```text
dsi24_projects/
│
├── eeg/
├── xr_research/
├── cognitive_load/
├── neurofeedback/
├── multimodal/
├── participant_logs/
└── exports/
```

---

# 16. Practical Advice

The DSI-24 works best when:

- sensor contact is adjusted carefully
- baseline is recorded
- timestamps are synchronized
- headset fit is consistent

It is especially strong for:

- EEG research
- mobile neuroscience
- XR cognition
- neuroergonomics
- BCI
- multimodal physiology

---

# 17. Biggest Advantage

The biggest advantage of DSI-24 is:

```text
RESEARCH-GRADE
DRY EEG
+
FAST SETUP
+
MOBILE RECORDING
```

without needing:

```text
wet EEG preparation
```

For research:

```text
ONE OF THE BEST
REAL-WORLD EEG SYSTEMS
```

especially for:

```text
XR
+
physiology
+
multimodal sensing
```.
