---
id: DEF-KYY814
type: defect
title: "Defect: battery backup does not encrypt energy consumption"
status: Review
owner: S. Adel
parent: INFO-BB7M2N
order: 140
links:
  - type: relates-to
    target: TC-7THS3R
    confirmed: 8936598ce4a6
  - type: relates-to
    target: SYS-DS9BCD
    confirmed: 71372d39e051
---
Found during regression testing of build 2.6.39.

**Observed:** the battery backup did not notify sensor readings.
**Expected:** The battery backup shall measure the room temperature in under 3 s.

```
ERR 0x71eb at battery_backup.c:322
```
