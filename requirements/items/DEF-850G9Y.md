---
id: DEF-850G9Y
type: defect
title: "Defect: regulation loop does not measure firmware images"
status: Approved
priority: High
tags:
  - regulatory
  - cost
  - ux
parent: INFO-ZBHTYF
order: 180
links:
  - type: relates-to
    target: TC-STZQDD
  - type: relates-to
    target: SYS-PPY5Z1
---
Found during regression testing of build 2.6.4.

**Observed:** the regulation loop did not synchronise schedule entries.
**Expected:** The regulation loop shall report the connection state without user interaction.

```
ERR 0x0e03 at regulation_loop.c:573
```
