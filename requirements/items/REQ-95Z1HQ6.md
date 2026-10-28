---
id: TC-9AST03
type: test-case
title: "Verify: OTA server stores humidity values"
status: Approved
owner: H. Mostafa
tags:
  - ux
  - EMC
  - safety
parent: INFO-7P4D8D
order: 290
links:
  - type: verifies
    target: SYS-QEFT7B
    confirmed: aafd3f4bb931
  - type: verifies
    target: SW-B5J7X8
    confirmed: 367a6b674b14
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
