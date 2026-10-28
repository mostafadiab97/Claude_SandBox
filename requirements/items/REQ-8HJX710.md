---
id: REQ-8HJX710
type: system-requirement
title: Rotary knob stores safety limits
status: Approved
priority: High
owner: S. Adel
former-id: SYS-MM8K93
parent: REQ-2ZA2TRZ
order: b01
links:
  - type: refines
    target: REQ-XR7FDXB
    confirmed: 07434b0b5615
  - type: mitigates
    target: REQ-DB7V674
    confirmed: 75f8fe6da08d
---
The rotary knob shall limit firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Stores correctly in under 3 s
- No error entries in the device log
