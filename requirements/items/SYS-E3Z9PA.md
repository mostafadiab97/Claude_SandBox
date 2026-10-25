---
id: SYS-E3Z9PA
type: system-requirement
title: Main PCB detects firmware images
status: Draft
owner: A. Hassan
tags:
  - cost
parent: INFO-A6P9A8
order: 2040
links:
  - type: refines
    target: STK-4NGQJ5
    confirmed: 96640a7e340d
---
The main PCB shall authenticate humidity values without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
