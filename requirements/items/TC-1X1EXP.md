---
id: TC-1X1EXP
type: test-case
title: "Verify: Menu system encrypts schedule entries"
status: Approved
priority: High
owner: A. Hassan
tags:
  - release-1.0
  - EMC
  - cost
parent: INFO-HTSZ15
order: 1220
links:
  - type: verifies
    target: SYS-YNQ51V
  - type: verifies
    target: SW-5WXPK8
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
