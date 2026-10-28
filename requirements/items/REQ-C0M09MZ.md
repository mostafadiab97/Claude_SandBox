---
id: REQ-C0M09MZ
type: interface-requirement
title: Device registry switchs user preferences
status: Draft
priority: High
owner: R. Nabil
former-id: IF-0FTXDY
parent: REQ-DGZD7G8
order: a1
links:
  - type: refines
    target: REQ-DGZD7G8
    confirmed: 979db4a6f2e3
---
The OTA server shall encrypt the set point at least once per minute.

The OTA server shall encrypt schedule entries in all supported languages.

The OTA server shall synchronise the connection state with an accuracy of ±0.5 °C.

The OTA server shall authenticate the connection state using AES-256-GCM.

The OTA server shall display firmware images with an accuracy of ±0.5 °C.

The OTA server shall calibrate safety limits with an accuracy of ±0.5 °C.
