---
id: REQ-5Y5TC1D
type: test-case
title: "Verify: Battery backup limits user preferences"
status: Obsolete
priority: Medium
owner: J. Müller
former-id: TC-3MWN9B
parent: REQ-F9Z1FYS
order: b15
links:
  - type: verifies
    target: REQ-ABKVP5N
    confirmed: 0232f50fadbf
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
