# Withings ScanWatch (Original / 1st Gen)

## Full name
**Withings ScanWatch** — Hybrid smartwatch with **1-lead ECG** and **SpO₂** (clinically positioned).

## Year (development / launch)
- Announced at CES 2020; planned availability in **Q2 2020** 

## Current status (production)
- **Discontinued (production stopped)**: Withings support states they **stopped producing the first ScanWatch** (and Steel HR), remaining stock may still be sold until out of stock

## Does discontinuation affect research use?
- **Functionality**: day-to-day use is **not inherently impacted** as long as the Withings App + cloud services continue supporting it (device still has active support pages and data viewing guidance) 
- **Practical impact**:
  1) Replacement units become harder to buy (inventory only). 
  2) Future clinical features/algorithms may prioritize newer models (e.g., ScanWatch 2 generation).
  3) For publications, always document the exact model as “ScanWatch (Original/1st Gen, 2020)”.

## What data can be collected?
The Withings ecosystem supports heart-related + sleep-related metrics in the app, including:
- **ECG (1-lead)** and atrial fibrillation detection positioning 
- **SpO₂**   
- **Heart rate** history (viewable in app) 
- **Sleep**: duration, depth/interruptions, sleep score, etc. (app-level sleep monitoring features)

> Note: Some respiratory/sleep-apnea related features can be region/clearance dependent (common for this product line).

## How is data collected / accessed?
### 1) Mobile App (primary)
- Use the **Withings App** (previously “Health Mate”) to pair the watch and sync health data

### 2) Withings Cloud + Web Dashboard export (CSV)
- You can export your account data from the **web-based Health Dashboard** as **CSV** (“Download my data”)  
- You can also export data from the **iOS app** (“Export All Health Data”), which emails a CSV archive

### 3) Developer API (Cloud access with consent)
- Withings Public API uses **OAuth 2.0** and allows approved apps to access user-consented health data

**Important limitation for research**:
- API/app exports are typically **summary-level signals**, not raw waveforms (e.g., no raw ECG/PPG stream access in most consumer APIs).

## Basic Specifications

### Battery Life
- Up to **30 days** in normal usage
- Rechargeable via magnetic charging cable
- Approx. 2 hours to fully charge

Note:
Battery duration depends on ECG usage frequency and continuous tracking settings.

---

### Water Resistance
- **5 ATM (50 meters)**
- Suitable for:
  - Showering
  - Swimming (pool)
- Not intended for:
  - Scuba diving
  - High-pressure water activities

---

# Data Collection & Access Methods

## Data Collected by Device

### Cardiovascular
- Continuous heart rate (PPG-based)
- On-demand ECG (1-lead)
- Atrial fibrillation detection (algorithm-based)

### Oxygen & Respiratory
- SpO₂
- Night-time breathing disturbances (region dependent)

### Sleep
- Sleep duration
- Sleep stages (light/deep)
- Sleep score

### Activity
- Steps
- Distance
- Calories
- Workout tracking

---

# How Data Is Collected

## Primary Method: Mobile App

Device → Bluetooth → Withings App (iOS / Android)

The watch syncs via Bluetooth to the Withings App.

Data is then stored in:
- Withings cloud account
- User dashboard (web)

---

## Cloud Storage

All data is synced to the user's Withings account.

Accessible via:
- Web dashboard
- Mobile app
- Data export tools

---

## Data Export Options

### Option A: Manual CSV Export
Via Web Dashboard:
- Download heart rate
- Download sleep data
- Download activity data

Output format:
- CSV files

---

### Option B: Full Account Data Export
Via app:
- Export all health data
- Email-delivered ZIP archive
- Contains CSV files

---

### Option C: Developer API (OAuth 2.0)

Withings provides a public API.

Characteristics:
- Cloud-based access
- Requires user authorization
- Returns summary-level metrics
- No raw ECG waveform access
- No raw PPG signal access

---

# Research Suitability Considerations

## Strengths
- Long battery life (good for longitudinal studies)
- FDA-cleared ECG (clinical credibility)
- High compliance due to classic watch design

## Limitations
- No raw waveform export
- No high-frequency signal sampling access
- Dependent on cloud ecosystem

---

# Practical Recommendation for Research Labs

Best suited for:
- Clinical validation cohorts
- AFib screening pilots
- Long-term heart rate trend monitoring

Not ideal for:
- Raw signal ML development
- Custom BVP feature extraction
- High-frequency physiological modeling

# Technical Specifications (Research-Oriented)

---

## Sampling Frequency

Withings does not publicly disclose full raw sensor sampling rates for the consumer ScanWatch.

Known characteristics:

- Heart rate: Summary-level data (not raw PPG waveform)
- ECG: On-demand recording (single-lead), waveform viewable in app
- Sleep: Epoch-based summary (stage-level, not raw signal)
- Activity: Step-level aggregation

Important:
Raw PPG and continuous ECG waveform export are NOT available through the standard consumer API.

---

## Sensor Stack

The ScanWatch (1st Gen) includes:

- Optical PPG heart rate sensor
- Single-lead ECG electrodes (metal bezel contact system)
- SpO₂ optical sensor
- 3-axis accelerometer
- Altimeter (selected models)

No continuous raw PPG export capability.
No gyroscope exposure in public documentation.

---

## Data Resolution / Granularity

Data provided to users is primarily summary-based:

- Heart rate: Minute-level trends
- ECG: Event-based recording sessions
- Sleep: Stage-level segmentation (epoch-based)
- Activity: Aggregated step count and duration

Not suitable for:
- High-frequency signal analysis
- Custom waveform feature extraction
- Advanced BVP morphology research

Suitable for:
- Trend analysis
- Population-level monitoring
- Clinical screening studies

---

## Data Latency & Sync Behavior

ScanWatch does NOT provide real-time streaming access.

Data flow:

Device → Bluetooth sync → Mobile App → Withings Cloud

Characteristics:

- Requires manual or automatic sync via app
- No real-time API streaming
- Cloud-based storage
- Data export after synchronization

Implication for research:

- Not suitable for real-time intervention systems
- Suitable for retrospective analysis
- Dependent on user sync compliance
