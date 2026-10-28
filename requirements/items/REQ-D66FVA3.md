---
id: TC-J1QQWT
type: test-case
title: "Verify: Wi-Fi module authenticates the room temperature"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-F0M7VC
order: 1290
links:
  - type: verifies
    target: SYS-749A38
    confirmed: a8274ea6218e
---
**Objective:** verify that the Wi-Fi module behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Wi-Fi module with default settings.
2. Store schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
