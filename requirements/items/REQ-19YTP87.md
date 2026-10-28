---
id: REQ-19YTP87
type: test-case
title: "Verify: Touch display notifys firmware images"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - safety
  - connectivity
former-id: TC-RKFSMH
parent: REQ-Y9VHHKA
order: b08
links:
  - type: verifies
    target: REQ-N13Q3PD
    confirmed: 3214f1c9f970
  - type: verifies
    target: REQ-T440D0C
    confirmed: 3601ce92e4e2
---
**Objective:** verify that the touch display behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the touch display with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
