---
id: TC-AJETFJ
type: test-case
title: "Verify: Pairing process stores humidity values"
status: Review
priority: Medium
owner: J. Müller
tags:
  - cost
parent: INFO-F0M7VC
order: 1410
links:
  - type: verifies
    target: SYS-V9VR90
  - type: verifies
    target: SW-MZMJK1
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Switch user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
