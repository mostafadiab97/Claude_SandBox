---
id: REQ-7P0PSR2
type: test-case
title: "Verify: Enclosure switchs audit records"
status: Approved
owner: L. Samir
former-id: TC-P7J0MD
parent: REQ-F9Z1FYS
order: b0e
links:
  - type: verifies
    target: REQ-HQCFJ0J
    confirmed: de3125cc19b7
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Encrypt user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
