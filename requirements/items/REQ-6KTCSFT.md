---
id: REQ-6KTCSFT
type: test-case
title: "Regression: Backlight displays firmware images"
status: Draft
priority: High
owner: J. Müller
former-id: TC-3ZNJYK
parent: REQ-6H15AV2
order: b1d
links:
  - type: verifies
    target: REQ-96F7GMN
    confirmed: 4ce801427d87
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
