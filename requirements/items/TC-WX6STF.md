---
id: TC-WX6STF
type: test-case
title: "Regression: Mobile app encrypts relay events"
status: Review
priority: High
owner: A. Hassan
tags:
  - cost
parent: INFO-ECHASH
order: 780
links:
  - type: verifies
    target: SYS-FBM4B7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
