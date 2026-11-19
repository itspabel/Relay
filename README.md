<div align="center">
  
# Relay

### Stay connected. No internet required.

**A privacy-focused, offline-first communication app for nearby Android
devices.**

[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=flat-square&logo=android&logoColor=white)](#)
[![Connectivity](https://img.shields.io/badge/Connectivity-Bluetooth%20%7C%20Wi--Fi%20%7C%20Wi--Fi%20Direct-35D0B0?style=flat-square)](#)
[![Version](https://img.shields.io/badge/Version-1.0.0-7C9BFF?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-In%20Development-F2B86B?style=flat-square)](#)
</div>

---

## About Relay

# Relay — Offline Peer-to-Peer Communication & File Transfer

**Relay** (`com.pabel.relay`) is an offline-first Android communication, local file sharing, and synchronized media playback application designed to work directly between nearby Android devices without internet access, mobile data, or cloud accounts.

---

## App Description

Relay turns nearby Android phones and tablets into a private, server-free communication and sharing network. After creating a local-only identity during onboarding—complete with a cryptographic Android Keystore fingerprint and no phone number, email, or account sign-up—users can discover nearby Relay peers over Bluetooth, BLE, Wi-Fi Direct, and same-Wi-Fi/hotspot local networks, or pair instantaneously using time-limited single-use QR codes.

Once connected, users can exchange offline messages, manage local voice/video call sessions, transfer multiple files with Relay's built-in file browser, and listen to music or watch videos together in real time over a local network room.

---

## Key Features

### 1. Zero-Account Local Identity & Security
- **Offline Onboarding:** Set up a display name, geometric monogram avatar (or local photo via Android Photo Picker), and local device ID without email, phone number, or cloud login.
- **On-Device Cryptographic Fingerprints:** Generates a local device identity fingerprint backed by Android Keystore (`6-digit` verification code matching on QR confirmation).
- **Ephemeral Single-Use QR Session Tokens:** Pairing and transfer QR codes embed time-limited (`1m` / `2m` / `5m` configurable) single-use tokens that expire automatically after expiry or successful use—never exposing private keys.
- **Trusted Peer Management:** Review, trust, disconnect, or remove paired devices stored locally in Room.

### 2. Multi-Transport Nearby Device Discovery & Diagnostics
- **Multi-Radio Local Discovery:** Searches simultaneously across:
  - **Bluetooth Classic & BLE (with GATT identity exchange)**
  - **Wi-Fi Direct (`WifiP2pManager` peer & DNS-SD service discovery)**
  - **Same Wi-Fi LAN / Mobile Hotspot (NSD mDNS + UDP broadcast/hotspot beacon fallback)**
- **Real-Time Radio & Permission Readiness:** Live indicators for Bluetooth, Wi-Fi/P2P, Location status (on Android 12 and lower), Bluetooth discoverability prompt, and clear per-permission / transport diagnostic messages.
- **No Fake Peers:** Displays only real nearby Relay devices detected over active local radios or QR handshakes.

### 3. In-App QR Pairing & Transfer Connection
- **My QR Pairing Identity & Transfer QR:** Generate live QR cards with countdown timers, configurable expiration (`1m`, `2m`, `5m`), and one-tap regeneration.
- **Built-In Camera QR Scanner:** Requests `CAMERA` permission only when scanning is started, validates Relay QR payloads (rejecting expired, replayed, self-scanned, or malformed codes), and shows target device info + 6-digit security verification code before connecting.
- **Manual IP/Port Fallback:** Advanced manual endpoint entry remains available on the Transfers screen alongside one-scan QR transfer setup.

### 4. Custom Privacy-Respecting File Browser & Transfers
- **No Broad Storage or Folder Permissions:** Selects individual files using Android's supported file picker & MediaStore/SAF workflows—no forced folder permissions or `READ_EXTERNAL_STORAGE`/`MANAGE_EXTERNAL_STORAGE`.
- **Categorized Browsing:** Filter across **All Files**, **Images**, **Videos**, **Audio**, **Documents**, and **Other Files** (including archives such as `.zip`, `.rar`, `.7z`).
- **Rich File Cards & Controls:** Displays thumbnails for images and videos, file type icons, file sizes, modification dates, live search, sorting options, multi-file selection counters, and staged transfer queue.
- **Incoming Receiver & Local Storage:** Toggle local TCP file receiver mode, track transfer progress/status, and save received files cleanly to `Downloads/Relay`.

### 5. Offline Chats & Calls
- **Offline Conversations:** Local peer-to-peer chat conversations and store-and-forward offline message queuing backed by local Room persistence.
- **Local Calls:** Audio and video call history and local session management tied to connected offline peers without internet signaling servers.

### 6. Together Mode (Synced Media Rooms)
- **Host & Join Over Local Wi-Fi / Wi-Fi Direct:** Pick local audio or video media to stream and synchronize playback across nearby Relay devices in a shared local listening or watch room.

### 7. Adaptive Material 3 Interface & Personalization
- **Themes & Responsive Layout:** Supports Dark, Light, and System themes, dynamic Navigation Bar (phones) / Navigation Rail (tablets & wide screens), and edge-to-edge system bar insets.
- **Storage & Diagnostics Settings:** Inspect local Room database, cache, and received file storage sizes, clear temporary cache safely, and review permission statuses.
- **About & Update Check:** Includes developer profile, featured projects, and manual/periodic GitHub release update check (`minSdk 24` / Android 7.0 through `targetSdk 36` / Android 16). 

## Developer

**Tasfiqul Alam Pabel**\
Independent Developer

-   Facebook:
    [@tasfiqulalampabel](https://facebook.com/tasfiqulalampabel)
-   Instagram:
    [@tasfiqul_alam_pabel](https://instagram.com/tasfiqul_alam_pabel)

## Other Projects

### Pockeva

A personal finance management app.

### SirErKhata

An offline tuition and student management app.

## Release Downloads

Release APKs will be published through the project's GitHub Releases
page when available.

The intended release package includes:

-   **Universal APK** --- for compatible Android devices across
    supported ABIs.
-   **ABI-specific APKs** --- separate builds for supported processor
    architectures.

Always download APKs from the official project release page. Verify the
package name and version before installing.

## Important Notes

-   Relay is designed for nearby communication, not communication over
    unlimited distances.
-   Devices must have a supported connection path to communicate.
-   Group calling and synchronized media playback depend on network
    quality and device performance.
-   Bluetooth is not suitable for synchronized video streaming.
-   DRM-protected content from subscription streaming services is not
    intended to be shared through Together Mode.

## License

No open-source license has been specified for this project. Unless a
license is added to the repository, all rights remain with the copyright
holder and reuse or redistribution is not automatically permitted.

------------------------------------------------------------------------

<div align="center">
  
**Relay --- Nearby communication, without the internet.**

Made with care by **Tasfiqul Alam Pabel**

</div>

