---
id: REQ-V90FC45
type: test-case
title: "Verify: Battery backup reports relay events"
status: Review
priority: High
owner: R. Nabil
tags:
  - performance
  - safety
  - release-1.0
former-id: TC-N64T3E
parent: REQ-F9Z1FYS
order: aI
links:
  - type: verifies
    target: REQ-CZRWJVP
    confirmed: fd7d82b6415e
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
