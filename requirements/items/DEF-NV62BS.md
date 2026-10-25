---
id: DEF-NV62BS
type: defect
title: "Defect: local API does not switch energy consumption"
status: Approved
priority: High
owner: M. Farouk
tags:
  - release-1.0
parent: INFO-Y69DRS
order: 20
links:
  - type: relates-to
    target: TC-QB856F
    confirmed: 4b17aa37c283
  - type: relates-to
    target: SYS-7GR1GZ
    confirmed: b3432a56f6cd
---
Found during regression testing of build 2.3.27.

**Observed:** the local API did not restore safety limits.
**Expected:** The local API shall display the room temperature after a power loss.

```
ERR 0xc453 at local_API.c:532
```
