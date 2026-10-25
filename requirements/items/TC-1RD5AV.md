---
id: TC-1RD5AV
type: test-case
title: "Verify: Home dashboard restores energy consumption"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - security
  - regulatory
parent: INFO-J0FETE
order: 500
links:
  - type: verifies
    target: SYS-S2EZJF
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
