---
id: REQ-PGH30PY
type: test-case
title: "Verify: Enclosure measures error conditions"
status: Draft
priority: Medium
owner: S. Adel
former-id: TC-BJRPJW
parent: REQ-F9Z1FYS
order: b1d
links:
  - type: verifies
    target: REQ-QCJ3WMP
    confirmed: 1d8cfb08af6f
  - type: verifies
    target: REQ-J2ZK72J
    confirmed: f40caf35bcf0
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Report schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
