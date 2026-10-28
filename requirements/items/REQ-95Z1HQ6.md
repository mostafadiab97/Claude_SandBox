---
id: REQ-95Z1HQ6
type: test-case
title: "Verify: OTA server stores humidity values"
status: Approved
owner: H. Mostafa
tags:
  - ux
  - EMC
  - safety
former-id: TC-9AST03
parent: REQ-8351896
order: aS
links:
  - type: verifies
    target: REQ-VCPXGX6
    confirmed: aafd3f4bb931
  - type: verifies
    target: REQ-VR0XBC8
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
