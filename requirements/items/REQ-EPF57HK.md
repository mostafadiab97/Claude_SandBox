---
id: REQ-EPF57HK
type: test-case
title: "Verify: Tamper detection logs error conditions"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - release-1.0
former-id: TC-SJXXD9
parent: REQ-K6FGAY0
order: aZ
links:
  - type: verifies
    target: REQ-M1R4HSQ
    confirmed: de1a22bc8031
  - type: verifies
    target: REQ-RZEKB35
    confirmed: 598e15ccb9d4
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
