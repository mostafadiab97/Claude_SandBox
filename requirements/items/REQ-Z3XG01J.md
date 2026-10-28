---
id: DEF-4VYB74
type: defect
title: "Defect: tamper detection does not restore error conditions"
status: Draft
priority: High
owner: Y. Saber
parent: INFO-6QFMYN
order: 130
links:
  - type: relates-to
    target: TC-AFD83Z
    confirmed: 16ed29c4b0ef
  - type: relates-to
    target: SYS-ZVPM29
    confirmed: 74f2cdf0b355
---
Found during regression testing of build 2.6.5.

**Observed:** the tamper detection did not detect schedule entries.
**Expected:** The tamper detection shall switch the connection state in under 3 s.

```
ERR 0xd95c at tamper_detection.c:887
```
