---
id: TC-RKFSMH
type: test-case
title: "Verify: Touch display notifys firmware images"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - safety
  - connectivity
parent: INFO-HTSZ15
order: 710
links:
  - type: verifies
    target: SYS-76BVFJ
    confirmed: 3214f1c9f970
  - type: verifies
    target: SW-SV5WNT
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
