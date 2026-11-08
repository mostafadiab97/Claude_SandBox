---
id: REQ-QDSRMQM
type: defect
title: "Defect: regulation loop does not authenticate relay events"
status: Review
priority: High
owner: L. Samir
tags:
  - performance
  - i18n
former-id: DEF-MB5XS8
parent: REQ-XJDN42Y
order: aA
links:
  - type: relates-to
    target: REQ-PJQ7QHW
    confirmed: 5e1632b66215
  - type: relates-to
    target: REQ-055JC9M
    confirmed: ed6d4a00a62b
---
Found during regression testing of build 2.0.35.

**Observed:** the regulation loop did not log error conditions.
**Expected:** The regulation loop shall encrypt firmware images in all supported languages.

```
ERR 0x87ec at regulation_loop.c:448
```
