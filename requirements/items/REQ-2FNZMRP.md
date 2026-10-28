---
id: REQ-2FNZMRP
type: test-case
title: "Verify: Notification service limits sensor readings"
status: Draft
priority: Medium
owner: J. Müller
tags:
  - performance
former-id: TC-CDENPW
parent: REQ-WR5ZJN9
order: b0J
links:
  - type: verifies
    target: REQ-39K6DTS
    confirmed: 7b8278116333
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Synchronise error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
