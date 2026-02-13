# Withings BPM Connect

Clinical-grade smart blood pressure monitor with automatic cloud synchronization.

The **Withings BPM Connect** is a Wi-Fi enabled upper-arm blood pressure monitor designed for home and remote clinical monitoring.

---
## Link：https://www.withings.com/us/en/bpm-connect?utm_source=google&utm_medium=cpc&utm_campaign=WIPAID_Google_US_Search_Brand_Products&nbt=nb%3Aadwords%3Ag%3A1424708298%3A144941515351%3A758225049764&nb_adtype=&nb_kwd=withings%20bpm%20connect&nb_ti=kwd-793564868772&nb_mi=&nb_pc=&nb_pi=&nb_ppi=&nb_placement=&nb_li_ms=&nb_lp_ms=&nb_fii=&nb_ap=&nb_mt=e&gad_source=1&gad_campaignid=1424708298&gbraid=0AAAAADCRUEnNBY19YL1NXXwgl8UCAc7yc&gclid=EAIaIQobChMI1LKK5oPXkgMVpShECB3JPwW3EAAYASAAEgJyZ_D_BwE

## Measurements

Each measurement session generates a single timestamped record.

| Field | Unit | Description |
|------|----|----|
| Systolic | mmHg | Systolic blood pressure |
| Diastolic | mmHg | Diastolic blood pressure |
| HeartRate | bpm | Pulse rate |
| IrregularHeartbeat | flag | Arrhythmia detection |
| Timestamp | datetime | Measurement time |

> Not continuous monitoring — event-based measurements only.

---

## Data Collection Methods

### 1. Cloud API (recommended)

Device → WiFi → Withings Cloud → API → Research Database

- Automatic synchronization
- Remote collection
- Scalable for cohorts

Developer portal:  
https://developer.withings.com/

---

### 2. CSV Export

1. Login to Withings dashboard
2. Settings → Download my data
3. Export CSV file

Suitable for pilot studies only.

---

## Battery

The device contains a built-in rechargeable battery (Micro-USB charging).

### Battery Life

Typical usage:

| Measurement Frequency | Expected Battery Life |
|------|------|
| 1 measurement / day | ~6 months |
| 2 measurements / day | ~3–5 months |
| Occasional use | >6 months |

The device is designed for long-term monitoring and rarely requires charging during studies.

## App, Web, and Data Access

The device itself only performs measurements.  
All records are uploaded to the Withings cloud and synchronized across platforms.

| Platform | Purpose |
|------|------|
| Mobile App (Health Mate) | View measurements immediately after recording |
| Web Dashboard | Manage account and export data |
| API | Programmatic access for research |

All platforms display the same dataset stored in the cloud.

---

## Data Available

Each measurement produces a single record:

- Systolic blood pressure
- Diastolic blood pressure
- Heart rate
- Irregular heartbeat flag
- Timestamp

No raw waveform or continuous signal is provided.

---

## Subscription Requirement

No subscription is required.

The device and cloud storage are fully functional without Withings+ membership.  
The optional subscription only provides coaching features and does not affect data access.

---

## Real-time Data

- Measurements appear in the app immediately after completion
- No continuous or streaming data
- Data is event-based only

---

## Data Retention & Storage

| Item | Behavior |
|------|------|
| Cloud storage | Indefinite (until account deletion) |
| Device storage | Temporary buffer before sync |
| Export | Unlimited CSV/API retrieval |

The device is not intended for local storage; it relies on cloud persistence.

## Data Access: CSV vs API

Withings data can be retrieved in two ways:

- **CSV Export** (manual, good for pilot studies)
- **Public Health Data API** (OAuth2, scalable for cohorts)

---

## Option A — CSV Export (manual)

### Export from Mobile App
1. Open the Withings App (Health Mate)
2. Go to **Profile**
3. Tap **Settings**
4. Select **Export All Health Data**
5. Start archive → you will receive an email with a **CSV** download link

### Export from Web Dashboard
1. Open the Withings online dashboard
2. **Settings** → select user
3. Click **Download my data**
4. Download the archive (**CSV**)

Notes:
- This export is not real-time and requires manual action.
- Suitable for small-scale / short pilot studies.
- The archive is typically delivered as a ZIP containing CSV files.

---

## Option B — Withings Public API (recommended for research)

### What you need
To use the API you must implement **OAuth 2.0**:

1. **Create a Withings developer/partner application**
2. Obtain:
   - `client_id`
   - `client_secret`
   - `redirect_uri` (callback URL)
3. Use **OAuth web flow** to obtain:
   - `access_token`
   - `refresh_token`
4. Call API endpoints to retrieve measurements (BP/HR are under the `measure` API).

Reference:
- API Reference (endpoints + measurement types)
- OAuth Web Flow guide

### OAuth2 Web Flow (high-level)
1. Redirect user to Withings authorization URL (user logs in & grants access)
2. Your redirect URI receives an authorization `code`
3. Exchange `code` for `access_token` + `refresh_token`
4. Use `access_token` to call endpoints
5. Use `refresh_token` to renew the access token when needed

### Measurement retrieval
Blood pressure and heart rate can be retrieved via the **Measure endpoint** (`getmeas`).
The API uses measurement type codes for values like:
- Diastolic BP (mmHg)
- Systolic BP (mmHg)
- Heart pulse (bpm)

### Near real-time updates (optional)
Withings also supports notifications/webhooks so your system can be notified when new data is available, then you can fetch it via API.

---

## Practical Notes
- **CSV** = easiest, manual, not scalable
- **API** = best for studies, requires OAuth + token storage + refresh logic
- The device does **not** provide continuous streaming signals; only discrete measurement records.
