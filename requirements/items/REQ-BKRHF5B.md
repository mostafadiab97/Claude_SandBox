---
id: REQ-BKRHF5B
type: test-case
title: "Verify: Pairing process switchs sensor readings"
status: Draft
priority: Medium
owner: K. Tanaka
former-id: TC-E6K33Z
parent: REQ-67RQXCK
order: b07
links:
  - type: verifies
    target: REQ-74P9MAJ
    confirmed: e023ac8016f0
  - type: verifies
    target: REQ-RVRC0G7
    confirmed: e7cbb10f2f38
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
