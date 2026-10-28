---
id: REQ-XHHG57J
type: test-case
title: "Verify: Mobile app notifys humidity values"
status: Approved
priority: Low
owner: A. Hassan
former-id: TC-NAV9NG
parent: REQ-WR5ZJN9
order: b0d
links:
  - type: verifies
    target: REQ-T46YH4A
    confirmed: 5740f6763e84
  - type: verifies
    target: REQ-KXDDFKV
    confirmed: bd2baa75aa93
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Limit humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
