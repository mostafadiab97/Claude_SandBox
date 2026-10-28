---
id: REQ-K06NRHQ
type: test-case
title: "Verify: Cloud backend restores the set point"
status: Approved
priority: Low
owner: É. Laurent
former-id: TC-8C1A78
parent: REQ-8351896
order: b1U
links:
  - type: verifies
    target: REQ-H2GK9F4
    confirmed: 7e6cc32b80b3
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
