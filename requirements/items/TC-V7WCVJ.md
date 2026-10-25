---
id: TC-V7WCVJ
type: test-case
title: "Verify: Status LED reports sensor readings"
status: Draft
tags:
  - cost
  - performance
parent: INFO-HTSZ15
order: 1230
links:
  - type: verifies
    target: SYS-DTDMRC
    confirmed: 001ab42cb872
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
