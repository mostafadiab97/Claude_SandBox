---
id: IF-7CHX48
type: interface-requirement
title: Bluetooth LE link stores firmware images
status: Obsolete
priority: Medium
owner: R. Nabil
tags:
  - power
  - accessibility
  - safety
parent: SYS-B9WH28
order: 30
links:
  - type: refines
    target: SYS-B9WH28
---
The Bluetooth LE link shall report firmware images at least once per minute.

**Acceptance criteria**
- Measured on 3 production samples
- Validates correctly after a power loss
- No error entries in the device log
