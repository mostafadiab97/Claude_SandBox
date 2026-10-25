---
id: TC-RNAN3V
type: test-case
title: "Verify: Main PCB calibrates the room temperature"
status: Approved
priority: Low
parent: INFO-MACGC3
order: 280
links:
  - type: verifies
    target: SYS-6PYBJD
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
