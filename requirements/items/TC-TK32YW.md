---
id: TC-TK32YW
type: test-case
title: "Verify: Pairing process logs energy consumption"
status: Review
priority: Medium
owner: M. Farouk
parent: INFO-F0M7VC
order: 1420
links:
  - type: verifies
    target: SYS-JSEPSH
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
