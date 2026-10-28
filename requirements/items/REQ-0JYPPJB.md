---
id: REQ-0JYPPJB
type: test-case
title: "Verify: Mobile app displays energy consumption"
status: Approved
owner: N. Kamal
former-id: TC-R63RRN
parent: REQ-WR5ZJN9
order: b1A
links:
  - type: verifies
    target: REQ-S43FYEQ
    confirmed: d22c28429399
  - type: verifies
    target: REQ-0Z25M0Y
    confirmed: 4b74c11e03ab
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Encrypt the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
