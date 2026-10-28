---
id: REQ-J7EHETS
type: test-case
title: "Verify: Cloud backend detects the set point"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - ux
  - regulatory
former-id: TC-DXG9A2
parent: REQ-8351896
order: b0j
links:
  - type: verifies
    target: REQ-E0XKBA1
    confirmed: 9d3e4fe37fb5
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Notify audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
