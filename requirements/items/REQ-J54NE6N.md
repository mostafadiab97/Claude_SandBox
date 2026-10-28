---
id: REQ-J54NE6N
type: test-case
title: "Verify: Heat pump driver restores sensor readings"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - release-2.0
  - ux
former-id: TC-0VER7R
parent: REQ-XGWSK2K
order: aK
links:
  - type: verifies
    target: REQ-GR9AKS7
    confirmed: 773f6956359c
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Validate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
