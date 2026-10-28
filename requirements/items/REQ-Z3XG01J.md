---
id: REQ-Z3XG01J
type: defect
title: "Defect: tamper detection does not restore error conditions"
status: Draft
priority: High
owner: Y. Saber
former-id: DEF-4VYB74
parent: REQ-1XKBKFE
order: aC
links:
  - type: relates-to
    target: REQ-44BJ0JK
    confirmed: 16ed29c4b0ef
  - type: relates-to
    target: REQ-6ADPEP5
    confirmed: 74f2cdf0b355
---
Found during regression testing of build 2.6.5.

**Observed:** the tamper detection did not detect schedule entries.
**Expected:** The tamper detection shall switch the connection state in under 3 s.

```
ERR 0xd95c at tamper_detection.c:887
```
