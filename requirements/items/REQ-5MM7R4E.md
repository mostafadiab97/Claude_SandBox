---
id: REQ-5MM7R4E
type: test-case
title: "Verify: Heat pump driver notifys relay events"
status: Draft
priority: Medium
owner: L. Samir
former-id: TC-YRT45Q
parent: REQ-XGWSK2K
order: aU
links:
  - type: verifies
    target: REQ-6MCMEW9
    confirmed: 5718299a4e75
  - type: verifies
    target: REQ-5FGV75Q
    confirmed: 6c2ce4814808
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Restore schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
