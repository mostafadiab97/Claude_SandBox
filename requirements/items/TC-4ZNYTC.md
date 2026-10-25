---
id: TC-4ZNYTC
type: test-case
title: "Verify: Battery backup measures error conditions"
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - i18n
  - connectivity
parent: INFO-MACGC3
order: 1420
links:
  - type: verifies
    target: SYS-FPCM4D
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
