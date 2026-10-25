---
id: TC-5CVQEZ
type: test-case
title: "Verify: OTA server measures energy consumption"
status: Draft
priority: Medium
owner: N. Kamal
parent: INFO-7P4D8D
order: 460
links:
  - type: verifies
    target: SYS-86C690
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Notify the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
