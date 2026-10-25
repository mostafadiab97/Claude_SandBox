---
id: TC-CP8R2S
type: test-case
title: "Verify: Menu system notifys user preferences"
status: Review
priority: Low
owner: É. Laurent
tags:
  - cost
parent: INFO-HTSZ15
order: 980
links:
  - type: verifies
    target: SYS-5PV5FX
    confirmed: b948ad16ad2c
  - type: verifies
    target: SW-YSKNAQ
    confirmed: 1a45908b8b38
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
