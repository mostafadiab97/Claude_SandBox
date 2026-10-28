---
id: TC-G06ERF
type: test-case
title: "Verify: OTA server reports the connection state"
status: Approved
priority: Medium
owner: R. Nabil
parent: INFO-7P4D8D
order: 1370
links:
  - type: verifies
    target: SYS-DRG6R3
    confirmed: 08f38a1d34b8
  - type: verifies
    target: SW-836F5K
    confirmed: 94ad9d032234
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
