---
id: TC-7TQASG
type: test-case
title: "Verify: Telemetry pipeline displays sensor readings"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - performance
parent: INFO-7P4D8D
order: 330
links:
  - type: verifies
    target: SYS-YJBS7Z
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
