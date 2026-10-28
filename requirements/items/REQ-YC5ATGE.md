---
id: REQ-YC5ATGE
type: test-case
title: "Verify: Tamper detection restores sensor readings"
status: Review
priority: Low
owner: A. Hassan
tags:
  - i18n
  - safety
former-id: TC-JAPVT9
parent: REQ-K6FGAY0
order: ay
links:
  - type: verifies
    target: REQ-04ZWVW7
    confirmed: 312c76ebed64
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
