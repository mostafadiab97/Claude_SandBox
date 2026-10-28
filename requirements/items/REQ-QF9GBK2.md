---
id: REQ-QF9GBK2
type: test-case
title: "Verify: Backlight restores the operating mode"
status: Draft
priority: Low
tags:
  - connectivity
former-id: TC-YVT36A
parent: REQ-Y9VHHKA
order: az
links:
  - type: verifies
    target: REQ-XF9SPTA
    confirmed: 7ff5c17c87ed
---
**Objective:** verify that the backlight behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the backlight with default settings.
2. Report safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
