---
id: REQ-YPMJX9G
type: system-requirement
title: Main PCB detects firmware images
status: Draft
owner: A. Hassan
tags:
  - cost
former-id: SYS-E3Z9PA
parent: REQ-CMCS31A
order: b2H
links:
  - type: refines
    target: REQ-4H1F9N3
    confirmed: 96640a7e340d
---
The main PCB shall authenticate humidity values without user interaction.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
