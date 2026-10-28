---
id: REQ-GJHRZH4
type: test-case
title: "Verify: Notification service encrypts error conditions"
status: Draft
priority: Medium
owner: S. Adel
tags:
  - regulatory
  - ux
former-id: TC-370KDA
parent: REQ-WR5ZJN9
order: aT
links:
  - type: verifies
    target: REQ-ED1Z2TR
    confirmed: b93a511f8f0f
---
**Objective:** verify that the notification service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the notification service with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
