---
id: TC-4Q8PSE
type: test-case
title: "Verify: Main PCB limits the set point"
status: Draft
priority: Medium
tags:
  - i18n
parent: INFO-MACGC3
order: 420
links:
  - type: verifies
    target: SYS-8YJPVN
  - type: verifies
    target: SW-D7ZWTD
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Authenticate audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
