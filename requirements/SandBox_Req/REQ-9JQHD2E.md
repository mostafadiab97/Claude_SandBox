---
id: REQ-9JQHD2E
type: test-case
title: "Verify: OTA server switchs user preferences"
status: Draft
priority: Low
owner: J. Müller
tags:
  - ux
  - power
  - performance
former-id: TC-BX7CG2
parent: REQ-8351896
order: b1K
links:
  - type: verifies
    target: REQ-CM5Q1FW
    confirmed: 45befcee12fc
  - type: verifies
    target: REQ-MRZRVZM
    confirmed: e4527fa2a61d
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Limit error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
