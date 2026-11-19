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

Relay is an Android communication project designed to help people
connect directly with nearby devices---without relying on cloud
accounts, remote messaging servers, or an internet connection for
everyday communication.

It is being designed around local connectivity technologies, with
privacy, direct communication, and practical offline use at its core.

> **Internet policy:** Messaging, calls, nearby discovery, and local
> file sharing are intended to work over supported nearby connections.
> Internet access is used only for optional tasks such as checking and
> downloading app updates.

## Planned Features

  -----------------------------------------------------------------------
  Feature                             Description
  ----------------------------------- -----------------------------------
  Private messaging                   Exchange messages directly with
                                      nearby users.

  Group chats                         Communicate with multiple connected
                                      devices.

  Audio & video calls                 Make one-to-one and supported group
                                      calls.

  File sharing                        Send and receive files between
                                      nearby devices.

  Voice messages                      Exchange recorded voice messages.

  Nearby discovery                    Find other Relay devices in
                                      connection range.

  Together Mode                       Listen to music and watch local
                                      videos together with synchronized
                                      playback.

  Local history                       Keep conversations and transfer
                                      history on the device.
  -----------------------------------------------------------------------

*Feature availability depends on implementation progress, Android
permissions, device capabilities, and connection conditions. This list
describes the project scope; it does not imply that every feature is
already complete.*

## Connection Methods

Relay is designed to support:

-   **Bluetooth** --- nearby discovery, pairing, messaging, and suitable
    small transfers.
-   **Same Wi-Fi network** --- preferred for higher-speed transfers,
    calls, and media streaming.
-   **Wi-Fi Direct** --- direct device-to-device communication without
    requiring a conventional Wi-Fi router.

The app should select a suitable connection method based on the task and
device capabilities. Real-world connectivity can vary by Android
version, hardware, and network configuration.

## Privacy by Design

Relay's goal is to keep everyday communication local:

-   No account registration for nearby communication.
-   No cloud messaging service.
-   No remote database for conversations.
-   Local conversation and transfer history.
-   Secure device pairing and protected communication.
-   No advertising or tracking by design.

Security features and encryption must be verified in the actual release;
this section describes the project's privacy goals, not an independent
security certification.

## App Information

  Item                      Value
  ------------------------- -------------------
  App name                  Relay
  Android package           `com.pabel.relay`
  Current planned release   `v1.0.0`
  Version code              `100`
  Platform                  Android

## Updates

Relay includes a planned GitHub-based update checker.

When an internet connection is available, the app can check the
project's `update.json` file for a newer version. If an update is
available, the app can show release information and direct users to the
official release download.

The update checker is optional. It does not provide the communication
system or make nearby messaging dependent on the internet.

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

