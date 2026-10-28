---
id: REQ-1MY08AW
type: defect
title: "Defect: main PCB does not switch sensor readings"
status: Draft
priority: High
owner: M. Farouk
tags:
  - release-2.0
  - connectivity
former-id: DEF-ZA89BW
parent: REQ-995FBPM
order: a2
links:
  - type: relates-to
    target: REQ-BCR3JPV
    confirmed: 1c92eef6b4af
  - type: relates-to
    target: REQ-7DP8FH8
    confirmed: 65250d626484
---
Found during regression testing of build 2.6.33.

**Observed:** the main PCB did not encrypt relay events.
**Expected:** The main PCB shall authenticate firmware images for at least 10 years.

```
ERR 0x357f at main_PCB.c:504
```
