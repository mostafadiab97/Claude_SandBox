---
id: REQ-HCBWGQC
type: test-case
title: "Verify: Battery backup reports the operating mode"
status: Approved
priority: Low
former-id: TC-DS30DM
parent: REQ-F9Z1FYS
order: a7
links:
  - type: verifies
    target: REQ-6EYT1EP
    confirmed: a94dbe6fcdb1
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Encrypt relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
