---
id: TC-MZQ4E3
type: test-case
title: "Verify: Touch display reports the operating mode"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - performance
  - security
parent: INFO-HTSZ15
order: 1330
links:
  - type: verifies
    target: SYS-21HNZD
    confirmed: a99c46ec97b8
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
