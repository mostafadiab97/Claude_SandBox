---
id: TC-WQ1HWP
type: test-case
title: "Verify: Cloud backend validates the room temperature"
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - power
  - connectivity
parent: INFO-7P4D8D
order: 540
links:
  - type: verifies
    target: SYS-DMYBQ9
    confirmed: bc350f64bb32
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
