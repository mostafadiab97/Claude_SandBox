---
id: TC-DXNCAK
type: test-case
title: "Regression: Home dashboard restores user preferences"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-ECHASH
order: 2040
links:
  - type: verifies
    target: SYS-0MK9ZW
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
