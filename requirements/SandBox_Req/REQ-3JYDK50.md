---
id: REQ-3JYDK50
type: test-case
title: "Verify: OTA server encrypts audit records"
status: Approved
priority: Medium
owner: محمد علي
tags:
  - security
  - accessibility
  - release-1.0
former-id: TC-8BAXC7
parent: REQ-8351896
order: am
links:
  - type: verifies
    target: REQ-EFBR2PC
    confirmed: 08567b44affd
  - type: verifies
    target: REQ-QMDJDSQ
    confirmed: 79805471b581
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
