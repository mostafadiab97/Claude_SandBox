---
id: REQ-QXDX1G0
type: test-case
title: "Verify: Secure boot validates audit records"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - ux
former-id: TC-HMBA5X
parent: REQ-K6FGAY0
order: b0x
links:
  - type: verifies
    target: REQ-3DHTHXM
    confirmed: 7b9cca966730
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Authenticate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
