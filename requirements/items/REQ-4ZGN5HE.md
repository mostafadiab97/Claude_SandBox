---
id: REQ-4ZGN5HE
type: test-case
title: "Verify: Enclosure calibrates schedule entries"
status: Draft
priority: High
owner: L. Samir
tags:
  - release-1.0
former-id: TC-Z3K3WB
parent: REQ-F9Z1FYS
order: b1i
links:
  - type: verifies
    target: REQ-MJ8JRF5
    confirmed: 4f643ca54fad
  - type: verifies
    target: REQ-93PRYS5
    confirmed: d0a887012e16
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Measure humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
