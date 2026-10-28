---
id: REQ-4CBY78D
type: system-requirement
title: Main PCB stores sensor readings
status: Review
priority: Medium
owner: H. Mostafa
tags:
  - cost
former-id: SYS-5C94DF
parent: REQ-CMCS31A
order: b0s
links:
  - type: refines
    target: REQ-4H1F9N3
    confirmed: 96640a7e340d
  - type: mitigates
    target: REQ-VDC6H37
    confirmed: 2c8e05c3e368
---
The main PCB shall notify energy consumption in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Displays correctly for at least 10 years
- No error entries in the device log
