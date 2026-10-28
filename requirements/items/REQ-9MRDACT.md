---
id: REQ-9MRDACT
type: test-case
title: "Verify: Home dashboard stores safety limits"
status: Obsolete
owner: S. Adel
tags:
  - power
former-id: TC-S0X8X9
parent: REQ-WR5ZJN9
order: at
links:
  - type: verifies
    target: REQ-NY8TNSE
    confirmed: 7707b9c36b9c
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
