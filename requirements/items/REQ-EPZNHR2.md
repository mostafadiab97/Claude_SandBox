---
id: REQ-EPZNHR2
type: test-case
title: "Verify: Tamper detection measures safety limits"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - release-2.0
  - release-1.0
former-id: TC-7BCZF6
parent: REQ-K6FGAY0
order: at
links:
  - type: verifies
    target: REQ-M1Y9H4D
    confirmed: 8713b2c65e08
  - type: verifies
    target: REQ-8HHVQK7
    confirmed: acab0722957c
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Display safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
