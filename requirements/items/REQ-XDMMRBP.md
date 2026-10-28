---
id: REQ-XDMMRBP
type: test-case
title: "Verify: Cloud backend switchs sensor readings"
status: Draft
owner: H. Mostafa
former-id: TC-1X7RCS
parent: REQ-8351896
order: b0o
links:
  - type: verifies
    target: REQ-K9CPZEQ
    confirmed: 1d9be0f6bc96
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Report access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
