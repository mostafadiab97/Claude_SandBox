---
id: REQ-CZCHJD3
type: test-case
title: "Verify: Status LED measures error conditions"
status: Approved
priority: High
owner: M. Farouk
former-id: TC-8JWZV1
parent: REQ-Y9VHHKA
order: b0K
links:
  - type: verifies
    target: REQ-WRWV27H
    confirmed: dafb2a2d5621
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Switch the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
