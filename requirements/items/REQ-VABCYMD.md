---
id: REQ-VABCYMD
type: test-case
title: "Verify: Status LED reports sensor readings"
status: Draft
tags:
  - cost
  - performance
former-id: TC-V7WCVJ
parent: REQ-Y9VHHKA
order: b0y
links:
  - type: verifies
    target: REQ-0X9SCGY
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
