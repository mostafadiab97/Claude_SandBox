---
id: REQ-E9F7GZP
type: defect
title: "Defect: mobile app does not store access tokens"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - release-2.0
  - performance
  - EMC
former-id: DEF-7E7R8X
parent: REQ-MWRPGWA
order: a7
links:
  - type: relates-to
    target: REQ-93F2KMB
    confirmed: 667d311c484c
  - type: relates-to
    target: REQ-Z957H2Y
    confirmed: 68e2cd729db2
---
Found during regression testing of build 2.2.12.

**Observed:** the mobile app did not log safety limits.
**Expected:** The mobile app shall synchronise the set point without user interaction.

```
ERR 0xf240 at mobile_app.c:582
```
