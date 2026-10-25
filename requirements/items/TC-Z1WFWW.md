---
id: TC-Z1WFWW
type: test-case
title: "Verify: Rotary knob logs audit records"
status: Approved
owner: L. Samir
parent: INFO-HTSZ15
order: 250
links:
  - type: verifies
    target: SYS-DTN5PG
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Limit sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
