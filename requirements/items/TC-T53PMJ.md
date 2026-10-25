---
id: TC-T53PMJ
type: test-case
title: "Verify: Touch display calibrates the room temperature"
status: Obsolete
priority: Medium
owner: L. Samir
parent: INFO-HTSZ15
order: 1440
links:
  - type: verifies
    target: SYS-9W9NZD
    confirmed: 4875c522f62f
  - type: verifies
    target: SW-BERKW5
    confirmed: 4ff3c09d3986
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
