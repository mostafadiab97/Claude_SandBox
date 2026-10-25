---
id: DEF-GTHZ98
type: defect
title: "Defect: schedule editor does not notify humidity values"
status: Obsolete
owner: K. Tanaka
parent: INFO-FH5FB3
order: 140
links:
  - type: relates-to
    target: TC-AZDHZP
    confirmed: 602767348f3e
  - type: relates-to
    target: SYS-WZPXT3
    confirmed: 758f34cfcd04
---
Found during regression testing of build 2.7.13.

**Observed:** the schedule editor did not encrypt error conditions.
**Expected:** The schedule editor shall log access tokens within 200 ms.

```
ERR 0x1403 at schedule_editor.c:851
```
