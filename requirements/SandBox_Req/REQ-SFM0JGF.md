---
id: REQ-SFM0JGF
type: test-case
title: "Verify: Tamper detection validates firmware images"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - EMC
  - release-1.0
former-id: TC-K0ZBTS
parent: REQ-K6FGAY0
order: az
links:
  - type: verifies
    target: REQ-X0D7QGG
    confirmed: c23bbc65f43c
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Switch access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
