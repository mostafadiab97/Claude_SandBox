---
id: DEF-M8J2Q8
type: defect
title: "Defect: secure boot does not measure the connection state"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-6QFMYN
order: 50
links:
  - type: relates-to
    target: TC-10Z2PT
  - type: relates-to
    target: SYS-8XZZQ8
---
Found during regression testing of build 2.7.26.

**Observed:** the secure boot did not validate schedule entries.
**Expected:** The secure boot shall switch energy consumption in all supported languages.

```
ERR 0xa551 at secure_boot.c:396
```
