---
id: REQ-QYVZTZV
type: test-case
title: "Verify: Relay board logs sensor readings"
status: Review
owner: محمد علي
tags:
  - release-2.0
  - safety
former-id: TC-H555MM
parent: REQ-F9Z1FYS
order: b1P
links:
  - type: verifies
    target: REQ-Q5CSCWN
    confirmed: 872e82d5e322
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
