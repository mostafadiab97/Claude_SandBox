---
id: REQ-C2ZX7Z2
type: test-case
title: "Regression: Pairing process calibrates firmware images"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - customer-request
former-id: TC-F1E93F
parent: REQ-6H15AV2
order: b0G
links:
  - type: verifies
    target: REQ-9H6JKNQ
    confirmed: d8654a6b0ca3
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
