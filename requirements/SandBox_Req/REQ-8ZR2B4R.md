---
id: REQ-8ZR2B4R
type: test-case
title: "Verify: Tamper detection stores audit records"
status: Draft
owner: N. Kamal
tags:
  - EMC
  - release-1.0
  - connectivity
former-id: TC-VD31W2
parent: REQ-K6FGAY0
order: ad
links:
  - type: verifies
    target: REQ-0JTCYEX
    confirmed: 01ce30983654
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Calibrate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
