---
id: REQ-GDDD1FQ
type: test-case
title: "Verify: Pairing process authenticates sensor readings"
status: Approved
priority: Medium
owner: Y. Saber
former-id: TC-X38T6J
parent: REQ-67RQXCK
order: b0v
links:
  - type: verifies
    target: REQ-2WNTMGV
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
