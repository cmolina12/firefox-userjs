# Firefox user.js Configuration

This repository contains my customized `user.js` file for Firefox, based on the [arkenfox/user.js](https://github.com/arkenfox/user.js) privacy and security hardening project.

## 🔒 Goals

- Minimize browser fingerprinting
- Increase privacy & anonymity
- Block common tracking vectors
- Retain reasonable usability

## 🧪 Notes

- Tested on:
  - Firefox `v140.0` on **macOS 14 Sonoma**
  - Firefox `v140.0` on **Linux Mint Cinnamon (latest release)**
- Using `resistFingerprinting = true`
- Timezone spoofed to `Atlantic/Reykjavik`
- Canvas and WebGL randomized

## 📄 user.js Overview

This config modifies Firefox behavior via `user.js`, placed in the profile directory. It includes:

- Arkenfox defaults
- Custom fingerprinting countermeasures
- Personal usability/privacy balance tweaks

## ⚠️ Disclaimer

This configuration is tailored for personal use and may degrade functionality on some websites. Review and adapt for your own needs.
