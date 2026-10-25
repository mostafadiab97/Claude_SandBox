---
id: TC-BKY4D5
type: test-case
title: "Verify: Pairing process logs schedule entries"
status: Approved
owner: L. Samir
parent: INFO-F0M7VC
order: 480
links:
  - type: verifies
    target: SYS-TKV6VE
    confirmed: 2a2c879fe6d8
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Restore schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
