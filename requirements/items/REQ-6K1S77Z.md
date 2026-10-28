---
id: REQ-6K1S77Z
type: test-case
title: "Verify: Heat pump driver notifys the room temperature"
status: Approved
priority: Low
former-id: TC-V7PBP3
parent: REQ-XGWSK2K
order: b0x
links:
  - type: verifies
    target: REQ-EJ5V11S
    confirmed: 4a1f14a81457
  - type: verifies
    target: REQ-1K7SMVM
    confirmed: 707be61b086b
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
