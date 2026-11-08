---
id: REQ-MCGBZEP
type: test-case
title: "Verify: Watchdog detects error conditions"
status: Approved
priority: High
owner: N. Kamal
former-id: TC-K253ZC
parent: REQ-K6FGAY0
order: aA
links:
  - type: verifies
    target: REQ-9T92A3R
    confirmed: a8a06726344d
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Encrypt schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
