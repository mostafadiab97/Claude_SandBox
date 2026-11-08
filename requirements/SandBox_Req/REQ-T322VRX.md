---
id: REQ-T322VRX
type: test-case
title: "Verify: Tamper detection displays error conditions"
status: Review
priority: High
owner: N. Kamal
tags:
  - EMC
  - cost
former-id: TC-AF5Q4Q
parent: REQ-K6FGAY0
order: aY
links:
  - type: verifies
    target: REQ-7W5PV59
    confirmed: 89bbd5dd030b
  - type: verifies
    target: REQ-BKVNXAX
    confirmed: ea742fa40ce3
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Switch error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
