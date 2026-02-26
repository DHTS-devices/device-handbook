# Masimo MightySat Pulse Oximeter
#Link: https://www.masimo.com/products/wearables/mightysatrx/
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

## Measurement Accuracy

Masimo SET technology is widely validated in:

- Low perfusion states
- Motion conditions
- Neonatal and adult monitoring

Widely cited in peer-reviewed medical research.

---

## Data Granularity

| Level | Availability |
|--------|--------------|
| Real-time display | ✔️ |
| Session export | ✔️ |
| Continuous logging | Limited |
| Raw waveform | ❌ |

---
## Real-Time Data & Download Capability

### Is the Data Real-Time?

the device performs continuous measurement and updates values in near real-time.

Typical refresh rate:
- SpO₂: ~1 second updates
- Pulse Rate: ~1 second updates
- Perfusion Index (PI): real-time display
- PVi (selected models): real-time display

However, **real-time display does not mean real-time downloadable data stream**.

---

## Data Download Options

Masimo MightySat models differ in data access capability.

---

### MightySat Rx (Bluetooth Model)

| Feature | Availability |
|----------|--------------|
| Bluetooth sync | ✔️ |
| Mobile app integration | ✔️ |
| Session history | ✔️ |
| CSV export | Limited |
| API access | ❌ |
| Raw waveform export | ❌ |

Data can be viewed and exported via the **Masimo Professional Health App**.

Exported data typically includes:

| Field | Type |
|--------|------|
| timestamp | datetime |
| spo2 | percentage |
| pulse_rate | bpm |
| perfusion_index | percentage |
| pvi | percentage (if supported) |

⚠️ Exported data is generally summary-level, not continuous per-second time series.

---

## Raw Signal Access

| Data Type | Consumer MightySat | Hospital Masimo Systems |
|------------|-------------------|--------------------------|
| SpO₂ values | ✔️ | ✔️ |
| Pulse Rate | ✔️ | ✔️ |
| Perfusion Index | ✔️ | ✔️ |
| Pleth waveform (PPG) | ❌ | ✔️ |
| Continuous streaming | ❌ | ✔️ |
| HL7 / EMR integration | ❌ | ✔️ |

Raw pleth waveform access requires hospital-grade Masimo monitoring systems (e.g., Root platform, Rad series).

---
