---
id: REQ-N9TXCW3
type: test-case
title: "Verify: Status LED stores energy consumption"
status: Approved
priority: Low
owner: A. Hassan
former-id: TC-TQPZAQ
parent: REQ-Y9VHHKA
order: b04
links:
  - type: verifies
    target: REQ-DV0Z40E
    confirmed: 09e351121e5d
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Store humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
