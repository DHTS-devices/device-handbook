# ReSpeaker Mic Array v2.0

---

# 1. Overview

- Device name:
  ReSpeaker Mic Array v2.0

- Device type:
  USB Microphone Array / Voice Interface Development Board

- Category:
  Video & Audio

- Manufacturer:
  Seeed Studio

- Overview:
  The ReSpeaker Mic Array v2.0 is a USB microphone array designed for voice capture, speech recognition, and audio interaction research. The device contains four built-in MEMS microphones and connects directly to a computer through USB.

  Unlike a standard USB microphone, this device supports multi-directional voice pickup and can be used for beamforming and direction-of-arrival (DoA) detection. It is commonly used in robotics, smart room systems, AI voice assistants, and interactive audio environments.

  The device functions as a standard USB audio input and does not require a subscription or cloud account.

- Primary use cases:
  - Voice recording
  - Speech recognition experiments
  - Robotics voice interaction
  - Smart room audio capture
  - Beamforming research
  - Multi-speaker recording
  - AI voice assistant development
  - AI voice interaction projects
  - Robotics systems
  - Smart environment research
  - Spatial audio experiments
  - Multi-directional audio capture

- Official website / guide:
  https://wiki.seeedstudio.com/ReSpeaker_Mic_Array_v2.0/

---

# 2. License / Account / Subscription

- Is an account required?
  No

- Is a subscription required?
  No

- What features are available without subscription?
  All core microphone and recording functions are available without subscription.

- What features require subscription?
  None

---

# 3. Classification

- Category_L1:
  Video_Audio

- Category_L2:
  Microphone_Array

---

# 4. Hardware Information

- Number of microphones:
  4 MEMS microphones

- Audio processor:
  XMOS XVF-3000

- Connection type:
  USB

- Audio output:
  USB audio interface

- Power source:
  USB powered

- Operating system support:
  - Windows
  - Linux
  - macOS

- LED indicators:
  12 programmable RGB LEDs

- Hardware notes:
  The device does not contain internal storage. Audio is streamed directly to the connected computer.

  Since the device is USB powered, no separate charger or battery is required.

---

# 5. Main Features

- Far-field voice capture
- Multi-directional microphone array
- Beamforming
- Direction of arrival (DoA) detection
- Echo cancellation
- Noise suppression
- Real-time audio streaming

- Feature notes:
  Compared to a standard USB microphone, the ReSpeaker array performs better in environments where multiple people are speaking or where directional voice capture is needed.

  The device is commonly used in robotics and AI interaction projects where the system needs to determine where sound is coming from.

---

# 6. Exportable Data

## 6.1 Data Types

Available data includes:
- Raw audio recordings
- Multi-channel audio
- Beamformed audio
- Environmental sound recordings
- Voice recordings
- Speech input streams

---

## 6.2 Time Granularity

- Real-time audio streaming
- Continuous recording
- Session-based recording

---

## 6.3 Data Availability

- Available whenever connected to a computer
- Depends on operating system microphone permissions

---

## 6.4 Data Format

- WAV
- PCM audio stream
- MP3 (software dependent)

---

# 7. Setup & Workflow

## 7.1 Requirements

Required:
- USB cable
- Computer or embedded system
- Audio recording software (optional)

Optional software:
- Audacity
- OBS Studio
- Python
- Whisper
- Vosk

- Environment notes:
  Linux systems are generally easier for advanced beamforming and DSP workflows, although the device works on Windows and macOS as a standard USB microphone.

---

## 7.2 Setup Steps

### Windows

1. Connect device through USB
2. Wait for automatic driver installation
3. Open Sound Settings
4. Confirm ReSpeaker appears as an input device
5. Select ReSpeaker as recording microphone

---

### macOS

1. Connect device through USB
2. Open Audio MIDI Setup
3. Confirm device detection
4. Select as audio input source

---

## 7.3 Daily Usage Workflow

Typical workflow:
1. Connect device
2. Verify microphone input
3. Open recording or experiment software
4. Start recording
5. Save exported files after session
6. Disconnect device after use

- Usage notes:
  For long recording sessions, verify that:
  - USB connection remains stable
  - system sleep mode is disabled
  - storage space is sufficient

---

# 8. Data Export

## 8.1 Manual Export

Audio can be recorded and exported using:
- Audacity
- OBS Studio
- Adobe Audition
- Python scripts

Typical export formats:
- WAV
- MP3
- PCM

---

## 8.2 API / Automated Export

Compatible with:
- PyAudio
- sounddevice
- Whisper
- Vosk
- OpenAI Realtime API

Possible workflows:
- Real-time speech transcription
- AI voice assistant pipelines
- Robotics voice interaction
- Environmental audio analysis

Developer resources:
https://github.com/respeaker/usb_4_mic_array

---

# 9. Additional Software / Environment

Required:
- USB audio support

Optional:
- Audacity
- OBS Studio
- Python
- Linux audio tools

Development environment:
- Python recommended
- Linux preferred for advanced DSP workflows

- Software notes:
  The device can be integrated into AI speech pipelines for:
  - voice assistants
  - speech-to-text systems
  - robotics interaction
  - environmental monitoring

---

# 10. Battery & Maintenance

- Powered directly through USB
- No internal battery

Maintenance recommendations:
- Keep microphones clean
- Avoid moisture exposure
- Disconnect safely after use
- Store in protective container when not in use

- Maintenance notes:
  The device requires minimal maintenance but should be protected from dust and unstable USB power sources.

---

# 11. Troubleshooting

## Device Not Detected

Possible causes:
- USB cable issue
- Driver issue
- Insufficient USB power

Possible solutions:
- Reconnect USB cable
- Restart computer
- Try another USB port
- Use powered USB hub

---

## Low Recording Volume

Possible causes:
- Low microphone gain
- Incorrect system settings
- Large speaker distance

Possible solutions:
- Increase input gain
- Reduce environmental noise
- Test recording settings

---

## Noise or Static

Possible causes:
- Electrical interference
- Unstable USB connection
- Low-quality USB hub

Possible solutions:
- Connect directly to motherboard USB port
- Use shorter cable
- Use powered USB hub

---

# 12. Notes

- Commonly used for robotics and AI voice interaction projects
- More suitable than standard USB microphones for multi-speaker environments
- Useful for smart room and XR interaction experiments
- Does not contain internal storage
- Audio is streamed directly to connected system

- DHTS notes:
  This device is particularly useful for:
  - AI interaction systems
  - robotics research
  - smart room experiments
  - XR voice interaction
  - environmental audio capture
