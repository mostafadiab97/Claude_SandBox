---
id: REQ-C958QZX
type: test-case
title: "Verify: Secure boot notifys the operating mode"
status: Draft
priority: Medium
owner: S. Adel
former-id: TC-FT21R4
parent: REQ-K6FGAY0
order: b0F
links:
  - type: verifies
    target: REQ-MND8W5P
    confirmed: 12c71184dbf6
  - type: verifies
    target: REQ-Z0CVGH2
    confirmed: e94aaaa10742
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Display the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
