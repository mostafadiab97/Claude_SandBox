---
id: TC-4HXF1C
type: test-case
title: "Regression: OTA server reports the set point"
status: Approved
priority: Low
owner: S. Adel
parent: INFO-ECHASH
order: 2170
links:
  - type: verifies
    target: SYS-EQ67JM
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
