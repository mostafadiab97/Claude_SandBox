---
id: REQ-Z60MH5N
type: test-case
title: "Verify: Watchdog notifys error conditions"
status: Approved
priority: Medium
owner: A. Hassan
former-id: TC-8SG8ME
parent: REQ-K6FGAY0
order: ab
links:
  - type: verifies
    target: REQ-3WETC0K
    confirmed: 173f8dfb735a
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Authenticate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
