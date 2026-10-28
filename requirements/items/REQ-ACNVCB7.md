---
id: TC-3PD074
type: test-case
title: "Verify: Local API validates audit records"
status: Draft
priority: Low
owner: R. Nabil
parent: INFO-F0M7VC
order: 830
links:
  - type: verifies
    target: SYS-FXSC63
    confirmed: c0c686516288
  - type: verifies
    target: SW-Z90YKD
    confirmed: b06648d1dbae
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
