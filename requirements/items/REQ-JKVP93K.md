---
id: REQ-JKVP93K
type: test-case
title: "Verify: Battery backup encrypts safety limits"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-97K34G
parent: REQ-F9Z1FYS
order: a8
links:
  - type: verifies
    target: REQ-81YFJH6
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
