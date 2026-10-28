---
id: REQ-FYRAHPV
type: test-case
title: "Regression: User account service synchronises the operating mode"
status: Draft
priority: High
owner: N. Kamal
former-id: TC-9M50TH
parent: REQ-6H15AV2
order: b1k
links:
  - type: verifies
    target: REQ-J23W5Z5
    confirmed: 2a9e2d07c950
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
