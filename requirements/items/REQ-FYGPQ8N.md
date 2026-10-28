---
id: REQ-FYGPQ8N
type: test-case
title: "Verify: Home dashboard limits error conditions"
status: Approved
owner: L. Samir
tags:
  - performance
  - safety
  - accessibility
former-id: TC-ZHW1Q3
parent: REQ-WR5ZJN9
order: b10
links:
  - type: verifies
    target: REQ-SKCWE3M
    confirmed: 223c3f40a1fb
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
