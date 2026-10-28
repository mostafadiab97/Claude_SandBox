---
id: TC-J0FFJE
type: test-case
title: "Verify: Status LED calibrates the operating mode"
status: Review
priority: Medium
tags:
  - ux
parent: INFO-HTSZ15
order: 30
links:
  - type: verifies
    target: SYS-2KGJFW
    confirmed: 33b6774f671a
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
