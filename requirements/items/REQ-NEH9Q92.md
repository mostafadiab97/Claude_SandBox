---
id: REQ-NEH9Q92
type: test-case
title: "Verify: Cloud backend measures error conditions"
status: Approved
priority: Medium
owner: S. Adel
tags:
  - i18n
former-id: TC-ZTPN2D
parent: REQ-8351896
order: aX
links:
  - type: verifies
    target: REQ-8M8WPB5
    confirmed: "633397687564"
---
**Objective:** verify that the cloud backend behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the cloud backend with default settings.
2. Switch the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
