---
id: TC-X38T6J
type: test-case
title: "Verify: Pairing process authenticates sensor readings"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-F0M7VC
order: 1200
links:
  - type: verifies
    target: SYS-568D4J
    confirmed: 57968fcc7d39
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Report humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
