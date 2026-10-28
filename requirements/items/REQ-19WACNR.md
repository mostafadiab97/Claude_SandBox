---
id: TC-VSXW8T
type: test-case
title: "Verify: Pairing process logs firmware images"
status: Draft
priority: Medium
owner: H. Mostafa
parent: INFO-F0M7VC
order: 1490
links:
  - type: verifies
    target: SYS-RP9EW2
    confirmed: 0ce16e7c9c10
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Notify the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
