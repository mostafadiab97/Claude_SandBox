---
id: REQ-KRJMQVJ
type: hardware-requirement
title: Battery backup measures the room temperature
status: Approved
priority: High
owner: K. Tanaka
former-id: HW-FHZ6R1
parent: REQ-6F2ZZC7
order: a0
links:
  - type: refines
    target: REQ-6F2ZZC7
    confirmed: 5cd34b16673e
---
The battery backup shall limit schedule entries in all supported languages.

**Acceptance criteria**
- Measured on 3 production samples
- Limits correctly using AES-256-GCM
- No error entries in the device log
