---
id: REQ-Q7VJJ9Q
type: test-case
title: "Regression: Status LED validates humidity values"
status: Obsolete
priority: Medium
tags:
  - accessibility
former-id: TC-3BC647
parent: REQ-6H15AV2
order: b05
links:
  - type: verifies
    target: REQ-RBJJVJD
    confirmed: a1c30d626e9c
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
