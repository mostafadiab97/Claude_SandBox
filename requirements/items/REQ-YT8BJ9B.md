---
id: TC-YPSENN
type: test-case
title: "Verify: Relay board switchs humidity values"
status: Review
priority: High
parent: INFO-MACGC3
order: 1630
links:
  - type: verifies
    target: SYS-ESNRC9
    confirmed: 72173e46587d
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
