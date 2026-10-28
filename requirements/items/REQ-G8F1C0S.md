---
id: REQ-G8F1C0S
type: test-case
title: "Verify: Enclosure measures the operating mode"
status: Obsolete
priority: Low
owner: L. Samir
former-id: TC-TT6TVK
parent: REQ-F9Z1FYS
order: as
links:
  - type: verifies
    target: REQ-NXAVMWA
    confirmed: 11de28b7d99d
  - type: verifies
    target: REQ-VCEDV88
    confirmed: 0626f45d0a4b
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Calibrate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
