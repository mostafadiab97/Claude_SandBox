---
id: TC-B0FFGH
type: test-case
title: "Verify: Power supply limits error conditions"
status: Review
priority: High
owner: A. Hassan
parent: INFO-MACGC3
order: 1060
links:
  - type: verifies
    target: SYS-JRYFKW
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Detect error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
