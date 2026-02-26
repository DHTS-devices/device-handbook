# Masimo MightySat Pulse Oximeter

## Category
Clinical Device / Pulse Oximeter / Physiological Monitoring

---

## Company Information

- **Company:** Masimo Corporation
- **Product Name:** MightySat® Fingertip Pulse Oximeter
- **FDA Clearance:** Yes (medical device)
- **Primary Market:** Clinical & professional use
- **Connectivity:** Bluetooth (select models)

---

## Overview

Masimo MightySat is a clinically validated fingertip pulse oximeter designed to measure:

- Oxygen saturation (SpO₂)
- Pulse rate
- Perfusion index (PI)
- Pleth variability index (PVi) (selected models)
- Respiratory rate (derived, selected models)

It uses Masimo’s proprietary Signal Extraction Technology (SET®), designed to improve signal reliability during motion and low perfusion conditions.

---

## Key Features

- Medical-grade SpO₂ measurement
- Pulse Rate (PR)
- Perfusion Index (PI)
- Motion-resistant signal processing
- Bluetooth connectivity (MightySat Rx)
- Rechargeable battery
- Fingertip clip form factor

---

## Sensors & Measurement Technology

| Sensor Type | Measurement |
|------------|-------------|
| Dual-wavelength LED (Red/IR) | SpO₂ |
| Photodetector | Pulse waveform |
| Signal Extraction Technology (SET®) | Motion artifact reduction |

Technology base: Photoplethysmography (PPG)

---

## Data Types Collected

| Metric | Unit | Description |
|--------|------|------------|
| SpO₂ | % | Oxygen saturation |
| Pulse Rate | BPM | Beats per minute |
| Perfusion Index (PI) | % | Peripheral perfusion strength |
| Pleth Variability Index (PVi) | % | Fluid responsiveness indicator |
| Respiratory Rate (RRp) | breaths/min | Derived from pleth waveform |

---

## Data Format

### 1. On-Device Display
Real-time numerical display.

### 2. Bluetooth App Export (MightySat Rx model)

App-level data may include:

| Field | Type |
|-------|------|
| timestamp | datetime |
| spo2 | percentage |
| pulse_rate | bpm |
| perfusion_index | percentage |
| pvi | percentage (if available) |

⚠️ Raw pleth waveform export is typically not accessible in consumer mode.

---

## Raw Signal Access

| Data Type | Availability |
|-----------|--------------|
| SpO₂ summary | ✔️ |
| Pulse Rate | ✔️ |
| Perfusion Index | ✔️ |
| Pleth waveform (raw PPG) | ❌ (consumer) |
| Clinical waveform export | Possible in hospital-integrated systems |

For research requiring raw waveform:
Hospital-grade Masimo monitors are required.

---

## Measurement Accuracy

Masimo SET technology is widely validated in:

- Low perfusion states
- Motion conditions
- Neonatal and adult monitoring

Widely cited in peer-reviewed medical research.

---

## Use Cases

### 1. Clinical Research
- Hypoxia monitoring
- Sleep-disordered breathing studies
- COVID-related oxygen tracking
- COPD research

### 2. Sports & Altitude Research
- High-altitude oxygen monitoring
- VO₂-related estimation studies

### 3. Digital Health Validation Studies
- Comparing wearable SpO₂ devices
- Sensor validation benchmark

---

## Not Suitable For

- Continuous 24-hour passive monitoring
- HRV analysis
- Raw PPG machine learning modeling (consumer version)
- Large-scale wearable behavioral studies

---

## Data Granularity

| Level | Availability |
|--------|--------------|
| Real-time display | ✔️ |
| Session export | ✔️ |
| Continuous logging | Limited |
| Raw waveform | ❌ |

---

## Research Tier Classification (DHTS)

| Tier | Suitability |
|------|-------------|
| Clinical Research | ⭐⭐⭐⭐ |
| Device Validation | ⭐⭐⭐⭐ |
| Consumer Fitness | ⭐⭐ |
| ML Signal Processing | ⭐ (unless hospital system) |

---

## Battery & Hardware

- Rechargeable battery
- Fingertip clip sensor
- OLED display
- Bluetooth (Rx model)

---

## Regulatory Status

- FDA-cleared (varies by model)
- CE marked
- Medical device classification

---

## Comparison Context

Compared to consumer devices (Fitbit, Garmin):

- Higher SpO₂ accuracy
- Medical validation
- Lower long-term wearability
- Limited open data access

---

## Summary

Masimo MightySat is a medical-grade pulse oximeter optimized for accurate oxygen saturation measurement under motion and low perfusion conditions.

It is suitable for clinical and validation research but limited in raw signal accessibility for advanced ML modeling.
