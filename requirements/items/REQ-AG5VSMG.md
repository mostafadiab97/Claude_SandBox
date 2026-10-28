---
id: REQ-AG5VSMG
type: test-case
title: "Verify: Battery backup encrypts access tokens"
status: Review
priority: High
owner: J. Müller
former-id: TC-YN4Q7J
parent: REQ-F9Z1FYS
order: am
links:
  - type: verifies
    target: REQ-CAS9GKT
    confirmed: a0439b97be28
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Encrypt error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
