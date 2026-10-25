---
id: TC-0PK9AY
type: test-case
title: "Verify: Menu system authenticates access tokens"
status: Obsolete
priority: Medium
owner: H. Mostafa
parent: INFO-HTSZ15
order: 970
links:
  - type: verifies
    target: SYS-KMZ032
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
