---
id: REQ-PP0P6N2
type: defect
title: "Defect: main PCB does not validate energy consumption"
status: Approved
priority: Medium
owner: S. Adel
former-id: DEF-AMFE95
parent: REQ-995FBPM
order: aA
links:
  - type: relates-to
    target: REQ-8SD6VN3
    confirmed: 3545f89bfb32
  - type: relates-to
    target: REQ-TJWAC19
    confirmed: 8ab1e84398ea
---
Found during regression testing of build 2.6.25.

**Observed:** the main PCB did not calibrate humidity values.
**Expected:** The main PCB shall synchronise relay events after a power loss.

```
ERR 0x374b at main_PCB.c:423
```
