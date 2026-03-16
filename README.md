# Easy Jam

<img width="480" height="871" alt="image" src="https://github.com/user-attachments/assets/51763515-f3ec-42e3-aea8-52016cdc00ee" />


Stream your phone's audio to multiple devices over WiFi.

**What it does:** Captures system audio and broadcasts it in real-time. Works with Spotify, YouTube, games, anything.

## Quick Start

1. Download **Easy Jam** on the [Play Store](https://play.google.com/store/apps/details?id=com.easyjam.app)
2. Hit "Share Audio" and select "Entire screen"
3. Other devices scan the QR code
4. They hit play, audio streams instantly

No pairing. No cables. Just works.

## Network Setup

Put all devices on the same WiFi. Or create a hotspot from the host phone.
Clients connect via browser, no app needed.

## Technical Details

**Audio:** 48kHz stereo PCM, captured via MediaProjection  
**Transport:** WebSocket binary  
**Latency:** 50-100ms depending on WiFi quality (still working on getting a perfect sync)
**Server:** Embedded NanoHTTPD

**Requirements:**
- Android 10+ for host
- A Browser for clients
- A Wifi or Hotspot connexion

## Why This Exists

Bluetooth audio doesn't work for multi-device setups. This is free, easy to use, plug and play.

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat&logo=socketdotio&logoColor=white)
![NanoHTTPD](https://img.shields.io/badge/NanoHTTPD-grey?style=flat)
