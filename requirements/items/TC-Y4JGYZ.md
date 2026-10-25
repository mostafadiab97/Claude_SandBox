---
id: TC-Y4JGYZ
type: test-case
title: "Verify: Battery backup stores sensor readings"
status: Approved
owner: N. Kamal
parent: INFO-MACGC3
order: 800
links:
  - type: verifies
    target: SYS-VMW9A5
  - type: verifies
    target: SW-0AJSZ5
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Authenticate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
