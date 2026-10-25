---
id: TC-FZDWRD
type: test-case
title: "Verify: Over-temperature monitor detects user preferences"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - ux
  - EMC
parent: INFO-Z4TW4B
order: 600
links:
  - type: verifies
    target: SYS-AT7SG8
    confirmed: c483239675ae
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Authenticate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
