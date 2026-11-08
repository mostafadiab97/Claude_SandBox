---
id: REQ-12W7RRB
type: defect
title: "Defect: schedule editor does not notify humidity values"
status: Obsolete
owner: K. Tanaka
former-id: DEF-GTHZ98
parent: REQ-MWRPGWA
order: aD
links:
  - type: relates-to
    target: REQ-WXZHS74
    confirmed: 602767348f3e
  - type: relates-to
    target: REQ-GMRFA4Q
    confirmed: 758f34cfcd04
---
Found during regression testing of build 2.7.13.

**Observed:** the schedule editor did not encrypt error conditions.
**Expected:** The schedule editor shall log access tokens within 200 ms.

```
ERR 0x1403 at schedule_editor.c:851
```
