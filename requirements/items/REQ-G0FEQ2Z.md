---
id: REQ-G0FEQ2Z
type: test-case
title: "Verify: Encryption layer limits the connection state"
status: Draft
priority: High
owner: N. Kamal
tags:
  - accessibility
former-id: TC-XBB4C8
parent: REQ-K6FGAY0
order: b0k
links:
  - type: verifies
    target: REQ-7F9G6TV
    confirmed: 4a1b95f28b03
  - type: verifies
    target: REQ-XT61T5V
    confirmed: 3faf6fa03816
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Synchronise the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
