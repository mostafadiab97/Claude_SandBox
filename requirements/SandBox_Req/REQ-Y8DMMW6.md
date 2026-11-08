---
id: REQ-Y8DMMW6
type: test-case
title: "Regression: OTA server notifys error conditions"
status: Draft
priority: Low
owner: J. Müller
former-id: TC-ZQV1AQ
parent: REQ-6H15AV2
order: b0E
links:
  - type: verifies
    target: REQ-7JRJWMP
    confirmed: d331f9bc5a8a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Store the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
