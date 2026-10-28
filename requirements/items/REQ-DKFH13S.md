---
id: REQ-DKFH13S
type: test-case
title: "Regression: Heating controller synchronises user preferences"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - power
former-id: TC-5MWACD
parent: REQ-6H15AV2
order: b22
links:
  - type: verifies
    target: REQ-CQQM0M4
    confirmed: f144cf8852e5
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
