---
id: TC-NRKTZ4
type: test-case
title: "Verify: Cloud backend detects the room temperature"
status: Approved
priority: High
owner: K. Tanaka
parent: INFO-7P4D8D
order: 240
links:
  - type: verifies
    target: SYS-C849TP
  - type: verifies
    target: SW-B5J7X8
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
