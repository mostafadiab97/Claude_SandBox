---
id: TC-4067BQ
type: test-case
title: "Verify: Local API synchronises firmware images"
status: Approved
priority: High
owner: S. Adel
tags:
  - EMC
  - safety
parent: INFO-F0M7VC
order: 1050
links:
  - type: verifies
    target: SYS-N9J3YN
    confirmed: b028c5e8a190
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Report access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
