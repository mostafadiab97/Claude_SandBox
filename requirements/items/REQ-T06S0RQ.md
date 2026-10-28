---
id: TC-MG81PS
type: test-case
title: "Verify: Main PCB detects the connection state"
status: Draft
priority: Low
owner: محمد علي
tags:
  - safety
  - release-2.0
parent: INFO-MACGC3
order: 590
links:
  - type: verifies
    target: SYS-1NBRAQ
    confirmed: e3d201ead13c
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Synchronise access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
