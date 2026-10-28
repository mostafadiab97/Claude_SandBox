---
id: TC-FX10H7
type: test-case
title: "Verify: Status LED reports sensor readings"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-HTSZ15
order: 1190
links:
  - type: verifies
    target: SYS-QT1CFV
    confirmed: ee55a0dd3a84
  - type: verifies
    target: SW-P1PC3F
    confirmed: 55aa95befbc6
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
