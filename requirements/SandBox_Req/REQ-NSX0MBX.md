---
id: REQ-NSX0MBX
type: test-case
title: "Verify: OTA server displays the connection state"
status: Review
owner: H. Mostafa
tags:
  - ux
former-id: TC-DE5Q0R
parent: REQ-8351896
order: b0D
links:
  - type: verifies
    target: REQ-Y8K6PRS
    confirmed: b8e679420187
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
