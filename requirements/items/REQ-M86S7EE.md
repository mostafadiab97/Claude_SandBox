---
id: REQ-M86S7EE
type: test-case
title: "Verify: Heat pump driver limits the connection state"
status: Draft
priority: High
owner: محمد علي
tags:
  - performance
  - safety
  - release-2.0
former-id: TC-QXD4C7
parent: REQ-XGWSK2K
order: b0G
links:
  - type: verifies
    target: REQ-CSQ5WDR
    confirmed: 0bcec31c69de
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
