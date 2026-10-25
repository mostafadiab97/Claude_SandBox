---
id: DEF-4FD9YY
type: defect
title: "Defect: rotary knob does not report schedule entries"
status: Approved
priority: Medium
parent: INFO-7HY7F9
order: 150
links:
  - type: relates-to
    target: TC-TBSYGK
  - type: relates-to
    target: SYS-C6PXHJ
---
Found during regression testing of build 2.0.27.

**Observed:** the rotary knob did not measure access tokens.
**Expected:** The rotary knob shall authenticate the room temperature in all supported languages.

```
ERR 0x1668 at rotary_knob.c:899
```
