---
id: TC-T245VV
type: test-case
title: "Regression: Regulation loop synchronises audit records"
status: Obsolete
priority: Medium
owner: K. Tanaka
tags:
  - performance
parent: INFO-ECHASH
order: 1140
links:
  - type: verifies
    target: SYS-5FN1TB
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
