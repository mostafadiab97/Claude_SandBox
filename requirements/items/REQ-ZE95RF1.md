---
id: REQ-ZE95RF1
type: test-case
title: "Verify: OTA server notifys error conditions"
status: Approved
owner: M. Farouk
tags:
  - i18n
former-id: TC-1TH1S8
parent: REQ-8351896
order: b0R
links:
  - type: verifies
    target: REQ-7JRJWMP
    confirmed: d331f9bc5a8a
---
**Objective:** verify that the OTA server behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the OTA server with default settings.
2. Report the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
