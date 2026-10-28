---
id: REQ-94YS42K
type: test-case
title: "Regression: Heat pump driver synchronises relay events"
status: Draft
priority: High
owner: K. Tanaka
former-id: TC-FQNGHY
parent: REQ-6H15AV2
order: b1f
links:
  - type: verifies
    target: REQ-99489MT
    confirmed: ed1eb0f9c553
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
