---
id: REQ-N0B26JQ
type: test-case
title: "Verify: Home dashboard limits schedule entries"
status: Obsolete
priority: High
owner: Y. Saber
tags:
  - i18n
former-id: TC-PC4EK6
parent: REQ-WR5ZJN9
order: aB
links:
  - type: verifies
    target: REQ-J3F7ENB
    confirmed: 9dbd45a382a2
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Detect safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
