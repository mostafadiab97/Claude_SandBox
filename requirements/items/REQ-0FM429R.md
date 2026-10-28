---
id: TC-B49CJC
type: test-case
title: "Verify: User account service reports schedule entries"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - security
  - accessibility
parent: INFO-7P4D8D
order: 1440
links:
  - type: verifies
    target: SYS-EGXJY6
    confirmed: 3e6744bf9b31
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Encrypt firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
