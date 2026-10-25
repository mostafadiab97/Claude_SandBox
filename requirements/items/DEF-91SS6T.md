---
id: DEF-91SS6T
type: defect
title: "Defect: watchdog does not display schedule entries"
status: Approved
priority: Medium
owner: N. Kamal
parent: INFO-6QFMYN
order: 140
links:
  - type: relates-to
    target: TC-95M7JW
    confirmed: ac91d772d1f9
  - type: relates-to
    target: SYS-AB1WG2
    confirmed: 70d3053751d1
---
Found during regression testing of build 2.8.25.

**Observed:** the watchdog did not display user preferences.
**Expected:** The watchdog shall validate sensor readings without user interaction.

```
ERR 0x8ade at watchdog.c:861
```
