# Capricorn App

<p>
  <a href="https://github.com/aule-org/capricorn-hw"><img src="https://img.shields.io/badge/Hardware-capricorn--hw-1f6feb.svg" alt="Capricorn hardware"></a>
  <a href="https://github.com/aule-org/capricorn-sw"><img src="https://img.shields.io/badge/Software-capricorn--sw-2da44e.svg" alt="Capricorn software"></a>
  <a href="https://github.com/aule-org/capricorn-app"><img src="https://img.shields.io/badge/App-Capricorn-8250df.svg" alt="Capricorn app"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="Apache 2.0"></a>
</p>

(English | [Español](README.es.md))

**Capricorn is the open-source AI tutor.** This repository is the app for the adults around the child: the parent who sets the device up, and anyone the family invites to follow the child's learning.

The device is for the child. The app is for the family. It never becomes a second screen for the child.

## What it does

- **Set up the device.** Connect Capricorn to Wi-Fi over Bluetooth and link it to the family.
- **Follow progress.** What the child practiced, what they now master and what comes next, in plain language.
- **Join a session.** Listen in, or step in as a human tutor, through the same LiveKit room the device uses.
- **Control privacy.** Consent, microphone and session settings, and deleting the child's data, all in one place.

## Status

Planned. The app will start from the one we built and shipped for our earlier device, which already handles Bluetooth Wi-Fi setup in production. Built with Flutter for Android and iOS.

## How the pieces fit

```
capricorn-hw   the device: board, e-ink, audio, enclosure
capricorn-sw   firmware: xiaozhi-esp32 + a LiveKit (WebRTC) transport
capricorn-app  the family app                                        (this repository)
```

## License

Apache License 2.0. See [LICENSE](LICENSE).

---

Made in Lima, Peru by [Aule](https://meetaule.com) · admin@meetaule.com
