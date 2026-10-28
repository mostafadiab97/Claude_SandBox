---
id: REQ-80NCSTV
type: defect
title: "Defect: battery backup does not encrypt energy consumption"
status: Review
owner: S. Adel
former-id: DEF-KYY814
parent: REQ-995FBPM
order: aD
links:
  - type: relates-to
    target: REQ-SD5ZA8M
    confirmed: 8936598ce4a6
  - type: relates-to
    target: REQ-R9KTZAB
    confirmed: 71372d39e051
---
Found during regression testing of build 2.6.39.

**Observed:** the battery backup did not notify sensor readings.
**Expected:** The battery backup shall measure the room temperature in under 3 s.

```
ERR 0x71eb at battery_backup.c:322
```
