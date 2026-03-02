## Overview

The Moov Heart Rate Workout Coach Sweatband is a forearm-based optical heart rate monitor designed for high-intensity training and interval workouts.

Unlike wrist-based wearables, the device is worn on the forearm within a sweatband to improve sensor stability during motion-heavy exercise.

It focuses on:

- Heart rate zone coaching
- HIIT training guidance
- Calorie burn optimization
- Real-time audio feedback via mobile app

This device is fitness-coaching oriented rather than clinical-grade.

---

## Measurement Technology

| Component | Function |
|------------|----------|
| Optical PPG sensor | Heart rate monitoring |
| Accelerometer | Movement detection |
| Bluetooth module | App connectivity |
| Sweatband enclosure | Motion stabilization |

Technology base: Photoplethysmography (PPG)

---

## Data Types Collected

| Metric | Unit | Description |
|--------|------|------------|
| Heart Rate | BPM | Continuous during workout |
| Heart Rate Zones | % max HR | Intensity classification |
| Calories Burned | kcal | Estimated energy expenditure |
| Workout Duration | seconds | Session length |
| Activity Intensity | categorical | Based on HR zones |

---

## Real-Time Capability

- Heart rate updates displayed in real time via app
- Audio coaching based on live HR zones
- Designed primarily for session-based training

⚠️ Real-time display does not imply raw data export capability.

---

## Data Format

### Raw Signal Access

| Data Type | Availability |
|------------|--------------|
| Raw PPG waveform | ❌ |
| RR interval | ❌ |
| HRV metrics | ❌ |
| Raw accelerometer data | ❌ |
| API access | ❌ |

No open API or raw physiological signal export.

---

### Available Data Structure (App-Level Summary)

Typical workout summary includes:

| Field | Type |
|--------|------|
| timestamp | datetime |
| duration | seconds |
| avg_hr | bpm |
| max_hr | bpm |
| calories | kcal |
| zone_1_time | seconds |
| zone_2_time | seconds |
| zone_3_time | seconds |
| zone_4_time | seconds |

This is session-level aggregated data.

---

## Data Download

- Data historically accessible through Moov mobile app
- Limited export capability (platform dependent)
- No official developer SDK
- No cloud API access

Since Moov operations ceased, long-term data access is unreliable.

---

## Use Cases

### Suitable For

- Fitness behavior research
- HIIT adherence studies
- Calorie estimation comparison
- Coaching-based intervention research

### Not Suitable For

- HRV research
- Continuous health monitoring
- Raw signal machine learning modeling
- Clinical cardiovascular research

---

## Data Granularity

| Level | Availability |
|--------|--------------|
| Real-time numeric HR | ✔️ |
| Session summary export | Limited |
| Continuous time-series export | ❌ |
| Raw PPG waveform | ❌ |

---

## Comparison Context

Compared to:

- Fitbit Charge series → Better ecosystem & long-term monitoring
- Garmin wearables → GPS + multi-sport integration
- Chest strap HR monitors → Higher HR accuracy for research

Moov Sweatband was optimized for fitness coaching rather than longitudinal health tracking.
