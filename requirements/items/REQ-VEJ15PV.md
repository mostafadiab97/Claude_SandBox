---
id: REQ-VEJ15PV
type: test-case
title: "Verify: Cloud backend limits sensor readings"
status: Review
priority: Medium
tags:
  - ux
former-id: TC-GK64J7
parent: REQ-8351896
order: b11
links:
  - type: verifies
    target: REQ-A8A09WQ
    confirmed: 908f575295da
  - type: verifies
    target: REQ-1ZRQKD6
    confirmed: 87117a978d16
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
