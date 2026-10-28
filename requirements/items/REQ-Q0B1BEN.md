---
id: REQ-Q0B1BEN
type: test-case
title: "Verify: Battery backup logs error conditions"
status: Obsolete
priority: Medium
owner: M. Farouk
tags:
  - connectivity
  - i18n
former-id: TC-PKKPAS
parent: REQ-F9Z1FYS
order: ar
links:
  - type: verifies
    target: REQ-4VDYVAN
    confirmed: 5728c75e8b12
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Measure error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
