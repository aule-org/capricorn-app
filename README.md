# Aule App

<p>
  <a href="https://github.com/meet-aule/aule-hw"><img src="https://img.shields.io/badge/Hardware-aule--hw-1f6feb.svg" alt="Aule hardware"></a>
  <a href="https://github.com/meet-aule/aule-fw"><img src="https://img.shields.io/badge/Firmware-aule--fw-2da44e.svg" alt="Aule firmware"></a>
  <a href="https://github.com/meet-aule/aule-sw"><img src="https://img.shields.io/badge/Server-aule--sw-d97706.svg" alt="Aule server"></a>
  <a href="https://github.com/meet-aule/aule-app"><img src="https://img.shields.io/badge/App-Aule-8250df.svg" alt="Aule app"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="Apache 2.0"></a>
</p>

(English | [Español](README.es.md))

**Aule is the open-source AI tutor.** This repository is the app for the adults around the child: the parent who sets the device up, and anyone the family invites to follow the child's learning.

The device is for the child. The app is for the family. It never becomes a second screen for the child.

## What it does

- **Set up the device.** Connect Aule to Wi-Fi over Bluetooth and link it to the family.
- **Follow progress.** What the child practiced, what they now master and what comes next, in plain language.
- **Join a session.** Listen in, or step in as a human tutor, through the same LiveKit room the device uses.
- **Control privacy.** Consent, microphone and session settings, and deleting the child's data, all in one place.

## Status

Planned. The app will start from the one we built and shipped for our earlier device, which already handles Bluetooth Wi-Fi setup in production. Built with Flutter for Android and iOS.

## How the pieces fit

```
aule-hw   the device: board, e-ink, audio, enclosure
aule-fw   firmware: xiaozhi-esp32 + a LiveKit (WebRTC) transport
aule-sw   central server: voice tutor, devices, family API
aule-app  the family app                                        (this repository)
```

## License

Apache License 2.0. See [LICENSE](LICENSE).

---

Made in Lima, Peru by [Aule](https://meetaule.com) · admin@meetaule.com
