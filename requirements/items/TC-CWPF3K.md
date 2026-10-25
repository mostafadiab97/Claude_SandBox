---
id: TC-CWPF3K
type: test-case
title: "Regression: OTA server validates the operating mode"
status: Obsolete
owner: S. Adel
parent: INFO-ECHASH
order: 570
links:
  - type: verifies
    target: SYS-XVVWVF
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
