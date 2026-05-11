# GPS Modules LoRaWAN GPS Tracker with 9-axis Accelerometer — LGT92 (915MHz)

---

# 1. Overview

- Device name:
  Dragino LoRaWAN GPS Tracker LGT92 (915MHz)

- Full name:
  GPS Modules LoRaWAN GPS Tracker with 9-axis accelerometer — LGT92 - 915MHz

- Manufacturer Part Number (Mfr. #):
  ```text
  101990655
  ```

- Device type:
  GPS Tracker / LoRaWAN Tracker / Motion Tracking Device / IoT Sensor Node

- Category:
  IoT / GPS Tracking / Edge Sensor Devices

- Manufacturer:
  Dragino

- Overview:
  The Dragino LGT92 is a low-power LoRaWAN GPS tracker designed for:

  - GPS location tracking
  - motion detection
  - asset tracking
  - wearable location tracking
  - smart logistics
  - outdoor sensing
  - movement research
  - IoT projects

  Unlike normal GPS devices that depend on:

  ```text
  Wi-Fi
  or
  Cellular Network
  ```

  the LGT92 uses:

  ```text
  LoRaWAN
  ```

  for:

  ```text
  LONG-RANGE
  LOW-POWER
  COMMUNICATION
  ```

  The device combines:

  - GPS
  - 9-axis IMU
  - accelerometer
  - gyroscope
  - magnetometer
  - LoRaWAN communication

  into one portable sensor node. 

---

# 2. What Category Should It Be In?

Recommended Github category:

```text
iot_tracking/
```

or

```text
sensor_tracking/
```

Example:

```text
devices/
└── iot_tracking/
    ├── lgt92_gps_tracker/
    ├── airtag/
    ├── gps_logger/
    └── lorawan_tracker/
```

Why?

Because this device mainly:

```text
COLLECTS LOCATION
+
MOVEMENT DATA
```

instead of:

```text
XR interaction
```

or:

```text
heavy AI processing
```

Think of it as:

```text
Sensor
↓
Location + Motion
↓
LoRaWAN transmission
```

---

# 3. Main Features

- GPS tracking
- LoRaWAN communication
- 9-axis IMU
- Motion detection
- Accelerometer
- Gyroscope
- Magnetometer
- Long battery life
- Real-time tracking
- Alarm button
- Open-source firmware
- Power monitoring

The LGT92 supports:

```text
LoRaWAN 1.0.3
```

and is available in:

```text
915 MHz (US915)
```

for U.S. deployment.

---

# 4. Hardware Information

- MCU:
  ```text
  STM32L072CZT6
  ```

- GPS module:
  ```text
  Quectel L76-L
  ```

- IMU:
  ```text
  MPU9250
  ```

  Includes:
  - accelerometer
  - gyroscope
  - magnetometer

- GPS accuracy:
  ```text
  < 2.5 m CEP
  ```

- GPS cold start:
  ```text
  < 35 seconds
  ```

- Warm start:
  ```text
  < 30 seconds
  ```

- Re-hot start:
  ```text
  < 1 second
  ```

- Connectivity:
  ```text
  LoRaWAN 915MHz
  ```

- Battery:
  ```text
  1000mAh rechargeable Li-ion
  ```

- Charging:
  USB charging clip

- Size:
  ```text
  85 × 48 × 15 mm
  ```

- Weight:
  ```text
  <55 g
  ```

- Power modes:
  ```text
  ultra-low power sleep
  ```

  Can last:
  ```text
  weeks to months
  ```

  depending on transmission interval. 

---

# 5. What Makes It Different

Traditional GPS tracker:

```text
GPS
↓
Cellular network
↓
Cloud
```

LGT92 workflow:

```text
GPS
+
IMU
↓
LoRaWAN
↓
Gateway
↓
Cloud / dashboard
```

Advantages:

```text
LOW POWER
+
LONG RANGE
```

without requiring:

```text
SIM card
```

This makes it useful for:

- outdoor tracking
- remote sensing
- research deployments
- long-duration monitoring

---

# 6. What Data Does It Collect?

---

## GPS Location

Measures:

```text
latitude
longitude
altitude
speed
```

Useful for:
- movement tracking
- route analysis
- mobility studies

---

## Motion / Activity

The device includes:

```text
9-axis IMU
```

Measures:

- acceleration
- orientation
- movement
- motion state

Can detect:

```text
moving
vs
stationary
```

Useful for:
- transportation research
- movement behavior
- logistics tracking

---

## Event Triggering

Can be configured for:

```text
motion-triggered transmission
```

Example:

```text
movement detected
↓
send GPS update
```

instead of continuous reporting.

This saves:

```text
battery life
```

---

# 7. What Comes in the Box

Usually included:

- LGT92 tracker
- USB charging clip
- battery
- strap / accessories

Usually NOT included:

- LoRaWAN gateway
- dashboard
- computer

---

# 8. IMPORTANT: This Is NOT Wi-Fi GPS

The LGT92 requires:

```text
LoRaWAN infrastructure
```

Examples:

```text
LoRa Gateway
```

such as:

- Dragino Gateway
- The Things Network (TTN)

Without LoRaWAN coverage:

```text
GPS works
BUT data transmission does not
```

This is one of the biggest beginner misunderstandings. 

---

# 9. STEP-BY-STEP First Setup

---

## STEP 1 — Charge Device

Use:

```text
USB charging clip
```

Fully charge before setup.

---

## STEP 2 — Turn On Device

Power switch:

```text
ON
```

LED should blink.

---

## STEP 3 — Register Device

Common platform:

```text
The Things Network (TTN)
```

Need:

```text
Device EUI
App EUI
App Key
```

usually found on:

```text
device label / box
```

---

## STEP 4 — Connect To Gateway

Workflow:

```text
LGT92
↓
LoRa Gateway
↓
TTN
↓
Dashboard
```

---

## STEP 5 — Wait For GPS Lock

Move outdoors.

Cold start may take:

```text
~30 seconds
```

or longer.

Best practice:

```text
open sky view
```

for faster lock.

---

## STEP 6 — Verify Data

Check:

```text
GPS coordinates
motion
battery
```

inside dashboard.

---

# 10. STEP-BY-STEP Research Workflow

For research:

DO NOT just track casually.

Create:

```text
STANDARDIZED PROTOCOL
```

---

## Participant Registration

Record:

```text
participant_id
device_id
date
study_condition
```

---

## Attach Tracker

Options:

- backpack
- wrist strap
- vehicle
- wearable mount

Keep placement:

```text
consistent
```

across participants.

---

## Start Tracking

Define:

```text
sampling interval
```

Example:

```text
every 5 min
every 30 sec
motion-triggered
```

---

## Export Data

Typical outputs:

```text
timestamp
latitude
longitude
speed
motion
battery
```

---

## Save Folder

Example:

```text
gps_tracking_study/
│
├── participant_001/
├── participant_002/
└── exports/
```

---

# 11. Research Recommendations For Your Lab

This may actually be useful for:

---

## XR + Mobility Research

Example:

```text
XR headset
+
LGT92
↓
movement tracking
```

Research:
- movement behavior
- XR locomotion

---

## Human Behavior Studies

Example:

```text
participant
↓
daily mobility
↓
GPS route analysis
```

Useful for:
- spatial behavior
- mobility patterns

---

## Health Research

Possible workflow:

```text
Garmin
+
Hexoskin
+
LGT92
↓
physiology
+
location
```

Interesting research questions:

```text
Does physiology change
by location or movement?
```

For example:
- stress vs environment
- walking behavior
- outdoor activity

---

# 12. Common Beginner Mistakes

---

## No LoRa Gateway

Most common issue.

Without:

```text
LoRaWAN coverage
```

device cannot transmit.

---

## Testing Indoors

GPS lock is weaker indoors.

Best:

```text
outdoor open sky
```

---

## Too Frequent Uploads

Frequent transmission:

```text
kills battery
```

---

## Forgetting Frequency Band

You have:

```text
915MHz
```

Must match:

```text
US915 gateway
```

Wrong region:

```text
device will not connect
```

---

# 13. Cleaning & Maintenance

Recommended:

- recharge regularly
- keep charging contacts clean
- avoid heavy water exposure
- avoid impact damage

---

# 14. Recommended Folder Structure

```text
lgt92_projects/
│
├── gps_tracking/
├── mobility_research/
├── wearable_tracking/
├── participant_logs/
├── exports/
└── lorawan_configs/
```

---

# 15. Practical Advice

The LGT92 works best when:

- GPS has open sky visibility
- LoRaWAN gateway exists
- upload interval is optimized
- battery is charged
- placement is consistent

It is especially strong for:

- movement studies
- asset tracking
- human mobility research
- long-term GPS monitoring
- outdoor sensing

---

# 16. Biggest Advantage

The biggest advantage of the LGT92 is:

```text
LONG-RANGE GPS TRACKING
+
LOW POWER
```

without needing:

```text
cellular subscription
```

making it useful for:

- research tracking
- field studies
- mobility analysis
- outdoor sensing
- IoT deployments
