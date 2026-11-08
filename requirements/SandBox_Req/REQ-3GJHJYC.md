---
id: REQ-3GJHJYC
type: test-case
title: "Verify: Enclosure synchronises safety limits"
status: Review
priority: High
owner: S. Adel
tags:
  - EMC
former-id: TC-0J1H30
parent: REQ-F9Z1FYS
order: b0K
links:
  - type: verifies
    target: REQ-0N8DMH3
    confirmed: ed79de17940f
  - type: verifies
    target: REQ-56210FN
    confirmed: 4ea9bf6f6ab0
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Log schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
