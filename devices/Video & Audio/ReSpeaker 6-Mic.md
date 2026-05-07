# ReSpeaker 6-Mic Circular Array Kit

---

# 1. Overview

- Device name:
  ReSpeaker 6-Mic Circular Array Kit

- Device type:
  Circular Microphone Array / Raspberry Pi Voice HAT

- Category:
  Video & Audio

- Manufacturer:
  Seeed Studio

- Overview:
  The ReSpeaker 6-Mic Circular Array Kit is a microphone array system designed for Raspberry Pi voice and AI applications. The kit consists of two connected boards:
  - a voice accessory HAT
  - a six-microphone circular array board

  The device is designed for speech recognition, voice interaction, beamforming, and smart assistant systems. Unlike a standard USB microphone, the ReSpeaker 6-Mic Array is intended for embedded AI and edge-computing workflows using Raspberry Pi systems.

  The array supports multi-channel audio input and can be integrated into:
  - robotics systems
  - smart speakers
  - AI assistants
  - conference systems
  - XR interaction environments
  - environmental audio monitoring

  The device is commonly used in projects involving:
  - Alexa Voice Service
  - Google Assistant
  - Whisper
  - local speech recognition pipelines

  The ReSpeaker 6-Mic Array is more advanced than a standard USB microphone because it supports multi-channel directional voice processing and embedded voice applications. :contentReference[oaicite:0]{index=0}

- Primary use cases:
  - Speech recognition
  - Smart assistant development
  - Voice-controlled robotics
  - Multi-speaker recording
  - Embedded AI systems
  - Smart room audio systems
  - Voice conferencing systems

- Best for:
  - Raspberry Pi AI projects
  - Robotics
  - Edge AI development
  - Smart speaker experiments
  - Multi-directional audio capture
  - Embedded voice systems

- Official website / guide:
  [Seeed Studio Wiki](https://wiki.seeedstudio.com/ReSpeaker_6-Mic_Circular_Array_kit_for_Raspberry_Pi/?utm_source=chatgpt.com)

- Product page:
  [Seeed Studio Product Page](https://www.seeedstudio.com/ReSpeaker-6-Mic-Circular-Array-Kit-for-Raspberry-Pi.html?utm_source=chatgpt.com)

---

# 2. License / Account / Subscription

- Is an account required?
  No

- Is a subscription required?
  No

- What features are available without subscription?
  All microphone and recording functions

- What features require subscription?
  None

- Notes:
  The device operates locally and does not require cloud services or subscriptions.

---

# 3. Classification

- Category_L1:
  Video_Audio

- Category_L2:
  Microphone_Array

---

# 4. Hardware Information

- Microphone configuration:
  6 microphone circular array

- Audio chips:
  - 2 × X-Power AC108 ADC
  - 1 × X-Power AC101 DAC

- Input channels:
  8 input channels

- Output channels:
  8 output channels

- Connection type:
  Raspberry Pi 40-pin GPIO HAT

- Audio outputs:
  - 3.5mm headset jack
  - Speaker connector

- Supported platform:
  Raspberry Pi

- Grove support:
  Yes

- Maximum sample rate:
  48kHz

- Microphone sensitivity:
  -22 dBFS omnidirectional microphones :contentReference[oaicite:3]{index=3}

- Hardware notes:
  The system consists of two separate boards connected together using a ribbon cable:
  - microphone circular array board
  - Raspberry Pi voice accessory HAT

  The device is intended for embedded systems rather than direct standalone desktop usage. :contentReference[oaicite:4]{index=4}

---

# 5. Main Features

- Six microphone array
- Beamforming
- Multi-channel recording
- Direction of arrival (DoA)
- Smart assistant integration
- Raspberry Pi compatibility
- Echo channel support
- Embedded AI audio workflows

- Feature notes:
  The ReSpeaker 6-Mic Array is designed specifically for voice AI applications. Compared to a standard microphone, the device can better isolate directional speech and improve voice pickup in noisy environments.

  The array supports:
  - Amazon Alexa Voice Service
  - Google Assistant
  - local speech recognition systems

  The system is commonly used in robotics and smart speaker projects. :contentReference[oaicite:5]{index=5}

---

# 6. Exportable Data

## 6.1 Data Types

Available data includes:
- Multi-channel audio recordings
- Raw microphone audio
- Beamformed audio
- Echo reference channels
- Environmental audio
- Voice recordings

---

## 6.2 Time Granularity

- Real-time streaming
- Continuous recording
- Session-based recording

---

## 6.3 Data Availability

- Available during active recording
- Depends on Raspberry Pi configuration and permissions

---

## 6.4 Data Format

Possible formats:
- WAV
- PCM
- Multi-channel audio streams

- Notes:
  The first 6 input channels are microphone channels.
  Additional channels may contain playback echo reference data. :contentReference[oaicite:6]{index=6}

---

# 7. Setup & Workflow

## 7.1 Requirements

Required:
- Raspberry Pi
- MicroSD card
- Power supply
- Ribbon cable connection
- Linux / Raspberry Pi OS

Optional:
- Speaker
- Headphones
- Python
- Whisper
- Vosk

Recommended:
- Raspberry Pi 4
- External powered USB supply

---

## 7.2 Setup Steps

1. Connect microphone array board to voice accessory HAT
2. Attach HAT to Raspberry Pi GPIO header
3. Insert SD card with Raspberry Pi OS
4. Power Raspberry Pi
5. Install required drivers and audio libraries
6. Verify microphone detection

Example Linux command:

```bash
arecord -L
```

Test recording:

```bash
arecord -D plughw:1,0 -f S16_LE -r 16000 -c 8 test.wav
```

---

## 7.3 Daily Usage Workflow

Typical workflow:
1. Power Raspberry Pi
2. Verify microphone array detection
3. Start recording or AI pipeline
4. Process audio stream
5. Save exported recordings
6. Shut down Raspberry Pi safely

- Usage notes:
  Long-term recording sessions should use stable power supplies and proper cooling for Raspberry Pi systems.

---

# 8. Data Export

## 8.1 Manual Export

Possible export methods:
- WAV recording export
- SD card transfer
- SCP / network transfer
- USB drive export

Typical formats:
- WAV
- PCM
- Multi-channel recordings

---

## 8.2 API / Automated Export

Compatible with:
- PyAudio
- ALSA
- Whisper
- Vosk
- Google Assistant SDK
- Alexa Voice Service

Possible workflows:
- Real-time speech recognition
- Embedded AI systems
- Robotics interaction
- Smart speaker pipelines

Developer resources:
[ReSpeaker GitHub Repository](https://github.com/respeaker/seeed-voicecard?utm_source=chatgpt.com)

---

# 9. Additional Software / Environment

Required:
- Raspberry Pi OS
- ALSA audio support

Optional:
- Python
- Audacity
- Whisper
- Vosk
- Home Assistant

Development environment:
- Linux recommended
- Raspberry Pi environment preferred

- Software notes:
  The device is primarily intended for Linux-based embedded systems rather than Windows desktop environments.

  Driver installation and kernel compatibility may vary depending on Raspberry Pi version. :contentReference[oaicite:8]{index=8}

---

# 10. Battery & Maintenance

- Power source:
  Raspberry Pi power supply

- Internal battery:
  None

- Maintenance recommendations:
  - Keep microphones clean
  - Avoid dust accumulation
  - Use stable power supplies
  - Avoid ribbon cable damage
  - Store in anti-static protection when not in use

- Maintenance notes:
  Raspberry Pi cooling may be required during heavy AI workloads.

---

# 11. Troubleshooting

## Device Not Detected

Possible causes:
- Ribbon cable issue
- Incorrect GPIO connection
- Driver installation issue

Possible solutions:
- Reconnect ribbon cable
- Reinstall drivers
- Verify Raspberry Pi GPIO alignment

---

## Recording Errors

Possible causes:
- ALSA configuration issue
- Incorrect sample format
- Driver mismatch

Possible solutions:
- Verify ALSA configuration
- Check supported sample formats
- Restart audio services

- Notes:
  Some users report recording format compatibility issues depending on Linux distribution and Raspberry Pi model. :contentReference[oaicite:9]{index=9}

---

## Noise or Static

Possible causes:
- Power instability
- Electrical interference
- Poor grounding

Possible solutions:
- Use stable power supply
- Reduce nearby electrical interference
- Verify cable connections

---

# 12. Notes

- The device is commonly referred to as:
  - ReSpeaker 6-Mic Array
  - ReSpeaker Circular Array
  - ReSpeaker Voice HAT

- The system is designed primarily for embedded voice AI applications rather than standard desktop audio recording. :contentReference[oaicite:10]{index=10}

- Compared to normal USB microphones, this device is significantly more useful for:
  - robotics
  - smart speakers
  - edge AI systems
  - multi-speaker voice interaction

- DHTS notes:
  This device is useful for:
  - embedded AI projects
  - robotics systems
  - smart room research
  - XR interaction experiments
  - Raspberry Pi voice pipelines
  - environmental audio analysis
