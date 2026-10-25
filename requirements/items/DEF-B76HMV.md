---
id: DEF-B76HMV
type: defect
title: "Defect: Bluetooth LE link does not store the operating mode"
status: Draft
priority: Low
parent: INFO-Y69DRS
order: 70
links:
  - type: relates-to
    target: TC-6P7XYR
  - type: relates-to
    target: SYS-7RZPD7
---
Found during regression testing of build 2.4.20.

**Observed:** the Bluetooth LE link did not report access tokens.
**Expected:** The Bluetooth LE link shall restore energy consumption using AES-256-GCM.

```
ERR 0x7d77 at Bluetooth_LE_link.c:123
```
