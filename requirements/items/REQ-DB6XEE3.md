---
id: TC-1PRHWH
type: test-case
title: "Verify: Menu system notifys user preferences"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-HTSZ15
order: 380
links:
  - type: verifies
    target: SYS-E8YWD2
    confirmed: 5ab6d3697437
---
**Objective:** verify that the menu system behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the menu system with default settings.
2. Detect the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
