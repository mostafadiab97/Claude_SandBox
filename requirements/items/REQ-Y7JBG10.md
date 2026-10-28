---
id: REQ-Y7JBG10
type: defect
title: "Defect: pairing process does not synchronise schedule entries"
status: Draft
priority: Medium
owner: H. Mostafa
former-id: DEF-XJ24RB
parent: REQ-YW554H8
order: a0
links:
  - type: relates-to
    target: REQ-GCYP2SH
    confirmed: 80872881cabf
  - type: relates-to
    target: REQ-BWJ3AFX
    confirmed: 0999a3b2ce99
---
Found during regression testing of build 2.6.29.

**Observed:** the pairing process did not limit error conditions.
**Expected:** The pairing process shall display the room temperature in all supported languages.

```
ERR 0x88eb at pairing_process.c:855
```
