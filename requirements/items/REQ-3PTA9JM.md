---
id: TC-A61630
type: test-case
title: "Regression: Zone valve calibrates relay events"
status: Review
priority: High
owner: S. Adel
parent: INFO-ECHASH
order: 1150
links:
  - type: verifies
    target: SYS-8Q3CHA
    confirmed: bba9c1adc60e
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
