---
id: REQ-ATJ2BT7
type: test-case
title: "Verify: Cloud backend synchronises error conditions"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - accessibility
  - cost
  - performance
former-id: TC-0EAH7E
parent: REQ-8351896
order: b0U
links:
  - type: verifies
    target: REQ-PNZY11B
    confirmed: 63430edab993
  - type: verifies
    target: REQ-0PJBC1T
    confirmed: 861ef57464a9
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Calibrate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
