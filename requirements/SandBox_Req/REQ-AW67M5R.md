---
id: REQ-AW67M5R
type: test-case
title: "Verify: Battery backup limits safety limits"
status: Obsolete
priority: Medium
owner: N. Kamal
former-id: TC-TM21YZ
parent: REQ-F9Z1FYS
order: b1T
links:
  - type: verifies
    target: REQ-H28Q7YZ
    confirmed: 339efbb2167c
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Display audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
