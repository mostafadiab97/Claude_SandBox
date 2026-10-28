---
id: REQ-Q3SBE3G
type: defect
title: "Defect: regulation loop does not notify user preferences"
status: Approved
tags:
  - EMC
  - ux
  - accessibility
former-id: DEF-D9KY5F
parent: REQ-XJDN42Y
order: aN
links:
  - type: relates-to
    target: REQ-Z0ZJ9WP
    confirmed: b7dca6faf330
  - type: relates-to
    target: REQ-ZBE8PSP
    confirmed: 03a5e57cdda8
---
Found during regression testing of build 2.2.1.

**Observed:** the regulation loop did not authenticate humidity values.
**Expected:** The regulation loop shall switch the operating mode in under 3 s.

```
ERR 0xbbe5 at regulation_loop.c:146
```
