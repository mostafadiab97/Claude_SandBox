---
id: REQ-BAYKJ5C
type: test-case
title: "Verify: Device registry restores the connection state"
status: Approved
owner: N. Kamal
tags:
  - customer-request
  - power
  - regulatory
former-id: TC-81V1ZJ
parent: REQ-8351896
order: b1L
links:
  - type: verifies
    target: REQ-JYC0NB4
    confirmed: 57d91dd17cd7
  - type: verifies
    target: REQ-KM0NNHS
    confirmed: 08d749a8875b
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
