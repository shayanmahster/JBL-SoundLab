# JBL SoundLab PRO

**Tuned by `shayan`**

A custom Android DSP & Acoustic Equalizer app designed with a JBL-inspired dark/orange interface, Harman Target curve presets, dynamic bass boost, 3D spatializer, and real-time audio session hooking — **no root required**.

---

## Download

- **[Download JBL-SoundLab-PRO-v1.0.apk](./JBL-SoundLab-PRO-v1.0.apk)** (~40.9 MB)

---

## Features

- **System-Wide Dynamic Session Hook:** Uses Android's `AudioPlaybackCallback` and Global Session 0 mix to automatically tune audio from Spotify, YouTube, Telegram, Chrome, and local media players.
- **JBL Acoustic Profiles:**
  - **JBL Signature:** Harman Target curve (deep controlled sub-bass, neutral mids, crisp highs)
  - **Pure Bass Boost:** Heavy low-end punch for EDM, Trap, and Hip-Hop
  - **Club & Spatial:** 3D Surround soundstage + V-shape curve
  - **Vocal & Acoustic:** Forward vocal clarity and controlled bass
  - **Extreme Punch:** High-headroom loudness enhancement
  - **Flat Studio:** Neutral reference response
- **5-Band Graphic Equalizer:** Interactive ±15 dB sliders for hardware frequency bands.
- **Bass Boost & Spatial 3D Controls:** Independent 0–100% intensity sliders.
- **Built-in 808 Sub-Bass Test Beat:** Audition EQ and bass changes directly inside the app.

---

## Compatibility & Installation

- **Supported Devices:** Android 8.0 – Android 16 (tested on Google Pixel, OnePlus 7T / crDroid, and standard AOSP/OEM devices).
- **Root Required?** **No.** Uses standard `android.media.audiofx` APIs.
- **Spotify Tip:** Enable **Device Broadcast Status** inside Spotify Settings for instant session syncing.

### Install via ADB
```bash
adb install -r JBL-SoundLab-PRO-v1.0.apk
```
