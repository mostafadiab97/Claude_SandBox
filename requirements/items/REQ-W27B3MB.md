---
id: REQ-W27B3MB
type: test-case
title: "Verify: Telemetry pipeline reports user preferences"
status: Approved
owner: L. Samir
former-id: TC-ADMPWY
parent: REQ-8351896
order: b0E
links:
  - type: verifies
    target: REQ-WSY0MZM
    confirmed: c14e888575b5
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Measure energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
