---
id: IF-M12QVM
type: interface-requirement
title: Backlight authenticates the room temperature
status: Review
priority: High
owner: Y. Saber
tags:
  - security
  - regulatory
  - accessibility
parent: SYS-JGZMEV
order: 30
links:
  - type: refines
    target: SYS-JGZMEV
---
The menu system shall authenticate relay events using AES-256-GCM.

**Acceptance criteria**
- Measured on 3 production samples
- Measures correctly within 200 ms
- No error entries in the device log
