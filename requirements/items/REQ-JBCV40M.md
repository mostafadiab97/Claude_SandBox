---
id: TC-FA0Y3E
type: test-case
title: "Regression: Zone valve displays the operating mode"
status: Draft
priority: Low
owner: محمد علي
tags:
  - power
parent: INFO-ECHASH
order: 2100
links:
  - type: verifies
    target: SYS-ZQSPB3
    confirmed: c8c012d7096b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
