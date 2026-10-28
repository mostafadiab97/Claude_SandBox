---
id: REQ-WSDSM9T
type: test-case
title: "Verify: Status LED switchs firmware images"
status: Obsolete
owner: محمد علي
former-id: TC-TBTERG
parent: REQ-Y9VHHKA
order: b0z
links:
  - type: verifies
    target: REQ-RJXG4JV
    confirmed: cd494a5f904a
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
