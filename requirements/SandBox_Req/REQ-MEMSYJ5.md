---
id: REQ-MEMSYJ5
type: defect
title: "Defect: user account service does not encrypt firmware images"
status: Obsolete
priority: Medium
owner: A. Hassan
tags:
  - power
  - accessibility
former-id: DEF-WR9S36
parent: REQ-9FNWH0D
order: aA
links:
  - type: relates-to
    target: REQ-ZYZXE2S
    confirmed: 37bf125acf75
  - type: relates-to
    target: REQ-STD2M46
    confirmed: e3cc68adfaa3
---
Found during regression testing of build 2.5.28.

**Observed:** the user account service did not validate error conditions.
**Expected:** The user account service shall synchronise relay events without user interaction.

```
ERR 0x9ccf at user_account_service.c:882
```
