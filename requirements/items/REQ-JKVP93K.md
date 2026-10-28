---
id: TC-97K34G
type: test-case
title: "Verify: Battery backup encrypts safety limits"
status: Draft
priority: Medium
owner: K. Tanaka
parent: INFO-MACGC3
order: 90
links:
  - type: verifies
    target: SYS-11FFG3
    confirmed: b87802a5ad61
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
