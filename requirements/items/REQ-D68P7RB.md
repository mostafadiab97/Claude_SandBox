---
id: REQ-D68P7RB
type: test-case
title: "Regression: Regulation loop synchronises audit records"
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - performance
former-id: TC-T245VV
parent: REQ-6H15AV2
order: b0p
links:
  - type: verifies
    target: REQ-ACEDPGP
    confirmed: 52219f23d7ef
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
