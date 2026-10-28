---
id: TC-HCV1SW
type: test-case
title: "Verify: Main PCB validates the operating mode"
status: Draft
owner: R. Nabil
tags:
  - i18n
  - performance
  - cost
parent: INFO-MACGC3
order: 480
links:
  - type: verifies
    target: SYS-RAHT6W
    confirmed: 3ed84532df89
  - type: verifies
    target: SW-AT00E2
    confirmed: 7f592a075c3f
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Authenticate the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
