---
id: TC-7WJQNP
type: test-case
title: "Verify: Enclosure reports the room temperature"
status: Approved
priority: Medium
owner: N. Kamal
parent: INFO-MACGC3
order: 1260
links:
  - type: verifies
    target: SYS-T9M88W
  - type: verifies
    target: SW-YZSBP4
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Validate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
