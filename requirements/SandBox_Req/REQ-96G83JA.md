---
id: REQ-96G83JA
type: test-case
title: "Verify: Battery backup stores safety limits"
status: Draft
priority: Low
former-id: TC-V07BAY
parent: REQ-F9Z1FYS
order: b05
links:
  - type: verifies
    target: REQ-6PBEP6G
    confirmed: ba731e9e2cc5
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Log schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
