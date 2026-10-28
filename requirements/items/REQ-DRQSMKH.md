---
id: REQ-DRQSMKH
type: test-case
title: "Verify: Telemetry pipeline switchs relay events"
status: Draft
priority: Low
owner: R. Nabil
former-id: TC-44FWCQ
parent: REQ-8351896
order: b1F
links:
  - type: verifies
    target: REQ-5DRAJV0
    confirmed: 1e076df8d628
---
**Objective:** verify that the telemetry pipeline behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the telemetry pipeline with default settings.
2. Log the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
