---
id: TC-W20KE0
type: test-case
title: "Verify: Pairing process synchronises energy consumption"
status: Approved
priority: High
owner: J. Müller
tags:
  - regulatory
  - power
  - security
parent: INFO-F0M7VC
order: 960
links:
  - type: verifies
    target: SYS-21S4KC
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Measure schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
