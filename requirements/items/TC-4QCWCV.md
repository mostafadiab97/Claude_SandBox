---
id: TC-4QCWCV
type: test-case
title: "Verify: Main PCB authenticates schedule entries"
status: Obsolete
priority: Medium
owner: S. Adel
parent: INFO-MACGC3
order: 340
links:
  - type: verifies
    target: SYS-9BFVNF
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Notify the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
