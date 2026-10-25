---
id: TC-D0XMQ6
type: test-case
title: "Verify: Main PCB logs audit records"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - accessibility
  - customer-request
parent: INFO-MACGC3
order: 370
links:
  - type: verifies
    target: SYS-A1R34W
    confirmed: 95a4e5b7531a
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
