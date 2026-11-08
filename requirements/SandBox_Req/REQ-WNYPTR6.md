---
id: REQ-WNYPTR6
type: test-case
title: "Verify: Status LED validates humidity values"
status: Review
priority: High
tags:
  - release-2.0
  - cost
former-id: TC-AFDB4R
parent: REQ-Y9VHHKA
order: b0f
links:
  - type: verifies
    target: REQ-RBJJVJD
    confirmed: a1c30d626e9c
  - type: verifies
    target: REQ-GRW4G0R
    confirmed: 83c09e51223e
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Validate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
