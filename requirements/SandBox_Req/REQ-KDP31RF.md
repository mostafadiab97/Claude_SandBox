---
id: REQ-KDP31RF
type: test-case
title: "Verify: Home dashboard detects sensor readings"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - release-2.0
  - performance
  - release-1.0
former-id: TC-WJN1D0
parent: REQ-WR5ZJN9
order: aR
links:
  - type: verifies
    target: REQ-SWMBTEW
    confirmed: 68b37681cbe6
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Log humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
