---
id: DEF-XJ24RB
type: defect
title: "Defect: pairing process does not synchronise schedule entries"
status: Draft
priority: Medium
owner: H. Mostafa
parent: INFO-Y69DRS
order: 10
links:
  - type: relates-to
    target: TC-R3XJAW
    confirmed: 80872881cabf
  - type: relates-to
    target: SYS-DZWWWA
    confirmed: 0999a3b2ce99
---
Found during regression testing of build 2.6.29.

**Observed:** the pairing process did not limit error conditions.
**Expected:** The pairing process shall display the room temperature in all supported languages.

```
ERR 0x88eb at pairing_process.c:855
```
