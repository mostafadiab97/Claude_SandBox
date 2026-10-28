---
id: REQ-TPRRW8A
type: test-case
title: "Verify: Cloud backend restores the connection state"
status: Draft
priority: High
owner: É. Laurent
tags:
  - release-2.0
  - connectivity
former-id: TC-ZW3JYS
parent: REQ-8351896
order: a4
links:
  - type: verifies
    target: REQ-KWY4YDV
    confirmed: 8d4772f02317
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
