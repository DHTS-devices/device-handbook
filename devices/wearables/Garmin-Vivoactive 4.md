# Garmin vivoactive 4

## Overview

Garmin vivoactive 4 is a multi-sport smartwatch designed for:

- Continuous heart rate monitoring
- SpO₂ tracking
- Stress monitoring
- Sleep tracking
- GPS-based activity tracking

It bridges consumer fitness and semi-research use due to relatively strong data export capability.

---

## Sensors & Measurement Technology

| Sensor | Measurement |
|--------|------------|
| Optical PPG | Heart Rate |
| Pulse Ox sensor | SpO₂ |
| Accelerometer | Movement |
| Gyroscope | Motion orientation |
| Barometric altimeter | Elevation |
| GPS / GLONASS | Location tracking |
| Skin-based HRV estimation | Stress score |

Technology base: Optical PPG + multi-sensor fusion.

---

## Data Types Collected

| Metric | Unit | Description |
|--------|------|------------|
| Heart Rate | BPM | Continuous |
| HRV-derived Stress | score | Algorithm-based |
| SpO₂ | % | Spot or overnight |
| Sleep Stages | categorical | Light/Deep/REM |
| Steps | count | Daily total |
| Calories | kcal | Estimated |
| Activity Minutes | minutes | Intensity-based |
| GPS Track | coordinates | Outdoor sessions |

---

## Real-Time Capability

- Continuous HR tracking
- GPS real-time during activity
- SpO₂ spot measurement
- Live activity streaming (Bluetooth)

Sampling frequency varies:
- HR: 1–5 sec depending on mode
- GPS: 1 sec during activity

---

## Data Format

### 1. Garmin Connect Platform

Data stored in:
- Garmin cloud ecosystem
- User-accessible dashboard

---

### 2. Export Options

Garmin supports:

| Format | Availability |
|--------|--------------|
| CSV | ✔️ (limited fields) |
| FIT file | ✔️ (native format) |
| TCX | ✔️ |
| GPX | ✔️ (GPS only) |
| API access | ✔️ (Garmin Health API) |

---

### 3. FIT File Structure

Native Garmin activity files are in `.FIT` format.

FIT files may include:

- Timestamped heart rate
- GPS coordinates
- Cadence
- Elevation
- Speed
- Activity events

Requires parsing tools:
- fitparse (Python)
- Garmin SDK
- Third-party libraries

---

## Raw Signal Access

| Data Type | Availability |
|------------|--------------|
| Per-second HR | ✔️ (activity mode) |
| HRV raw RR intervals | Limited |
| Raw PPG waveform | ❌ |
| GPS coordinates | ✔️ |
| Continuous time-series export | ✔️ (activity sessions) |

Garmin does not provide raw PPG waveform.

---

## Data Download Workflow

### Manual Export

1. Log into Garmin Connect (web).
2. Select activity.
3. Export as:
   - CSV
   - TCX
   - FIT

---

### API-Based Collection

Garmin Health API (enterprise level):
- Requires application
- Used in research collaborations
- Provides structured JSON endpoints

---

## Research Applications

### Suitable For

- Physical activity research
- GPS movement studies
- Sleep behavior analysis
- Stress modeling (algorithm-based)
- Digital phenotype research
- Heart rate time-series modeling

---

### Not Suitable For

- Raw PPG signal processing
- Clinical-grade HRV research
- Medical diagnosis studies

---

## Data Granularity

| Level | Availability |
|--------|--------------|
| Continuous HR | ✔️ |
| GPS per second | ✔️ |
| Sleep stage summary | ✔️ |
| Raw waveform | ❌ |

---

## Limitations

- No raw PPG waveform
- HRV limited
- API access requires approval
- SpO₂ not continuous during daytime

---
## How to Access Data Programmatically (Code-Level Access)

Garmin does not provide access to internal firmware or proprietary algorithms.

However, data can be accessed through:

1. Garmin Connect export (manual)
2. FIT file parsing (local processing)
3. Garmin Health API (enterprise level)

---

### 1. FIT File Download (Manual Method)

Steps:

1. Log into https://connect.garmin.com
2. Select an activity
3. Click “Export Original”
4. Download the `.FIT` file

The FIT file contains timestamped activity data.

---

### 2. Parsing FIT Files in Python

Install parser:

```bash
pip install fitparse
```
---

## Battery Life
### Battery performance depends on usage mode.

| Mode | Approximate Duration |
|------|----------------------|
| Smartwatch mode | Up to 8 days |
| GPS mode | ~18 hours |
| GPS + Music | ~6 hours |
| GPS + Pulse Ox | Reduced duration |
| Continuous Pulse Ox (overnight) | Moderate battery drain |

Enabling continuous SpO₂ significantly reduces battery life.

Charging time: ~1.5–2 hours (proprietary Garmin charger)

---

## Is the Data Real-Time?

Yes — during active use, many metrics update in near real-time.

---

## Sampling Frequency by Data Type

Sampling frequency varies by mode (rest vs activity).

### 1. Heart Rate (PPG-based)

| Mode | Frequency |
|------|-----------|
| Activity mode | ~1 second |
| Resting / smartwatch mode | 5–15 seconds (adaptive) |
| Broadcast mode | ~1 second |

Garmin uses adaptive sampling to conserve battery.

---

### 2. GPS

| Mode | Frequency |
|------|-----------|
| Standard GPS | 1 Hz (1 sample/sec) |
| Smart Recording | Variable (event-based) |
| UltraTrac mode | Reduced frequency |

Exported FIT files usually contain per-second GPS in standard mode.

---

### 3. SpO₂

| Mode | Frequency |
|------|-----------|
| Spot check | Single measurement |
| Overnight tracking | Periodic sampling |
| Continuous daytime | Not default |

SpO₂ is not continuously sampled every second.

---

### 4. Stress (HRV-derived)

Derived from heart rate variability.

| Mode | Frequency |
|------|-----------|
| Background | Periodic (algorithm-based) |
| Not raw RR export | ✔️ (processed only) |

Garmin does not provide raw RR interval stream in vivoactive 4.

---

### 5. Sleep Data

| Data Type | Frequency |
|-----------|-----------|
| Sleep stage | Epoch-based (multi-minute blocks) |
| Movement | Continuous background |
| HR during sleep | Adaptive sampling |

Sleep staging is algorithm-derived, not raw EEG.

---

## Data Export Granularity

| Metric | Per-second Export | Session Summary Only |
|--------|------------------|----------------------|
| Heart Rate (activity) | ✔️ |
| GPS | ✔️ |
| Steps | ❌ |
| Sleep Stages | ❌ |
| SpO₂ | ❌ |
| Stress | ❌ |

Per-second data is mostly available during recorded activities.

---

## Research Implications

Garmin vivoactive 4 supports:

- Per-second HR modeling (activity mode)
- GPS time-series analysis
- Exercise intensity research

It does NOT support:

- Raw PPG waveform analysis
- Clinical-grade HRV modeling
- Continuous medical monitoring

---
