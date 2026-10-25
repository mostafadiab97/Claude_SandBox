---
id: TC-TQ0KN5
type: test-case
title: "Verify: Cloud backend switchs error conditions"
status: Review
tags:
  - ux
  - cost
  - customer-request
parent: INFO-7P4D8D
order: 1050
links:
  - type: verifies
    target: SYS-G0JBM8
  - type: verifies
    target: SW-1Z9X0M
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
