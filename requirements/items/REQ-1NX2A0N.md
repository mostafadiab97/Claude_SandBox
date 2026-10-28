---
id: REQ-1NX2A0N
type: test-case
title: "Verify: Touch display stores audit records"
status: Review
owner: K. Tanaka
former-id: TC-2FCJ24
parent: REQ-Y9VHHKA
order: b1E
links:
  - type: verifies
    target: REQ-Y9PF6ZF
    confirmed: 0a633adec0ec
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
