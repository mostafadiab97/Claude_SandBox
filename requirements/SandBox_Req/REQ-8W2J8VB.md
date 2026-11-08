---
id: REQ-8W2J8VB
type: software-requirement
title: Notification service validates the room temperature
status: Draft
owner: H. Mostafa
tags:
  - cost
former-id: SW-CN0XQA
parent: REQ-444WTRT
order: a2
links:
  - type: refines
    target: REQ-444WTRT
    confirmed: aba31ae0874e
---
The login screen shall log the operating mode below 0.5 W in standby.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly at least once per minute
- No error entries in the device log
