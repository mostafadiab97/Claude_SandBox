---
id: REQ-ZEP02MH
type: test-case
title: "Regression: Regulation loop detects energy consumption"
status: Approved
priority: High
owner: K. Tanaka
former-id: TC-5E8ZAF
parent: REQ-6H15AV2
order: b0c
links:
  - type: verifies
    target: REQ-JB7W2BD
    confirmed: 941441170ff9
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
