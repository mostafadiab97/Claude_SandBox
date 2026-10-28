---
id: TC-5033FT
type: test-case
title: "Regression: Enclosure logs the connection state"
status: Review
priority: Medium
owner: N. Kamal
tags:
  - ux
  - cost
parent: INFO-ECHASH
order: 990
links:
  - type: verifies
    target: SYS-XRP95E
    confirmed: c526dc6b205d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
