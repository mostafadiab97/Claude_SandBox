---
id: TC-HAATCF
type: test-case
title: "Verify: Local API displays schedule entries"
status: Approved
owner: A. Hassan
parent: INFO-F0M7VC
order: 530
links:
  - type: verifies
    target: SYS-FA8CFD
  - type: verifies
    target: SW-J9XSE6
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Limit energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
