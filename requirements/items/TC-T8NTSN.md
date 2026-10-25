---
id: TC-T8NTSN
type: test-case
title: "Verify: OTA server restores schedule entries"
status: Approved
parent: INFO-7P4D8D
order: 640
links:
  - type: verifies
    target: SYS-K5FKWP
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
