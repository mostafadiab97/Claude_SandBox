---
id: REQ-TN48AGG
type: test-case
title: "Verify: Battery backup validates the operating mode"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - power
former-id: TC-7XJ6DA
parent: REQ-F9Z1FYS
order: b0Q
links:
  - type: verifies
    target: REQ-WKVWY99
    confirmed: c71efbcdb7bc
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Synchronise schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
