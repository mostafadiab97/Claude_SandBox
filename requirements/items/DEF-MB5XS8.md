---
id: DEF-MB5XS8
type: defect
title: "Defect: regulation loop does not authenticate relay events"
status: Review
priority: High
owner: L. Samir
tags:
  - performance
  - i18n
parent: INFO-ZBHTYF
order: 110
links:
  - type: relates-to
    target: TC-71Q4M2
  - type: relates-to
    target: SYS-XW4JM5
---
Found during regression testing of build 2.0.35.

**Observed:** the regulation loop did not log error conditions.
**Expected:** The regulation loop shall encrypt firmware images in all supported languages.

```
ERR 0x87ec at regulation_loop.c:448
```
