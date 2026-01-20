# Fitbit Charge 5

> Audience: Researchers / RAs who receive the device for the first time and need to quickly: set up → sync → understand what data can be collected/exported → know what accounts/software/permissions are required.

---

## 1. Overview
- **Device name**: Fitbit Charge 5
- **Device type**: Wrist-worn health/fitness tracker (wearable fitness tracker)
- **Typical lab use cases**:
  - Daily activity overview: steps, active minutes, calories, etc.
  - Heart rate trends (availability depends on export method and permissions)
  - Sleep summaries (availability depends on export method and permissions)
  - Best for: pilot studies collecting participants’ daily behavior + high-level health summaries
- **Official guide**: https://device101.fitbit.com/guides/morgan-101.html

---

## 2. License / Account / Subscription
- **Data typically available without Premium**: steps, heart_rate, sleep_summary, activity_minutes, calories, exercise_sessions, spO2_summary, stress_eda_metrics
- **Fitbit Premium features (in-app subscription)**: Guided Programs; Personalized Insights & Wellness Report; Premium Challenges and adventures; Access to hundreds of workouts; Mindfulness sessions

---

## 3. Classification (for indexing)
- **Category_L1**: Wearables
- **Category_L2**: Fitness tracker

---

## 4. Exportable data
- **Collectable data**:
  - steps
  - heart_rate
  - sleep_summary
  - activity_minutes
  - calories
  - exercise_sessions
  - spO2_summary
  - stress_eda_metrics

### 4.1 Time granularity (minute-level or finer?)
> Key point: **granularity depends on the export method (account export vs API) and the data type**. In most research/application workflows, common granularities include: **daily summaries, minute-level time series, and (in some cases) finer HR records**.

- **steps / activity_minutes / calories**
  - Common granularity: **daily summary** and **per-minute summary**
  - Note: for many exports/APIs, activity data is commonly organized by minute.

- **heart_rate**
  - Common granularity: **per-minute HR** + daily statistics (e.g., resting HR)
  - Note: whether you can obtain finer-grained HR depends on the endpoint, permissions, and account settings. Plan for per-minute by default and confirm with real exports.

- **sleep_summary**
  - Common granularity: **per-night / per-day** (one sleep record per sleep session), often including stages and duration
  - Note: sleep is typically event/session-based, not a continuous per-minute stream.

- **exercise_sessions**
  - Common granularity: **one record per exercise session** (start/end time + type + summary metrics)
  - Note: session/event-based data, not fixed-frequency sampling.

- **spO2_summary / stress_eda_metrics**
  - Common granularity: often **summary/report-style outputs** (e.g., daily or interval summaries). Availability/frequency may vary by region, account, and feature support.
  - Note: confirm fields and timestamps from a real export before treating as a standardized signal.

### 4.2 “How often is data collected?” (capture vs sync vs export)
- **On-device capture frequency**: determined by device firmware and system policies (not fully user-controlled). For research, the key is preventing gaps via consistent wear + charging.
- **Phone sync frequency (controllable)**: recommended **at least once per day** to ensure data uploads to the cloud.
- **Export/pull frequency (lab-controlled)**:
  - Manual export: typically **weekly / biweekly / monthly** archival, depending on study needs
  - API automated pull: commonly **daily** (e.g., pull yesterday’s data nightly), depending on your pipeline

### 4.3 Practical verification (avoid hard-coding granularity)
After your first account export or API pull, record:
1) timestamp format per dataset (date / datetime / minute)
2) number of records per day (e.g., ~1440 records/day suggests minute-level)
3) whether datasets are event-based (sleep/exercise = one record per session)

Final field dictionary + granularity notes should be maintained in:
`device-toolkit/devices/fitbit_charge_5/schemas/`

### Data formats (varies by method)
- **Possible formats**: JSON / CSV / TXT (depends on export method)

---

## 5. Setup & workflow (first-time researcher)
### 5.1 Pre-check checklist
- Battery level sufficient (recommend fully charged for first use)
- Phone can install Fitbit app (iOS/Android)
- Bluetooth is working
- Account policy: participant-owned account vs lab-managed account (per study SOP)

### 5.2 Mobile quick start (first use, including mobile export)
1. **Charge**: place Charge 5 on the charger and confirm charging (recommend full charge initially).
2. **Install Fitbit app**: install **Fitbit** from the app store (allow Bluetooth + notifications for smoother syncing).
3. **Sign in / create account**: sign in/register with the participant account or lab account per SOP.
4. **Add and pair device**:
   - In the app, go to **“Set up a device”**
   - Select **Charge 5**
   - Follow prompts to enable Bluetooth and complete pairing
5. **Basic setup**: complete profile setup (height/weight/goals). Follow study defaults if your SOP specifies.
6. **Wear**: wear on the wrist, snug but not tight. Loose fit can degrade HR quality.
7. **Confirm sync (critical)**:
   - Go back to the app home and pull-to-refresh, or open the device page to verify last sync time
   - Recommended **at least once per day** to ensure data uploads to the cloud

## 6. Data Export
1. **Mobile data export (for small-scale/personal testing)**:
   - **Prereq**: complete sync first and confirm “last synced” is up to date.
   - **Path (names vary by app version)**:
     1) Open **Profile / Account** or **Settings**
     2) Find **Privacy / Data / Manage data**
     3) Choose **Request / Download your data**
     4) Submit the request and wait for the export package to be prepared
   - **What you get**:
     - Usually an **export package (often ZIP)**
     - You may receive an in-app or email notification; sometimes download is completed via the web

2. **Daily usage notes**:
   - After shower/exercise with heavy sweat, dry the sensor area and skin before wearing
   - Charge when battery is low (e.g., below 20%) to avoid gaps
   - If sync fails: check Bluetooth/network first, then restart app/phone

### 6.2
** Web data
Link: https://dev.fitbit.com/login
Desktop: manual export (web) & API automation (developer registration)
> Desktop workflows are mainly for:
> 1) **Manual web export** (small/medium scale, easier file archiving)
> 2) **Registering a developer app + OAuth** for **API automated pulls** (best for scale)

# A. Manual web export (account data package)
1. Complete pairing and ensure regular sync on mobile (at least once per day).
2. On a computer browser, sign in to the same Fitbit account.
3. Navigate to **Privacy / Data / Manage data**.
4. Request **Download your data** (usually generates a ZIP package), then download to the computer.
5. Archive per lab convention (recommended: `participant_id/date/device/`).

- Pros: easy download and archiving
- Cons: manual steps; not suitable for very large scale

#### B. API automated pulls (recommended for scale)
##### B1. Register a developer application (dev.fitbit.com)
Go to: `https://dev.fitbit.com/login` and sign in.  
Click **REGISTER AN APP** and fill in:

- **Application Name***: `DHTS Device Toolkit` (or `DHTS Fitbit Export`)
- **Description***: `Internal research tool to export Fitbit data for lab studies (non-commercial).`
- **Application Website URL***: your GitHub repo homepage (device-toolkit or device-handbook)
- **Organization***: `DHTS / University of Arizona`
- **Organization Website URL***: your lab or university website
- **Terms of Service URL***: if no formal ToS yet, link a GitHub page/README (later replace with a proper ToS page)
- **Privacy Policy URL***: same approach; for human-subject research, create a proper privacy statement later
- **OAuth 2.0 Application Type***: **Server**
- **Redirect URL*** (critical):
  - Local FastAPI test: `http://localhost:8000/callback`
  - Production server: `https://<your-domain>/callback`
- **Default Access Type***: **Read Only**

Accept terms and register. In **MANAGE MY APPS**, you will see:
- **Client ID**
- **Client Secret**

Store them securely (do NOT commit to GitHub).

##### B2. OAuth & data pull (implemented in code repo)
- Build an authorization URL using Client ID → user consents → redirect returns a `code`
- Exchange `code + Client Secret` for `access_token / refresh_token`
- Schedule token-refresh and periodic pulls; store data to DB/files as needed

---

## 7. Additional software / drivers / environment
- **Required**: Fitbit app (iOS/Android) + Bluetooth
- **Optional**: web browser access to Fitbit account (management/export)
- **For automation (recommended)**:
  - Python/JS runtime
  - OAuth configuration (client id/secret, redirect URL)
  - secure token storage (SQLite/encrypted file)

---

## 8. Battery & maintenance
- **Typical battery life**: ~7 days (varies with usage and features)
- **Lab recommendations**:
  - set a regular charging schedule (e.g., weekly)
  - for abnormal HR data: check fit, sensor contact, and sweat/skin interference

---

## 9. Troubleshooting
- **Sync fails / device not found**: check Bluetooth permissions → restart app → restart phone → re-pair if needed
- **Missing HR data**: device too loose / bad placement → adjust; heavy sweat can affect optical readings
- **Switching phones/users**: confirm account consistency → re-pair → verify sync
- **Cannot use a school/organization Google account (Google Workspace restriction)**:
  If you see  
  *“Can’t use Fitbit with this Google Account… account managed by Google Workspace or a school … not supported …”*  
  the account is a **managed Google Workspace account**. To protect health data privacy, Fitbit does not support using managed org accounts for Fitbit login/linking.  
  **Fix**: use a personal (non-Workspace) Google account or register a Fitbit account with a personal email (e.g., Gmail/Outlook).

---

## 10. Code & automation (link to code repo)
- Suggested code location: `device-toolkit/devices/fitbit_charge_5/`
- Planned contents:
  - `export/`: API pull scripts (OAuth)
  - `parse/`: raw export → standardized tables
  - `schemas/`: field dictionary and mappings

