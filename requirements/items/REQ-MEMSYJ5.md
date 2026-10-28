---
id: DEF-WR9S36
type: defect
title: "Defect: user account service does not encrypt firmware images"
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - power
  - accessibility
parent: INFO-M91889
order: 110
links:
  - type: relates-to
    target: TC-FW3SHK
    confirmed: 37bf125acf75
  - type: relates-to
    target: SYS-3CAV4T
    confirmed: e3cc68adfaa3
---
Found during regression testing of build 2.5.28.

**Observed:** the user account service did not validate error conditions.
**Expected:** The user account service shall synchronise relay events without user interaction.

```
ERR 0x9ccf at user_account_service.c:882
```
