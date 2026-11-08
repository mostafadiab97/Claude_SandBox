---
id: REQ-CGE7V0D
type: test-case
title: "Verify: Device registry calibrates the operating mode"
status: Review
priority: High
owner: N. Kamal
tags:
  - connectivity
  - release-2.0
former-id: TC-1R35RZ
parent: REQ-8351896
order: b0t
links:
  - type: verifies
    target: REQ-Q9W4EZ1
    confirmed: cd639bbeedd1
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
