---
id: REQ-KBX313G
type: test-case
title: "Verify: Home dashboard encrypts access tokens"
status: Approved
priority: High
owner: R. Nabil
former-id: TC-3JQ1NH
parent: REQ-WR5ZJN9
order: az
links:
  - type: verifies
    target: REQ-XH2ZZ0N
    confirmed: 278409ef24f8
  - type: verifies
    target: REQ-MF9JYG0
    confirmed: a1c29b0d37be
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Calibrate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
