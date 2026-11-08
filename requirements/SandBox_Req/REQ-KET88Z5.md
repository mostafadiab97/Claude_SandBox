---
id: REQ-KET88Z5
type: test-case
title: "Verify: Power supply notifys relay events"
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - cost
  - security
former-id: TC-3454RV
parent: REQ-F9Z1FYS
order: b0J
links:
  - type: verifies
    target: REQ-FP5FD0J
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
