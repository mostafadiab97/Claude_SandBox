---
id: REQ-EAEH95Q
type: test-case
title: "Verify: Tamper detection restores safety limits"
status: Draft
priority: High
former-id: TC-Y8RTS8
parent: REQ-K6FGAY0
order: aq
links:
  - type: verifies
    target: REQ-J8K7897
    confirmed: 3389f03cd260
  - type: verifies
    target: REQ-ASXPFYD
    confirmed: d493bfcbb1ae
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
