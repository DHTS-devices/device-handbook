# Zoom F2-BT

---

# 1. Overview

- Device name:
  Zoom F2-BT

- Device type:
  Portable Field Recorder / Lavalier Bodypack Recorder

- Category:
  Video & Audio

- Manufacturer:
  Zoom

- Overview:
  The Zoom F2-BT is a small portable audio recorder designed mainly for recording speech with a lavalier microphone. It is usually clipped to a person’s belt, placed in a pocket, or attached near the speaker during interviews, fieldwork, lectures, video production, or documentation sessions.

  The main advantage of this recorder is that it records in 32-bit float WAV format. This means the user does not need to manually set recording gain before recording. If the speaker suddenly becomes loud, the audio is less likely to clip. If the speaker is quiet, the recording can usually be raised later during editing.

  The F2-BT version includes Bluetooth support. Bluetooth is used for remote control through the Zoom F2 Control app and for timecode synchronization when paired with compatible timecode devices.

  This device is most useful when the goal is to capture clean spoken audio from one person without carrying a large recorder or camera-mounted microphone.

- Primary use cases:
  - Interview recording
  - Lecture recording
  - Field notes and field audio
  - Documentary audio
  - Video production audio
  - Lavalier microphone recording
  - Hands-free voice recording
  - Recording a speaker while they move around

- Best for:
  - One-person speech recording
  - Interviews
  - Research fieldwork
  - Video projects
  - Situations where the recorder needs to be hidden or clipped onto clothing
  - Users who do not want to manually adjust audio gain

- Official website / guide:
  https://zoomcorp.com/en/jp/field-recorders/field-recorders/f2andf2-bt/

- Manual:
  https://zoomcorp.com/media/documents/E_F2_3.pdf

---

# 2. License / Account / Subscription

- Is an account required?
  No

- Is a subscription required?
  No

- What features are available without subscription?
  All normal recording functions are available without a subscription.

- What features require subscription?
  None

- Notes:
  The recorder works locally. A phone app may be used for Bluetooth control, but the recorder itself does not require a cloud account.

---

# 3. Classification

- Category_L1:
  Video_Audio

- Category_L2:
  Field_Recorder

---

# 4. Hardware Information

- Recorder type:
  Bodypack field recorder

- Recording format:
  32-bit float WAV / BWF

- Recording sample rates:
  - 44.1 kHz
  - 48 kHz

- Audio input:
  3.5 mm locking mic / line input

- Audio output:
  3.5 mm phone / line output

- Included microphone:
  Lavalier microphone

- Storage:
  microSD / microSDHC / microSDXC card

- Maximum supported card size:
  Up to 512 GB

- Power source:
  2 AAA batteries

- USB connection:
  USB-C

- Bluetooth:
  Yes, F2-BT model only

- Built-in speaker:
  No

- Display:
  No full display screen

- Hardware notes:
  The Zoom F2-BT is not designed like a traditional handheld recorder with a large screen and many controls. It is designed to be small, simple, and attached to a person during recording.

  Because there is no large screen, it is important to check the recorder before the session:
  - battery level
  - memory card space
  - microphone connection
  - recording status
  - hold switch position

---

# 5. Main Features

- 32-bit float recording
- No manual gain adjustment required
- Lavalier microphone input
- Compact bodypack design
- Bluetooth remote control
- Timecode support through compatible Bluetooth timecode devices
- Low-cut filter
- Hold switch to prevent accidental button presses
- USB-C file transfer
- microSD card recording

- Feature notes:
  The most important feature is 32-bit float recording. With normal recorders, the user must set gain carefully before recording. If gain is too high, loud speech may distort. If gain is too low, quiet speech may sound noisy after raising volume.

  With this recorder, gain adjustment is not the main concern. The user should still place the microphone correctly, avoid clothing noise, and check that the recorder is actually recording.

  The hold switch is important. After starting a recording, turn on hold mode so the recording is not accidentally stopped in a pocket or during movement.

---

# 6. Exportable Data

## 6.1 Data Types

Available data includes:
- Lavalier microphone recordings
- Interview audio
- Speech recordings
- Field audio
- Video production audio
- Timecoded audio files if timecode workflow is used

---

## 6.2 Time Granularity

- Continuous recording
- Session-based recording
- One file per recording session

---

## 6.3 Data Availability

- Audio is available after recording
- Files are stored on the microSD card
- Files can be transferred by removing the card or using USB-C

---

## 6.4 Data Format

- WAV
- BWF WAV

- Notes:
  The files are high-quality audio files and may be larger than normal compressed audio formats such as MP3.

---

# 7. Setup & Workflow

## 7.1 Requirements

Required:
- Zoom F2-BT recorder
- Lavalier microphone
- microSD card
- 2 AAA batteries
- Headphones for checking audio
- Computer for file transfer

Optional:
- Zoom F2 Control mobile app
- Bluetooth timecode device
- Extra batteries
- Extra microSD card
- Windscreen for outdoor use

---

## 7.2 Setup Steps Before Recording

1. Insert a microSD card
2. Insert two AAA batteries
3. Connect the lavalier microphone to the input jack
4. Lock the microphone connector if using a locking plug
5. Power on the recorder
6. Check that the card is recognized
7. Check that the battery has enough power
8. Do a short test recording
9. Listen to the test recording with headphones
10. Confirm that the microphone is not rubbing against clothing
11. Start the real recording
12. Turn on the hold switch after recording starts

---

## 7.3 Lavalier Microphone Placement

Recommended placement:
- Clip the microphone near the upper chest
- Keep it around 6–8 inches from the speaker’s mouth
- Avoid placing it directly under the chin
- Avoid contact with necklaces, jackets, scarves, or hair
- Keep the cable secured under clothing if possible

Good placement examples:
- shirt collar
- jacket lapel
- center chest area

Bad placement examples:
- inside a pocket
- under thick fabric
- touching skin directly
- near zippers or jewelry
- too close to the mouth

---

## 7.4 Daily Usage Workflow

Typical workflow:
1. Prepare batteries and memory card
2. Attach microphone to speaker
3. Place recorder in pocket or clip it to belt
4. Start test recording
5. Check for clothing noise
6. Start official recording
7. Enable hold switch
8. Record the session
9. Stop recording after session
10. Transfer files to computer
11. Rename files with date and project name
12. Back up files

Example file naming:

```text
2026-05-08_interview_participant01_zoom_f2bt.wav
```

---

# 8. Data Export

## 8.1 Manual Export

Method 1: microSD card

1. Power off the recorder
2. Remove microSD card
3. Insert card into computer
4. Copy WAV files to project folder
5. Back up files before deleting from card

Method 2: USB-C

1. Connect recorder to computer with USB-C cable
2. Use file transfer mode
3. Copy audio files to computer
4. Safely eject device

---

## 8.2 Recommended Folder Structure

```text
project_audio/
│
├── raw/
│   ├── 2026-05-08_interview01_raw.wav
│   └── 2026-05-08_interview02_raw.wav
│
├── edited/
│   ├── 2026-05-08_interview01_cleaned.wav
│
├── transcripts/
│   ├── 2026-05-08_interview01_transcript.txt
│
└── notes/
    └── recording_log.xlsx
```

---

## 8.3 Recording Log

Recommended fields:
- Date
- Project name
- Recorder name
- File name
- Speaker / participant ID
- Location
- Start time
- End time
- Battery changed?
- Card formatted?
- Notes about noise or recording problems

Example:

```text
Date: 2026-05-08
Device: Zoom F2-BT
File: 2026-05-08_interview01.wav
Location: Lab room
Mic placement: shirt collar
Issue: light clothing noise during first 30 seconds
```

---

# 9. Additional Software / Environment

Recommended software:
- Audacity
- Adobe Audition
- DaVinci Resolve
- Premiere Pro
- Final Cut Pro
- Zoom F2 Editor
- Zoom F2 Control app

For transcription:
- Whisper
- Otter.ai
- Adobe transcription tools
- Zoom / Teams transcript tools if audio is imported

- Software notes:
  Because the recorder uses 32-bit float WAV files, some simple audio programs may not handle the files as smoothly as professional audio software.

  If the file sounds too quiet or too loud, adjust the volume during editing instead of assuming the recording failed.

---

# 10. Battery & Maintenance

- Battery type:
  2 AAA batteries

- Battery recommendations:
  - Use fresh batteries before important sessions
  - Carry backup batteries
  - Do not start long sessions with low battery
  - Remove batteries during long-term storage

- Memory card recommendations:
  - Format card before important recording sessions
  - Back up files before deleting
  - Use reliable branded cards
  - Keep one spare card in the kit

- Maintenance recommendations:
  - Keep recorder dry
  - Avoid pulling microphone cable
  - Store lavalier microphone carefully
  - Keep windscreen and mic clip together
  - Check the locking connector before use

---

# 11. Troubleshooting

## No Audio Recorded

Possible causes:
- Microphone not fully plugged in
- Wrong input connection
- Recording was not started
- Card not recognized

Possible solutions:
- Reconnect lavalier microphone
- Do a test recording
- Check recording indicator
- Format or replace microSD card

---

## Audio Has Clothing Noise

Possible causes:
- Microphone rubbing against shirt
- Cable moving under clothing
- Mic placed too low or too loose

Possible solutions:
- Reclip microphone
- Secure cable with tape or clip
- Move microphone away from fabric edges
- Use a windscreen

---

## Audio Is Very Quiet

Possible causes:
- Microphone too far from mouth
- Speaker facing away from microphone
- Lavalier covered by clothing

Possible solutions:
- Move microphone closer
- Check placement
- Raise level during editing

- Notes:
  With 32-bit float recording, quiet audio can often be increased in post-production.

---

## Audio Sounds Distorted

Possible causes:
- Microphone overloaded physically
- Mic rubbing or hitting clothing
- Speaker blowing air directly into mic
- File playback software issue

Possible solutions:
- Check microphone placement
- Use windscreen
- Try opening file in professional audio software
- Lower edited gain if needed

---

## Recorder Stops Accidentally

Possible causes:
- Button pressed in pocket
- Hold switch not enabled

Possible solutions:
- After starting recording, enable hold mode
- Place recorder where buttons are not pressed

---

## Bluetooth App Not Connecting

Possible causes:
- Bluetooth disabled
- Device already paired
- App issue
- Low battery

Possible solutions:
- Restart Bluetooth
- Restart app
- Power cycle recorder
- Check battery level

---

# 12. Notes

- The Zoom F2-BT is best understood as a small bodypack recorder for one-person speech recording.

- It is not the same as a shotgun microphone, room microphone, or full multi-track recorder.

- It is very useful when the person being recorded needs to move around.

- The recorder should be tested before every session because there is no large screen for detailed monitoring.

- The most important practical checks are:
  - Is the microphone connected?
  - Is the recorder actually recording?
  - Is the hold switch enabled?
  - Is the microphone rubbing against clothing?
  - Is there enough battery?
  - Is there enough card space?

- For research or documentation use, always save the original raw WAV file before editing.
