---
id: TC-NSP0AR
type: test-case
title: "Verify: OTA server logs the connection state"
status: Draft
priority: Medium
owner: M. Farouk
parent: INFO-7P4D8D
order: 1270
links:
  - type: verifies
    target: SYS-PH3PWA
    confirmed: 2363be236978
  - type: verifies
    target: SW-NTY35T
    confirmed: afa2f9924712
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
