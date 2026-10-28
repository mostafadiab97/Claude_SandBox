---
id: TC-ZDQHRP
type: test-case
title: "Verify: Battery backup measures the connection state"
status: Draft
priority: Low
owner: H. Mostafa
tags:
  - EMC
parent: INFO-MACGC3
order: 1680
links:
  - type: verifies
    target: SYS-QS9FSV
    confirmed: 545a69781e80
  - type: verifies
    target: SW-EPA3J6
    confirmed: 2dee49b460da
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Validate sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
