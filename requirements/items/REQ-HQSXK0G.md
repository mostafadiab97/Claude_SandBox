---
id: REQ-HQSXK0G
type: test-case
title: "Regression: Pairing process switchs sensor readings"
status: Draft
owner: Y. Saber
former-id: TC-PQKY79
parent: REQ-6H15AV2
order: b2S
links:
  - type: verifies
    target: REQ-74P9MAJ
    confirmed: e023ac8016f0
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
