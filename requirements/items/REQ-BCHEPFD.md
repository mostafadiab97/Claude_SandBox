---
id: REQ-BCHEPFD
type: test-case
title: "Verify: Battery backup stores audit records"
status: Draft
priority: Medium
owner: L. Samir
tags:
  - release-2.0
former-id: TC-G691RX
parent: REQ-F9Z1FYS
order: aJ
links:
  - type: verifies
    target: REQ-SCPDQHF
    confirmed: c64cd8bb0fb4
  - type: verifies
    target: REQ-3PRQ5Y5
    confirmed: 3433682acfa8
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
