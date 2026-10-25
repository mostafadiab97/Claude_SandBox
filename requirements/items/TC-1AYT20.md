---
id: TC-1AYT20
type: test-case
title: "Verify: Touch display detects energy consumption"
status: Draft
priority: Low
owner: A. Hassan
tags:
  - regulatory
parent: INFO-HTSZ15
order: 200
links:
  - type: verifies
    target: SYS-3PT4BJ
  - type: verifies
    target: SW-99AAP4
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
