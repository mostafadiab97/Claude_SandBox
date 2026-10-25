---
id: TC-TT6TVK
type: test-case
title: "Verify: Enclosure measures the operating mode"
status: Obsolete
priority: Low
owner: L. Samir
parent: INFO-MACGC3
order: 550
links:
  - type: verifies
    target: SYS-RWYDHZ
  - type: verifies
    target: SW-MEDA9V
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Calibrate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
