---
id: REQ-0QR015Y
type: test-case
title: "Verify: Enclosure calibrates relay events"
status: Review
priority: High
owner: R. Nabil
former-id: TC-4MN8KY
parent: REQ-F9Z1FYS
order: a1
links:
  - type: verifies
    target: REQ-EMXTY67
    confirmed: a0e9ce534d79
  - type: verifies
    target: REQ-MFWJADQ
    confirmed: 5e11b806d907
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Log the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
