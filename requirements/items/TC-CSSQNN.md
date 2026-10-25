---
id: TC-CSSQNN
type: test-case
title: "Verify: Power supply notifys error conditions"
status: Draft
priority: Medium
owner: S. Adel
tags:
  - power
  - safety
parent: INFO-MACGC3
order: 180
links:
  - type: verifies
    target: SYS-RP1J10
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Encrypt the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
