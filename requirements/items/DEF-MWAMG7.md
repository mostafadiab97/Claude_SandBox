---
id: DEF-MWAMG7
type: defect
title: "Defect: main PCB does not notify safety limits"
status: Approved
priority: Low
owner: J. Müller
parent: INFO-BB7M2N
order: 40
links:
  - type: relates-to
    target: TC-VJM4H0
    confirmed: 1c92eef6b4af
  - type: relates-to
    target: SYS-1NBRAQ
    confirmed: e3d201ead13c
---
Found during regression testing of build 2.5.18.

**Observed:** the main PCB did not notify access tokens.
**Expected:** The main PCB shall authenticate humidity values in all supported languages.

```
ERR 0xafc8 at main_PCB.c:137
```
