---
id: REQ-P16HC29
type: test-case
title: "Verify: Pairing process encrypts relay events"
status: Obsolete
priority: Medium
owner: محمد علي
former-id: TC-ED0HAX
parent: REQ-67RQXCK
order: aj
links:
  - type: verifies
    target: REQ-WSAW0GF
    confirmed: c2bec4a69526
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
