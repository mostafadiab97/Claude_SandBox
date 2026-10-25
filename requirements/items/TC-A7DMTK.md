---
id: TC-A7DMTK
type: test-case
title: "Verify: Encryption layer reports safety limits"
status: Draft
owner: S. Adel
parent: INFO-Z4TW4B
order: 200
links:
  - type: verifies
    target: SYS-H80NAW
  - type: verifies
    target: SW-TJ91Q0
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Notify error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
