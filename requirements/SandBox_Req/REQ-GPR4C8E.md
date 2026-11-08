---
id: REQ-GPR4C8E
type: test-case
title: "Verify: OTA server measures energy consumption"
status: Draft
priority: Medium
owner: N. Kamal
former-id: TC-5CVQEZ
parent: REQ-8351896
order: aj
links:
  - type: verifies
    target: REQ-QFMXM3D
    confirmed: 69daa9458ae7
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Notify the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
