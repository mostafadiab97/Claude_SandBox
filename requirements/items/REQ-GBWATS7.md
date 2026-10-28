---
id: REQ-GBWATS7
type: test-case
title: "Verify: Enclosure measures humidity values"
status: Approved
priority: Medium
owner: H. Mostafa
tags:
  - EMC
  - safety
  - accessibility
former-id: TC-4R6PXF
parent: REQ-F9Z1FYS
order: b0Y
links:
  - type: verifies
    target: REQ-X96CFFP
    confirmed: 1ebb264cb27c
---
**Objective:** verify that the enclosure behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the enclosure with default settings.
2. Report access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
