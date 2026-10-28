---
id: REQ-F6NMZTT
type: defect
title: "Defect: regulation loop does not measure firmware images"
status: Approved
priority: High
tags:
  - regulatory
  - cost
  - ux
former-id: DEF-850G9Y
parent: REQ-XJDN42Y
order: aH
links:
  - type: relates-to
    target: REQ-C1VTA86
    confirmed: d5de4e6a038f
  - type: relates-to
    target: REQ-ZM76EGY
    confirmed: 0c11557d1e86
---
Found during regression testing of build 2.6.4.

**Observed:** the regulation loop did not synchronise schedule entries.
**Expected:** The regulation loop shall report the connection state without user interaction.

```
ERR 0x0e03 at regulation_loop.c:573
```
