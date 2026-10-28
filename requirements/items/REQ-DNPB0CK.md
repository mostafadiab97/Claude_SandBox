---
id: REQ-DNPB0CK
type: test-case
title: "Verify: Enclosure synchronises energy consumption"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - cost
  - release-1.0
  - accessibility
former-id: TC-DTFXBM
parent: REQ-F9Z1FYS
order: b0t
links:
  - type: verifies
    target: REQ-QT9ZQ3W
    confirmed: f35119afdb2b
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
