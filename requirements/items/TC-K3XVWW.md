---
id: TC-K3XVWW
type: test-case
title: "Verify: Battery backup measures the operating mode"
status: Draft
priority: Medium
owner: R. Nabil
tags:
  - i18n
  - EMC
  - security
parent: INFO-MACGC3
order: 70
links:
  - type: verifies
    target: SYS-G05WA7
    confirmed: c37aca9c7e04
  - type: verifies
    target: SW-88HPF9
    confirmed: 86f3854ab240
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Restore humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
