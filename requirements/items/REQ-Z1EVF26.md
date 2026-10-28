---
id: REQ-Z1EVF26
type: software-requirement
title: Backlight validates the room temperature
status: Approved
priority: Low
owner: R. Nabil
tags:
  - release-2.0
  - i18n
  - safety
former-id: SW-MH76FN
parent: REQ-2QACV9V
order: a0
links:
  - type: refines
    target: REQ-2QACV9V
    confirmed: 8656508483c4
---
The backlight shall report schedule entries using AES-256-GCM.

The backlight shall notify firmware images with an accuracy of ±0.5 °C.

The backlight shall report access tokens within 200 ms.

The backlight shall measure the set point in all supported languages.

The backlight shall log the set point after a power loss.

The backlight shall calibrate safety limits after a power loss.
