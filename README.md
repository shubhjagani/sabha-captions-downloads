# Sabha Captions for Mac

Live Gujarati-to-English or English-to-Gujarati captions from a microphone, Dante feed, or audio playing in other Mac apps.

**[Download the Mac installer (0.2.18)](https://github.com/shubhjagani/sabha-captions-downloads/releases/download/v0.2.18/Sabha-Captions-0.2.18-arm64.dmg)** · [Latest release](https://github.com/shubhjagani/sabha-captions-downloads/releases/latest)

No GitHub account is required to download. This repository contains installers and installation instructions.

## Requirements

- Apple Silicon Mac (M1 or later), macOS 13 or later.
- Internet access for transcription and translation.

## Install

1. Download and open the DMG, then drag **Sabha Captions** into **Applications**.
2. Open Sabha Captions from Applications.
3. If system audio access is missing, the app opens System Settings and shows a small drag row. Drag the entire row into the upper **Screen & System Audio Recording** list, enable Sabha Captions, then choose **Restart & check**.
4. Choose an audio input and click **Start captions**. Choose **System audio** to caption YouTube, music, or other apps. Microphone access is handled in the main audio input controls.

The app is Developer ID signed as **Pause Inc** and notarized by Apple. It requires no separate Node.js installation or virtual audio driver for system audio.

The installer includes the configured shared Soniox project key; no key entry is required. Caption usage is billed to the shared project. A key already saved on your Mac takes precedence.

## Automatic updates

Version 0.2.18 keeps completed caption rows stable as new translation chunks arrive and adds automatic updates. The app checks shortly after launch and every six hours, downloads stable updates in the background, and installs them when you quit normally. It does not restart during a live caption session. Use **Sabha Captions → Check for Updates…** for a manual check or update status.

If you have version 0.2.17 or earlier, install this release manually once to enable future automatic updates. Keep the app in Applications.

[Release details and file checksum](https://github.com/shubhjagani/sabha-captions-downloads/releases/tag/v0.2.18)
