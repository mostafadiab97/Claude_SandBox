---
id: TC-1TZSTX
type: test-case
title: "Verify: Relay board restores relay events"
status: Approved
owner: A. Hassan
parent: INFO-MACGC3
order: 1020
links:
  - type: verifies
    target: SYS-N56168
    confirmed: a37e51579246
  - type: verifies
    target: SW-65YC2Z
    confirmed: a23609dd7210
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Calibrate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
