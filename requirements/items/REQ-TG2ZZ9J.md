---
id: REQ-TG2ZZ9J
type: test-case
title: "Verify: Battery backup reports user preferences"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - release-2.0
former-id: TC-CGWQSD
parent: REQ-F9Z1FYS
order: b0f
links:
  - type: verifies
    target: REQ-BZG33TA
    confirmed: c22e3af7bfc8
  - type: verifies
    target: REQ-GX4PN4D
    confirmed: ff58105578cc
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Measure safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
