---
id: REQ-9MM9B5J
type: test-case
title: "Verify: Mobile app switchs the connection state"
status: Obsolete
priority: High
owner: R. Nabil
tags:
  - regulatory
  - i18n
former-id: TC-JPFB08
parent: REQ-WR5ZJN9
order: af
links:
  - type: verifies
    target: REQ-M56R4F8
    confirmed: 4f9a7c40ce36
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
