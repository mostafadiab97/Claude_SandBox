---
id: TC-5TTMCB
type: test-case
title: "Verify: Home dashboard authenticates error conditions"
status: Draft
priority: High
tags:
  - security
parent: INFO-J0FETE
order: 950
links:
  - type: verifies
    target: SYS-GC1TCM
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
