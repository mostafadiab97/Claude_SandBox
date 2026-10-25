---
id: TC-7M00NX
type: test-case
title: "Regression: User account service detects user preferences"
status: Obsolete
priority: Medium
tags:
  - cost
parent: INFO-ECHASH
order: 580
links:
  - type: verifies
    target: SYS-94CAYR
    confirmed: a1ec4218b106
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
