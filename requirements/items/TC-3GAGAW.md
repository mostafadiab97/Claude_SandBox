---
id: TC-3GAGAW
type: test-case
title: "Verify: Notification service stores access tokens"
status: Draft
priority: High
owner: K. Tanaka
tags:
  - regulatory
  - cost
  - performance
parent: INFO-J0FETE
order: 1400
links:
  - type: verifies
    target: SYS-BS5G2C
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
