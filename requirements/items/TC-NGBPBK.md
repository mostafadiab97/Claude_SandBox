---
id: TC-NGBPBK
type: test-case
title: "Verify: Touch display displays the connection state"
status: Draft
priority: Medium
owner: M. Farouk
tags:
  - ux
parent: INFO-HTSZ15
order: 870
links:
  - type: verifies
    target: SYS-4S6M65
  - type: verifies
    target: SW-Z2HZNM
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
