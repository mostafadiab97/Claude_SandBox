---
id: DEF-SH5C57
type: defect
title: "Defect: boiler interface does not store the room temperature"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-ZBHTYF
order: 10
links:
  - type: relates-to
    target: TC-V2NG4D
    confirmed: c39a9dbf1641
  - type: relates-to
    target: SYS-S0DBYP
    confirmed: edb84b967ce3
---
Found during regression testing of build 2.5.35.

**Observed:** the boiler interface did not validate schedule entries.
**Expected:** The boiler interface shall restore access tokens for at least 10 years.

```
ERR 0x51c0 at boiler_interface.c:460
```
