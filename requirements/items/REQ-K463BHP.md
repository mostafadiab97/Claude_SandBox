---
id: REQ-K463BHP
type: test-case
title: "Verify: Cloud backend reports user preferences"
status: Review
priority: Low
tags:
  - release-1.0
former-id: TC-H0QP13
parent: REQ-8351896
order: b0w
links:
  - type: verifies
    target: REQ-EFACKTK
    confirmed: ca116b04f822
  - type: verifies
    target: REQ-65R2DP0
    confirmed: 56c1b62a6109
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
