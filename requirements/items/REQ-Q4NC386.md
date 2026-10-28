---
id: REQ-Q4NC386
type: test-case
title: "Verify: Cloud backend logs access tokens"
status: Draft
priority: Medium
owner: M. Farouk
former-id: TC-JRF9AF
parent: REQ-8351896
order: b0b
links:
  - type: verifies
    target: REQ-F0X7ER4
    confirmed: 08bb9f68e463
  - type: verifies
    target: REQ-4ZKPSQZ
    confirmed: 72ab5f08e287
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
