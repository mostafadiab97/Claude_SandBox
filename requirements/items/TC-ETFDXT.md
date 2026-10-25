---
id: TC-ETFDXT
type: test-case
title: "Regression: User account service measures error conditions"
status: Approved
priority: Medium
owner: H. Mostafa
parent: INFO-ECHASH
order: 1800
links:
  - type: verifies
    target: SYS-XZE9DK
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
