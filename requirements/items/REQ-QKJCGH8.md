---
id: TC-5V70HD
type: test-case
title: "Verify: OTA server calibrates the room temperature"
status: Approved
priority: Medium
parent: INFO-7P4D8D
order: 780
links:
  - type: verifies
    target: SYS-YWZ4G6
    confirmed: af8070b2a3c3
  - type: verifies
    target: SW-NSQJT0
    confirmed: d99755f8771b
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Detect user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
