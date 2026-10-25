---
id: TC-HMBA5X
type: test-case
title: "Verify: Secure boot validates audit records"
status: Draft
priority: Medium
owner: N. Kamal
tags:
  - ux
parent: INFO-Z4TW4B
order: 1220
links:
  - type: verifies
    target: SYS-9ECYTV
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Authenticate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
