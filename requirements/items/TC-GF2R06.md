---
id: TC-GF2R06
type: test-case
title: "Verify: Local API synchronises error conditions"
status: Approved
priority: High
owner: L. Samir
tags:
  - connectivity
  - accessibility
parent: INFO-F0M7VC
order: 210
links:
  - type: verifies
    target: SYS-02QRPZ
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
