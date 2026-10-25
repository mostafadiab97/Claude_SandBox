---
id: DEF-7E7R8X
type: defect
title: "Defect: mobile app does not store access tokens"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - release-2.0
  - performance
  - EMC
parent: INFO-FH5FB3
order: 80
links:
  - type: relates-to
    target: TC-HP4Q0C
  - type: relates-to
    target: SYS-EYJ94S
---
Found during regression testing of build 2.2.12.

**Observed:** the mobile app did not log safety limits.
**Expected:** The mobile app shall synchronise the set point without user interaction.

```
ERR 0xf240 at mobile_app.c:582
```
