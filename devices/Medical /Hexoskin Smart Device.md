# Hexoskin Smart Device (Hexoskin Smart Shirt)

---

# 1. Overview

- Device name:
  Hexoskin Smart Device / Hexoskin Smart Shirt

- Device type:
  Wearable Physiological Monitoring Device / Smart Biometric Garment

- Category:
  Wearables & Physiological Monitoring

- Manufacturer:
  Hexoskin (Carré Technologies)  
  [Hexoskin Official Website](https://hexoskin.com?utm_source=chatgpt.com)

- Overview:
  The Hexoskin Smart Device is a wearable smart garment system designed for:

  - physiological monitoring
  - health research
  - sleep research
  - exercise science
  - cardiopulmonary monitoring
  - remote patient monitoring
  - wearable sensing
  - human behavior studies

  Unlike smartwatches (Fitbit, Garmin, Apple Watch), Hexoskin is:

  ```text
  A SMART SHIRT
  ```

  meaning sensors are embedded directly into clothing rather than worn on the wrist. It collects physiological signals from the chest and abdomen using textile sensors. :contentReference[oaicite:1]{index=1}

  The system measures:

  - ECG
  - heart rate (HR)
  - heart rate variability (HRV)
  - respiratory rate (RR)
  - breathing volume
  - activity
  - sleep
  - cadence
  - step count

  making it especially useful for:

  ```text
  LONG-TERM PHYSIOLOGICAL MONITORING
  ```

  in research settings. 

---

# 2. What Category Should It Be In?

Recommended Github category:

```text
wearables_physiological/
```

Example:

```text
devices/
└── wearables_physiological/
    ├── hexoskin/
    ├── empatica_e4/
    ├── fitbit/
    ├── garmin/
    └── polar_h10/
```

Why?

Because Hexoskin mainly:

```text
COLLECTS PHYSIOLOGICAL SIGNALS
```

instead of:

```text
XR interaction
```

or:

```text
AI computation
```

Think of it as:

```text
Wearable sensors
↓
Physiological data
↓
Analysis
```

---

# 3. Main Features

- ECG monitoring
- Heart rate
- HRV
- Respiratory monitoring
- Breathing volume
- Activity tracking
- Sleep monitoring
- Step count
- Cadence
- Bluetooth data streaming
- Long-term recording
- Research dashboard support

Hexoskin garments use:

```text
Textile sensors
```

built directly into the shirt. 

---

# 4. Hardware Information

- Sensor type:
  Textile physiological sensors

- ECG:
  ```text
  1-lead ECG
  ```

- ECG sampling rate:
  ```text
  256 Hz
  ```

- Respiratory channels:
  ```text
  Dual RIP sensors
  ```

- Respiratory sampling:
  ```text
  128 Hz
  ```

- Accelerometer:
  ```text
  3-axis accelerometer
  ```

- Accelerometer sampling:
  ```text
  64 Hz
  ```

- Connectivity:
  ```text
  Bluetooth
  ```

- Data storage:
  Internal recorder

- Battery:
  Approximately:
  ```text
  12–30+ hours
  ```

  depending on recorder model. 

---

# 5. What Makes It Different

Smartwatch workflow:

```text
Wrist sensor
↓
Approximate HR
```

Hexoskin workflow:

```text
Chest textile sensors
↓
ECG + respiration
↓
Physiological signals
```

The biggest difference:

```text
CARDIORESPIRATORY DATA
```

instead of only:

```text
activity tracking
```

Compared with Empatica E4:

| Device | Strongest Signal |
|---|---|
| Hexoskin | ECG + respiration |
| Empatica E4 | EDA + stress |
| Fitbit | Daily wellness |
| Polar H10 | Accurate ECG HR |

For your lab direction:

```text
Hexoskin
+
Empatica E4
=
Very strong combination
```

because:

```text
Hexoskin → cardiac + respiratory
E4 → EDA + temperature
```

---

# 6. What Signals Does It Collect?

---

## Cardiac Signals

Hexoskin contains:

```text
3 textile ECG electrodes
```

Placed around:
- chest
- torso

Measures:

- ECG
- HR
- RR interval
- HRV

This is useful for:

- cardiovascular research
- stress studies
- exercise physiology
- hot flash studies

---

## Respiratory Signals

One of Hexoskin’s biggest strengths.

Measures:

```text
RESPIRATION
```

Including:
- breathing rate
- breathing rhythm
- breathing volume
- minute ventilation

This is something most wearables cannot do reliably. 

---

## Activity Signals

Uses:

```text
3-axis accelerometer
```

Measures:
- movement
- steps
- cadence
- activity level
- posture

---

## Sleep Signals

Can estimate:
- sleep duration
- activity during sleep
- respiration during sleep
- overnight HR

Useful for:
- circadian rhythm research
- sleep quality studies

---

# 7. What Comes in the Box

Usually included:

- Hexoskin shirt
- Smart recorder device
- charging cable
- software access
- dashboard account

Usually NOT included:
- analysis computer
- research software

---

# 8. IMPORTANT: Shirt Fit Matters

This is VERY important.

Hexoskin only works well if:

```text
shirt fit is tight
```

Why?

Because ECG sensors need:

```text
GOOD SKIN CONTACT
```

Loose shirt causes:

- ECG noise
- missing HR
- bad respiration signal
- poor data quality

For research:

Always verify:

```text
correct shirt size
```

before collection. 

---

# 9. STEP-BY-STEP First Setup

---

## STEP 1 — Select Correct Shirt Size

Choose:
```text
tight fit
```

not loose fit.

This affects:

```text
signal quality
```

---

## STEP 2 — Wear Shirt Correctly

Sensors must contact:

```text
skin
```

Important:
shirt should sit flat on chest.

---

## STEP 3 — Attach Recorder

Insert recorder into:

```text
shirt side pocket
```

Connect sensor clip.

---

## STEP 4 — Charge Recorder

Fully charge before study.

---

## STEP 5 — Install Hexoskin App

Install:

```text
Hexoskin App
```

on:
- iPhone
- Android
- computer

---

## STEP 6 — Connect Bluetooth

Workflow:

```text
Recorder
↓
Bluetooth
↓
App
```

---

## STEP 7 — Verify Signal Quality

Check:

- HR signal
- ECG
- respiration

before participant starts.

---

# 10. STEP-BY-STEP Research Workflow

For research:

DO NOT just wear and record.

Create:

```text
STANDARDIZED PROTOCOL
```

---

## STEP 1 — Participant Preparation

Record:

```text
participant_id
date
study_id
shirt_size
```

---

## STEP 2 — Wear Shirt Properly

Check:
- chest contact
- comfort
- signal quality

---

## STEP 3 — Baseline Recording

Recommended:

```text
5 minutes resting baseline
```

before experiment.

Very useful for:
- HRV
- respiratory baseline
- physiological normalization

---

## STEP 4 — Start Experimental Task

Examples:
- exercise
- sleep
- stress induction
- XR experiment
- wearable study

---

## STEP 5 — Export Data

Typical signals:

```text
ECG
RR interval
HR
HRV
breathing
activity
```

---

## STEP 6 — Save Participant Folder

Example:

```text
hexoskin_study/
│
├── participant_001/
├── participant_002/
└── participant_003/
```

---

# 11. Research Recommendations For Your Lab

This is actually relevant to your work.

Because your lab studies:

```text
wearables
+
physiological sensing
```

Hexoskin can complement:

### Empatica E4

Workflow:

```text
Hexoskin
+
Empatica E4
↓
fusion dataset
```

Result:

```text
Cardiac
+
Respiration
+
EDA
+
Temperature
```

Very powerful for:

- stress research
- hot flash studies
- physiological event detection

---

## For Your Hot Flash Research

Potential setup:

```text
Hexoskin
+
EDA sensor
↓
real-time physiology
↓
event detection
```

Interesting signals:

- HR spike
- HRV change
- respiration change
- activity artifact removal

This could actually strengthen:

```text
hot flash detection models
```

because respiration may change during symptoms.

---

# 12. STEP-BY-STEP Data Export

1. Open Hexoskin dashboard
2. Select session
3. Download data
4. Export CSV

Possible signals:

```text
ECG
HR
RR interval
HRV
respiration
activity
sleep
```

---

# 13. Common Beginner Mistakes

---

## Wrong Shirt Size

Most common problem.

Loose shirt:

```text
BAD ECG SIGNAL
```

---

## Dry Skin / Poor Contact

Causes:
- ECG noise
- missing signal

---

## Forgetting Baseline

Very important for research.

---

## Not Synchronizing Time

If combining:

```text
Hexoskin + E4
```

Always sync timestamps.

---

## Motion Artifact

Heavy movement affects:
- ECG
- respiration

---

# 14. Cleaning & Maintenance

Recommended:
- remove recorder before washing
- wash shirt gently
- air dry
- clean electrodes carefully

Do NOT:
```text
wash recorder module
```

---

# 15. Recommended Folder Structure

```text
hexoskin_projects/
│
├── ecg/
├── respiration/
├── sleep/
├── wearable_fusion/
├── hot_flash/
├── participant_logs/
└── exports/
```

---

# 16. Practical Advice

Hexoskin works best when:

- shirt fits tightly
- skin contact is good
- baseline is recorded
- timestamps are synchronized
- participant movement is controlled

It is especially strong for:

- cardiopulmonary research
- physiological monitoring
- wearable sensing
- long-term studies
- sleep studies
- exercise physiology

---

# 17. Biggest Advantage

The biggest advantage of Hexoskin is:

```text
ECG
+
RESPIRATION
+
LONG-TERM WEARABILITY
```

inside a wearable shirt.

This makes it especially useful for:

- physiological research
- cardiopulmonary studies
- wearable AI
- stress studies
- sleep monitoring
- symptom detection systems. 
