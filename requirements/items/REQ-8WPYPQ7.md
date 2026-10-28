---
id: REQ-8WPYPQ7
type: test-case
title: "Regression: Backlight notifys audit records"
status: Review
priority: High
tags:
  - connectivity
  - power
former-id: TC-NTK6AJ
parent: REQ-6H15AV2
order: b0s
links:
  - type: verifies
    target: REQ-8MD3CMA
    confirmed: a04194db67ef
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
