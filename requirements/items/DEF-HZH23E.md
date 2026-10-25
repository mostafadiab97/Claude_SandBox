---
id: DEF-HZH23E
type: defect
title: "Defect: enclosure does not validate safety limits"
status: Review
priority: High
owner: H. Mostafa
tags:
  - i18n
  - power
  - release-2.0
parent: INFO-BB7M2N
order: 20
links:
  - type: relates-to
    target: TC-GWEA2X
  - type: relates-to
    target: SYS-EC99RK
---
Found during regression testing of build 2.1.25.

**Observed:** the enclosure did not log error conditions.
**Expected:** The enclosure shall report the connection state below 0.5 W in standby.

```
ERR 0x70de at enclosure.c:193
```
