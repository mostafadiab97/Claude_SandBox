---
id: TC-1V1GBW
type: test-case
title: "Regression: Zigbee radio displays schedule entries"
status: Draft
priority: Medium
parent: INFO-ECHASH
order: 830
links:
  - type: verifies
    target: SYS-ERGMGJ
    confirmed: 4e0d29ca2f08
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
