---
id: DEF-KBEXZF
type: defect
title: "Defect: backlight does not restore the operating mode"
status: Approved
owner: R. Nabil
tags:
  - EMC
parent: INFO-7HY7F9
order: 70
links:
  - type: relates-to
    target: TC-9Q2PAR
  - type: relates-to
    target: SYS-63GREP
---
Found during regression testing of build 2.6.8.

**Observed:** the backlight did not limit energy consumption.
**Expected:** The backlight shall authenticate access tokens without user interaction.

```
ERR 0xe792 at backlight.c:417
```
