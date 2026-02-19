# WHOOP Strap 4.0 – Device Documentation

## WebLink：https://www.whoop.com/us/en/?srsltid=AfmBOophhTs4AFnnepYLGO7lmKfo6S5FgGWzy1Q5IrHvZjzsQo80EHSC

## Overview
The WHOOP Strap 4.0 is a continuous physiological monitoring wearable designed for long-term recovery, strain, and sleep analysis.

Unlike traditional smartwatches, WHOOP has no screen and focuses entirely on passive biometric data collection and cloud analytics via a subscription platform.

It is commonly used in:

- Athletic performance monitoring
- Recovery & fatigue tracking
- Sleep research
- Behavioral health studies
- HRV-based physiological modeling

---

## Device Information
| Item | Description |
|-----|------|
| Manufacturer | WHOOP Inc. |
| Device Type | Wrist-worn physiological monitor |
| Category | Wearable Biometric Sensor |
| Form Factor | Strap / band |
| Screen | None |
| Waterproof | Yes (IP68) |
| Charging | Slide-on battery pack (charge while wearing) |
| Connectivity | Bluetooth Low Energy (BLE) |

---

## Sensors
| Sensor | Purpose |
|------|------|
| Optical PPG | Heart rate & HRV |
| Accelerometer | Activity & sleep detection |
| Gyroscope | Motion classification |
| Skin Temperature | Recovery & illness detection |
| SpO₂ | Blood oxygen estimation |

---

## Collected Data
WHOOP continuously records physiological signals and uploads processed metrics to the cloud.

| Data Type | Availability |
|------|------|
| Heart Rate | Continuous |
| Heart Rate Variability (HRV) | Nightly calculated |
| Respiratory Rate | Nightly calculated |
| Skin Temperature | Nightly deviation |
| Sleep Stages | Yes |
| Activity Strain | Yes |
| Recovery Score | Yes |
| Raw PPG | Not accessible |
| Raw Accelerometer | Not accessible |

---

## Data Access
WHOOP data is not stored locally and cannot be directly downloaded from the device.

| Method | Access |
|------|------|
| Mobile App | Yes |
| Cloud Dashboard | Yes |
| API | Yes (developer access required) |
| CSV Export | Limited |
| Raw Signal Access | No |

API Documentation:
https://developer.whoop.com/

---

## Battery
| Feature | Specification |
|------|------|
| Battery Life | ~4–5 days |
| Charging Method | Wearable battery pack |
| Charging Time | ~2 hours |
| Continuous Wear | Supported |

---

## Research Considerations
### Advantages
- Very high compliance (no charging removal)
- Stable HRV estimation during sleep
- Good long-term recovery tracking
- Comfortable for multi-week studies

### Limitations
- No raw signal access
- Subscription required
- Cloud dependency
- Limited reproducibility of proprietary metrics

---

## Typical Research Use Cases
- Sleep & recovery monitoring
- Overtraining detection
- Stress & HRV longitudinal studies
- Behavioral intervention monitoring
- Athlete workload modeling

---

## Comparison Notes
Compared to research-grade wearables:

| Device Type | WHOOP 4.0 |
|------|------|
| Raw Signals | No |
| Long-term Wear | Excellent |
| HRV Stability | High |
| ML Feature Engineering | Limited |
| Clinical Precision | Moderate |
| User Compliance | Very High |

---

## Setup
1. Install WHOOP mobile app
2. Create user account
3. Pair strap via Bluetooth
4. Wear continuously (recommended 24/7)
5. Data syncs automatically to cloud

---

## File Structure Recommendation
Suggested storage structure when used in research:


## Software Ecosystem

### Mobile Application
WHOOP requires the official mobile application to operate.

Platforms:
- iOS
- Android

The app acts as the primary user interface and performs data synchronization and visualization.

#### Functions Available in App
| Feature | Description |
|------|------|
| Live Heart Rate | Real-time HR monitoring |
| Recovery Score | Daily readiness based on HRV, sleep, strain |
| Sleep Analysis | Sleep stages, disturbances, sleep need |
| Strain Tracking | Cardiovascular load estimation |
| Respiratory Rate | Night respiratory calculation |
| Skin Temperature | Deviation from baseline |
| Activity Detection | Automatic workout detection |
| Coaching Insights | Behavioral recommendations |
| Journal | User-reported behaviors (caffeine, alcohol, stress, etc.) |

Data sync occurs automatically via Bluetooth to the phone and then uploads to WHOOP cloud servers.

---

### Web Dashboard
WHOOP also provides a browser-based dashboard.

Capabilities:
- Historical trend visualization
- Athlete/team monitoring
- Research cohort overview (team accounts)
- CSV data export (limited metrics)

---

## API Access

WHOOP provides a cloud-based developer API.

Documentation:
https://developer.whoop.com/

### Authentication
OAuth 2.0 authorization required per user account.

### Available Data via API
| Data | Availability |
|------|------|
| Recovery | Yes |
| Sleep | Yes |
| Workouts | Yes |
| Cycles (daily summaries) | Yes |
| Heart Rate (processed) | Yes |
| HRV | Yes |
| Respiratory Rate | Yes |
| Raw PPG | No |
| Raw Accelerometer | No |

### Important Notes
- Data is aggregated server-side
- Sampling frequency not exposed
- No access to raw sensor signals
- Rate-limited requests

---

