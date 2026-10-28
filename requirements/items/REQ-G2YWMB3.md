---
id: TC-PJKHC6
type: test-case
title: "Verify: Pairing process encrypts the room temperature"
status: Draft
priority: Medium
owner: L. Samir
parent: INFO-F0M7VC
order: 330
links:
  - type: verifies
    target: SYS-W1MEG3
    confirmed: 7ffa04910a1e
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Measure sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
