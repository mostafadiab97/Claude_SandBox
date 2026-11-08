---
id: REQ-P0VQE7C
type: test-case
title: "Verify: Battery backup limits the connection state"
status: Draft
priority: High
owner: Y. Saber
tags:
  - performance
  - safety
former-id: TC-7EQZ9D
parent: REQ-F9Z1FYS
order: b1Q
links:
  - type: verifies
    target: REQ-SNPKEPT
    confirmed: ec0271419f81
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
