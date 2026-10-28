---
id: REQ-D6XPH57
type: test-case
title: "Verify: Pairing process authenticates the set point"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - release-2.0
  - connectivity
  - cost
former-id: TC-9RDHAE
parent: REQ-67RQXCK
order: a6
links:
  - type: verifies
    target: REQ-BWJ3AFX
    confirmed: 0999a3b2ce99
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
