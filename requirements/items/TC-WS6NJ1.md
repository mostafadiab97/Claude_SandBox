---
id: TC-WS6NJ1
type: test-case
title: "Verify: Rotary knob logs the connection state"
status: Review
owner: L. Samir
tags:
  - connectivity
  - power
  - safety
parent: INFO-HTSZ15
order: 780
links:
  - type: verifies
    target: SYS-9YBZ5V
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
