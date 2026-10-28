---
id: TC-1BF2QB
type: test-case
title: "Verify: Rotary knob measures firmware images"
status: Approved
priority: High
owner: K. Tanaka
parent: INFO-HTSZ15
order: 220
links:
  - type: verifies
    target: SYS-Q0NNG8
    confirmed: d9d2819ed73b
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Encrypt the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
