---
id: REQ-HTVA6QE
type: test-case
title: "Verify: Notification service stores access tokens"
status: Draft
priority: High
owner: K. Tanaka
tags:
  - regulatory
  - cost
  - performance
former-id: TC-3GAGAW
parent: REQ-WR5ZJN9
order: b1F
links:
  - type: verifies
    target: REQ-BHV7AVF
    confirmed: 19954ae1e0af
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
