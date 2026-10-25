---
id: TC-XKWTF4
type: test-case
title: "Verify: Touch display logs audit records"
status: Approved
priority: High
tags:
  - release-1.0
  - regulatory
parent: INFO-HTSZ15
order: 1520
links:
  - type: verifies
    target: SYS-6DS2H0
  - type: verifies
    target: SW-DMY4GP
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
