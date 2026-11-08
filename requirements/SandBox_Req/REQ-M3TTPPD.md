---
id: REQ-M3TTPPD
type: test-case
title: "Verify: Secure boot logs the connection state"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - accessibility
former-id: TC-YXCMKZ
parent: REQ-K6FGAY0
order: b0o
links:
  - type: verifies
    target: REQ-10ZK2XJ
    confirmed: 939eef8c8900
  - type: verifies
    target: REQ-CV7WTVP
    confirmed: eb58fcaf9f95
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Store the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
