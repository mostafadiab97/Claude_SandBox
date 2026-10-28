---
id: REQ-R9VW5P1
type: test-case
title: "Verify: Touch display measures the connection state"
status: Draft
priority: High
owner: L. Samir
former-id: TC-DTP8PS
parent: REQ-Y9VHHKA
order: b1H
links:
  - type: verifies
    target: REQ-6F9V39K
    confirmed: 178903f1a8f4
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
