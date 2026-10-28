---
id: REQ-P51BDQ2
type: test-case
title: "Verify: Device registry limits firmware images"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - safety
  - accessibility
former-id: TC-74AYA9
parent: REQ-8351896
order: b0N
links:
  - type: verifies
    target: REQ-21V318B
    confirmed: e9e572deb541
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Measure the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
