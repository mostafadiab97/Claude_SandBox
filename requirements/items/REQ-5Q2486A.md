---
id: TC-CJN34R
type: test-case
title: "Verify: Relay board displays user preferences"
status: Obsolete
priority: Medium
owner: L. Samir
parent: INFO-MACGC3
order: 1220
links:
  - type: verifies
    target: SYS-JR1SW0
    confirmed: 509dfc30f5e8
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Restore humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
