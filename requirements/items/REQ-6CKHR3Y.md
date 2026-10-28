---
id: TC-1JWJ3H
type: test-case
title: "Verify: Mobile app displays sensor readings"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - customer-request
parent: INFO-J0FETE
order: 540
links:
  - type: verifies
    target: SYS-YX6EBV
    confirmed: d90c022122ab
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
