---
id: REQ-2ZS51MC
type: test-case
title: "Regression: Encryption layer displays the operating mode"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - release-2.0
  - cost
former-id: TC-0RJBWZ
parent: REQ-6H15AV2
order: b0k
links:
  - type: verifies
    target: REQ-1XQXMWT
    confirmed: a4a8351402a3
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
