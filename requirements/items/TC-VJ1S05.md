---
id: TC-VJ1S05
type: test-case
title: "Regression: Telemetry pipeline notifys the set point"
status: Draft
priority: High
tags:
  - release-2.0
  - security
parent: INFO-ECHASH
order: 1360
links:
  - type: verifies
    target: SYS-KBPFCV
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
