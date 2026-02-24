# Withings ScanWatch  
**Wearable Health & Fitness Tracker**

---

## Device Summary

**Manufacturer:** Withings  
**Model:** ScanWatch  
**Type:** Hybrid Smartwatch  
**Primary Focus:** Heart health, activity tracking, sleep insights, SpO₂  
**Sync:** Wireless (Bluetooth → Withings App / Health Mate)

The Withings ScanWatch combines a traditional analog watch appearance with advanced health sensors. It tracks activity, heart rate, sleep, and offers clinical-grade ECG functionality depending on region/model.

---

## Key Specifications

- **Display:** Analog hands + minimal OLED screen
- **Connectivity:** Bluetooth LE
- **Battery Life:** Up to *30 days* (varies by usage)
- **Compatibility:** iOS & Android
- **Sensors:**
  - PPG heart rate sensor
  - 3-axis accelerometer
  - Skin-temperature sensor (region/model dependent)
  - Electrodes for ECG

---

## What It Tracks

### Daily Activity
- Step count
- Active calories
- Distance walked
- Active time

### Heart & Cardiovascular
- Continuous heart rate monitoring (rest + workout)
- Heart rate zones
- ECG for atrial fibrillation detection
- SpO₂ (blood oxygen saturation)

### Sleep & Recovery
- Total sleep duration
- Sleep stages (light, deep, REM)
- Sleep score
- Sleep interruptions
- Respiratory insights (where supported)

---

## Setup Instructions

### 1. Download the App
Install the **Withings app (Health Mate)** on your smartphone:
- **iOS:** App Store
- **Android:** Google Play

### 2. Create / Log in to Withings Account

### 3. Add Device
1. Open the app → **Devices**
2. Tap **Add a device**
3. Choose **ScanWatch**
4. Follow pairing instructions via Bluetooth

> Keep the watch close to your phone during pairing.

---

## Daily Use

### Wearing the Watch
- Wear snugly above the wrist bone.
- Ensure sensor area on the back sits flush against the skin.
- Avoid loose wear for best heart/SpO₂ readings.

### Charging
- Connect magnetic charging cable
- Charging time varies by remaining battery
- A full charge typically lasts multiple weeks

### Syncing
- Open the Health Mate app to sync
- Background sync may occur automatically

---

## Reading Health Metrics

### Heart Rate
- Instantaneous and resting heart rate shown in the app
- Can switch into workout mode for continuous monitoring

### ECG
- In the ECG section of the app, follow on-screen instructions
- Hold watch crown or electrodes as directed for recording

### SpO₂
- SpO₂ measurements available in the app
- Wear snugly while measuring

### Sleep
- Sleep automatically detected
- View stages and score each morning in the app

---

## Tips for Best Results

- Wear the device daily — consistent tracking improves trends
- For ECG, be still and follow instructions on screen
- SpO₂ may be affected by cold skin, tattoos, or motion
- Sleep detection improves if the watch is worn snugly overnight

---

## Supported Apps & Integrations

- Withings Health Mate (primary app)
- Third-party export via Health Mate integrations (Apple Health / Google Fit / Strava where supported)

---

### Data Export (For Research Use)

To export collected data:

1. Log in to Withings account (web portal if required).
2. Navigate to data export section.
3. Download available CSV files.
4. Verify timestamps and units before analysis.

Ensure compliance with:
- Institutional review protocols
- Data anonymization standards
- Secure storage procedures

---

### General Time Representation

All recorded data are timestamped.

- **Timestamp format:** Unix epoch (seconds) or ISO 8601 (depending on export method)
- **Time zone:** Typically stored in UTC and displayed in local device time
- **Resolution:** Varies by metric (see below)

When exporting data for research:
- Always confirm time zone alignment
- Convert to a consistent time base before analysis
- Check for daylight saving adjustments

#### A) ECG

- Type: Event-based time series
- Duration: ~30 seconds per recording
- Output:
  - Summary classification (e.g., sinus rhythm)
  - PDF waveform (in-app)
- Raw waveform export: Not typically available via standard export

Each ECG event includes:
- Start timestamp
- Duration
- Result label

### Summary of Temporal Types

| Data Type | Structure | Sampling |
|-----------|----------|----------|
| Steps | Aggregated interval | 1–5 min bins |
| Heart Rate | Intermittent | Variable |
| ECG | Event-based | ~30 sec segment |
| SpO₂ | Spot measurement | Single timestamp |
| Sleep | Segmented overnight | Stage intervals |
| Daily Summary | Daily aggregate | 24h |

---
