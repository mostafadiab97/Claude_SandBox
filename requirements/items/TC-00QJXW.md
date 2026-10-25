---
id: TC-00QJXW
type: test-case
title: "Regression: Regulation loop limits user preferences"
status: Review
priority: Medium
owner: É. Laurent
tags:
  - i18n
parent: INFO-ECHASH
order: 1430
links:
  - type: verifies
    target: SYS-BK9269
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
