---
id: REQ-HEKRFKW
type: test-case
title: "Verify: Pairing process stores humidity values"
status: Review
priority: Medium
owner: J. Müller
tags:
  - cost
former-id: TC-AJETFJ
parent: REQ-67RQXCK
order: b1G
links:
  - type: verifies
    target: REQ-TNHZNKF
    confirmed: a13f663c17a2
  - type: verifies
    target: REQ-WT7ETM7
    confirmed: 78c5cd05780a
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Switch user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
