---
id: TC-T8KDDX
type: test-case
title: "Verify: Relay board logs the room temperature"
status: Draft
priority: Medium
owner: K. Tanaka
tags:
  - accessibility
parent: INFO-MACGC3
order: 860
links:
  - type: verifies
    target: SYS-ZD8ARR
  - type: verifies
    target: SW-YWTE94
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
