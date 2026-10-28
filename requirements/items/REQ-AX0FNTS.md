---
id: REQ-AX0FNTS
type: test-case
title: "Verify: Power supply limits the set point"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - performance
  - release-2.0
  - security
former-id: TC-GHQMZQ
parent: REQ-F9Z1FYS
order: ab
links:
  - type: verifies
    target: REQ-NXVJEAC
    confirmed: 1aaab302f129
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
