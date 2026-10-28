---
id: REQ-9X0X3N3
type: test-case
title: "Regression: Login screen synchronises firmware images"
status: Draft
priority: High
owner: N. Kamal
tags:
  - cost
former-id: TC-ZY3099
parent: REQ-6H15AV2
order: b0d
links:
  - type: verifies
    target: REQ-0Z7H5M4
    confirmed: 4a4496e229e3
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
