---
id: REQ-4DHSJFV
type: test-case
title: "Verify: Encryption layer logs relay events"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - EMC
  - release-2.0
  - i18n
former-id: TC-PF5G19
parent: REQ-K6FGAY0
order: b0Y
links:
  - type: verifies
    target: REQ-PP1RGP0
    confirmed: 0e56d083aedf
  - type: verifies
    target: REQ-81SC32G
    confirmed: bab2c9f18398
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Detect relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
