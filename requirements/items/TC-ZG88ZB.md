---
id: TC-ZG88ZB
type: test-case
title: "Verify: Battery backup measures the room temperature"
status: Approved
priority: High
owner: M. Farouk
tags:
  - i18n
  - connectivity
parent: INFO-MACGC3
order: 740
links:
  - type: verifies
    target: SYS-0NHZ18
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Detect firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
