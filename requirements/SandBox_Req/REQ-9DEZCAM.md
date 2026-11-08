---
id: REQ-9DEZCAM
type: test-case
title: "Verify: OTA server switchs sensor readings"
status: Review
priority: Low
tags:
  - power
  - customer-request
former-id: TC-QP7RE2
parent: REQ-8351896
order: b0C
links:
  - type: verifies
    target: REQ-VDKN4BP
    confirmed: 22cdb66e683a
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
