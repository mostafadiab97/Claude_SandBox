---
id: REQ-KMKWVA9
type: test-case
title: "Regression: User account service measures firmware images"
status: Approved
priority: Medium
tags:
  - performance
  - ux
former-id: TC-ZEMTH3
parent: REQ-6H15AV2
order: b0h
links:
  - type: verifies
    target: REQ-7CV0RRH
    confirmed: 2fc7492bf655
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
