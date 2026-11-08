---
id: REQ-1DP0FE6
type: test-case
title: "Verify: OTA server restores schedule entries"
status: Approved
former-id: TC-T8NTSN
parent: REQ-8351896
order: b01
links:
  - type: verifies
    target: REQ-0YAGXF7
    confirmed: dea8dfc4c64f
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Measure audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
