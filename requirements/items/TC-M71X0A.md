---
id: TC-M71X0A
type: test-case
title: "Verify: Local API displays the operating mode"
status: Approved
priority: Low
owner: H. Mostafa
tags:
  - safety
  - accessibility
parent: INFO-F0M7VC
order: 240
links:
  - type: verifies
    target: SYS-0ZTB0C
  - type: verifies
    target: SW-QK4N65
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
