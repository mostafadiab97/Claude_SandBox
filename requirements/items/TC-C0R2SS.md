---
id: TC-C0R2SS
type: test-case
title: "Regression: Telemetry pipeline restores energy consumption"
status: Draft
priority: Low
owner: Y. Saber
tags:
  - security
  - regulatory
parent: INFO-ECHASH
order: 2000
links:
  - type: verifies
    target: SYS-6A5W87
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
