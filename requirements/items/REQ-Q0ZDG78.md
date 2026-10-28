---
id: REQ-Q0ZDG78
type: defect
title: "Defect: secure boot does not display humidity values"
status: Draft
priority: Low
owner: A. Hassan
tags:
  - safety
  - power
former-id: DEF-KSXW1A
parent: REQ-1XKBKFE
order: a1
links:
  - type: relates-to
    target: REQ-8NGVP88
    confirmed: 60cd3bff904f
  - type: relates-to
    target: REQ-6PB57PX
    confirmed: 3dd7a8ccfac1
---
Found during regression testing of build 2.1.19.

**Observed:** the secure boot did not encrypt error conditions.
**Expected:** The secure boot shall restore error conditions for at least 10 years.

```
ERR 0xc752 at secure_boot.c:451
```
