---
id: REQ-DY7D8CG
type: test-case
title: "Verify: Tamper detection calibrates safety limits"
status: Review
owner: É. Laurent
tags:
  - i18n
former-id: TC-S3NG9W
parent: REQ-K6FGAY0
order: b0b
links:
  - type: verifies
    target: REQ-NH579MT
    confirmed: 2dfa982258c0
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
