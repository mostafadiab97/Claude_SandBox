---
id: TC-WT51B7
type: test-case
title: "Verify: Enclosure detects the operating mode"
status: Draft
priority: Medium
owner: M. Farouk
parent: INFO-MACGC3
order: 610
links:
  - type: verifies
    target: SYS-VCX096
    confirmed: 63d283d89339
  - type: verifies
    target: SW-D8ZPBJ
    confirmed: 108303a36b9c
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Report the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
