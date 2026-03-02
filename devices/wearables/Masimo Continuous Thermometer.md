## Company Information

- **Company:** Masimo Corporation
- **Product Name:** Radius T° Continuous Thermometer
- **Regulatory Status:** FDA-cleared (medical device)
- **Primary Use:** Hospital continuous temperature monitoring
- **Integration Platform:** Masimo Root® patient monitoring system

---

## Overview

Masimo Radius T° is a wearable, wireless continuous temperature monitoring device designed for hospital and clinical environments.

Unlike spot-check thermometers, Radius T° provides:

- Continuous body temperature monitoring
- Real-time wireless transmission
- Integration with hospital monitoring systems
- Early detection of fever trends

It is typically used in inpatient settings rather than consumer environments.

---

## Measurement Technology

| Component | Function |
|------------|----------|
| Skin temperature sensor | Continuous surface temperature measurement |
| Predictive algorithm | Core temperature estimation |
| Wireless module | Data transmission to Root platform |
| Adhesive patch | Patient attachment |

The device estimates core temperature using surface measurements combined with Masimo’s proprietary algorithms.

---

## Data Types Collected

| Metric | Unit | Description |
|--------|------|------------|
| Skin Temperature | °C / °F | Continuous surface reading |
| Estimated Core Temperature | °C / °F | Algorithm-adjusted value |
| Temperature Trend | continuous | Real-time trend monitoring |
| Alert Flags | categorical | Fever threshold alerts |

---

## Real-Time Capability

Radius T° provides:

- Continuous temperature updates
- Real-time display via Masimo Root monitor
- Alarm notifications for threshold exceedance

Update frequency: near-continuous streaming to hospital monitor.

---

## Data Format

### On-Monitor Data

| Field | Type |
|--------|------|
| timestamp | datetime |
| skin_temp | °C / °F |
| estimated_core_temp | °C / °F |
| alert_status | boolean |

Data is integrated into hospital monitoring dashboards.

---

## Raw Data Access

| Data Type | Availability |
|------------|--------------|
| Continuous numeric temp | ✔️ |
| Session history | ✔️ |
| Raw sensor voltage | ❌ |
| Open API | ❌ (consumer level) |
| HL7 integration | ✔️ (hospital systems) |

Access typically requires hospital IT integration via:

- EMR systems
- HL7 protocol
- Masimo monitoring platform

No public SDK available.

---

## Use Cases

### Suitable For

- Inpatient fever monitoring
- Post-surgical temperature tracking
- Infection detection
- Sepsis early warning systems
- Pediatric continuous monitoring

### Not Suitable For

- Consumer fitness tracking
- Long-term at-home wearable studies
- Open machine learning pipelines (without hospital integration)

---

## Research Applications

- Fever trend modeling
- Early infection detection studies
- Clinical decision support research
- Vital sign integration modeling (HR + SpO₂ + Temp)

Often combined with:
- Masimo pulse oximetry
- Respiratory monitoring
- Multi-parameter ICU datasets

---

## Strengths

- Continuous monitoring
- Hospital-grade reliability
- Integration with full Masimo ecosystem
- Early detection capability

## How to Use

Masimo Radius T° is intended for clinical or hospital use under medical supervision.

---

### 1. Preparation

- Ensure the Masimo Root® monitoring system is powered on.
- Confirm the Radius T° sensor is fully charged.
- Verify patient identity in the monitoring system.
- Inspect adhesive patch and sensor surface for cleanliness.

---

### 2. Sensor Placement

1. Clean the patient’s skin (typically upper chest or axillary region depending on protocol).
2. Allow skin to dry completely.
3. Attach the adhesive patch firmly to the skin.
4. Secure the Radius T° sensor to the adhesive pad.

Proper skin contact is critical for accurate temperature estimation.

---

### 3. Pairing With Monitoring System

1. Activate the Radius T° device.
2. Confirm wireless connection to the Masimo Root® platform.
3. Verify that temperature values appear on the monitor.
4. Confirm correct patient association within the system.

---

### 4. Monitoring

- Temperature values update continuously.
- Monitor real-time temperature trend graph.
- Configure alert thresholds if required.
- Observe alarm notifications for fever or abnormal trends.

---

### 5. Data Recording

Temperature data is:

- Stored within the hospital monitoring system.
- Integrated into EMR via HL7 (if configured).
- Accessible through hospital IT systems.

Consumer-level direct data export is not supported.

---

### 6. Removal

1. Power off or disconnect the device.
2. Gently remove the adhesive patch.
3. Dispose of single-use components appropriately.
4. Clean reusable components according to hospital protocol.

---

## Important Notes

- Designed for supervised clinical environments.
- Not intended for consumer self-monitoring.
- Requires integration with Masimo Root® system.
- Accuracy may be affected by improper placement or poor skin contact.

### 1. Direct Device Collection (Standalone)

Radius T° itself does not store long-term exportable datasets.

- Real-time temperature is transmitted wirelessly.
- Data is displayed on the Masimo Root® monitoring platform.
- Limited on-device storage (temporary buffering only).

No USB export or standalone CSV download is available.

Typical exported dataset structure:

| Field | Type |
|--------|------|
| patient_id | string |
| timestamp | datetime |
| skin_temp | float |
| estimated_core_temp | float |
| alert_flag | boolean |

### Research Data Extraction Methods

If conducting research:

#### Option A: EMR Export
- Request structured data export from hospital IT
- Usually provided as CSV or database extract
- Most reliable method

#### Option B: Masimo System Data Export
- Export from Root monitoring platform (if enabled)
- Depends on institutional configuration

#### Option C: Screen Recording / Manual Logging
⚠️ Not recommended for research-grade studies

---

## Data Granularity Considerations

| Level | Availability |
|--------|--------------|
| Real-time numeric display | ✔️ |
| Continuous trend recording | ✔️ |
| Per-second export | System dependent |
| Raw sensor voltage | ❌ |

Actual sampling rate depends on hospital system configuration.
