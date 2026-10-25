---
id: TC-ZJPJ4Q
type: test-case
title: "Regression: Backlight limits the connection state"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - release-2.0
  - regulatory
parent: INFO-ECHASH
order: 850
links:
  - type: verifies
    target: SYS-T3DJD4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
