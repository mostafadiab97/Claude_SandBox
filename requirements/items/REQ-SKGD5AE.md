---
id: REQ-SKGD5AE
type: test-case
title: "Verify: Enclosure validates the room temperature"
status: Review
priority: Medium
owner: A. Hassan
tags:
  - accessibility
former-id: TC-TFZYK0
parent: REQ-F9Z1FYS
order: b1A
links:
  - type: verifies
    target: REQ-G8Z58Z4
    confirmed: e993ebab475d
  - type: verifies
    target: REQ-RKTE7XD
    confirmed: 18bfa3ee379d
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
