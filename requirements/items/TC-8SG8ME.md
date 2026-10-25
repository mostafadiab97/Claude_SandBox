---
id: TC-8SG8ME
type: test-case
title: "Verify: Watchdog notifys error conditions"
status: Approved
priority: Medium
owner: A. Hassan
parent: INFO-Z4TW4B
order: 380
links:
  - type: verifies
    target: SYS-KGMJR6
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
