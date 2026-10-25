---
id: TC-3454RV
type: test-case
title: "Verify: Power supply notifys relay events"
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - cost
  - security
parent: INFO-MACGC3
order: 820
links:
  - type: verifies
    target: SYS-Q3NWSK
    confirmed: 98491b75e1ce
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Report the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
