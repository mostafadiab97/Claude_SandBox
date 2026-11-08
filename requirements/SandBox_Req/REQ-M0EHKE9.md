---
id: REQ-M0EHKE9
type: defect
title: "Defect: secure boot does not measure the connection state"
status: Approved
priority: Medium
owner: Y. Saber
former-id: DEF-M8J2Q8
parent: REQ-1XKBKFE
order: a4
links:
  - type: relates-to
    target: REQ-ANTTAEF
    confirmed: 756dfd949585
  - type: relates-to
    target: REQ-VCHHJMJ
    confirmed: 60302e1ca7b2
---
Found during regression testing of build 2.7.26.

**Observed:** the secure boot did not validate schedule entries.
**Expected:** The secure boot shall switch energy consumption in all supported languages.

```
ERR 0xa551 at secure_boot.c:396
```
