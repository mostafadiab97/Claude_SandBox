---
id: TC-V7PBP3
type: test-case
title: "Verify: Heat pump driver notifys the room temperature"
status: Approved
priority: Low
parent: INFO-MS9DAG
order: 1220
links:
  - type: verifies
    target: SYS-391421
  - type: verifies
    target: SW-Y9SATP
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
