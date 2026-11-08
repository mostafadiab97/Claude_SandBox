---
id: REQ-2SX6B7S
type: test-case
title: "Regression: Bluetooth LE link authenticates error conditions"
status: Draft
priority: High
owner: محمد علي
tags:
  - security
  - cost
former-id: TC-AWDDCE
parent: REQ-6H15AV2
order: b0N
links:
  - type: verifies
    target: REQ-4JV3MM5
    confirmed: aaffd1e53d20
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
