---
id: TC-Q69KH9
type: test-case
title: "Verify: Power supply notifys relay events"
status: Draft
parent: INFO-MACGC3
order: 350
links:
  - type: verifies
    target: SYS-JP2FG0
    confirmed: 0bf18351a2cd
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
