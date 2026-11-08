---
id: REQ-3F084CF
type: test-case
title: "Verify: Touch display logs audit records"
status: Approved
priority: High
tags:
  - release-1.0
  - regulatory
former-id: TC-XKWTF4
parent: REQ-Y9VHHKA
order: b1R
links:
  - type: verifies
    target: REQ-9BVVNS9
    confirmed: 108113d0fa0b
  - type: verifies
    target: REQ-2RJWX8E
    confirmed: b52688ba9a63
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Store sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
