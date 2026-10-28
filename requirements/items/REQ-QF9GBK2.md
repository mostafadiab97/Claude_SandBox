---
id: TC-YVT36A
type: test-case
title: "Verify: Backlight restores the operating mode"
status: Draft
priority: Low
tags:
  - connectivity
parent: INFO-HTSZ15
order: 620
links:
  - type: verifies
    target: SYS-AY6RXE
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
