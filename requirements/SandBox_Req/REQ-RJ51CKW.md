---
id: REQ-RJ51CKW
type: test-case
title: "Verify: Home dashboard reports error conditions"
status: Obsolete
priority: High
owner: Y. Saber
former-id: TC-18KRFM
parent: REQ-WR5ZJN9
order: b0f
links:
  - type: verifies
    target: REQ-BF9PRQ8
    confirmed: 79d2c72aebd1
  - type: verifies
    target: REQ-NV41NQC
    confirmed: f3c404d14f3c
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Detect the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
