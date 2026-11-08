---
id: REQ-5VGVZZQ
type: test-case
title: "Verify: Status LED notifys schedule entries"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-1WJ01E
parent: REQ-Y9VHHKA
order: ax
links:
  - type: verifies
    target: REQ-8X41AR2
    confirmed: 5ff12c4c4c1a
  - type: verifies
    target: REQ-PRWSH2X
    confirmed: eec819e67021
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Store energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
