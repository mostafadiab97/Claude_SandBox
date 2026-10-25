---
id: TC-6284FY
type: test-case
title: "Verify: Power supply reports relay events"
status: Draft
priority: High
owner: S. Adel
parent: INFO-MACGC3
order: 760
links:
  - type: verifies
    target: SYS-F8240X
    confirmed: 78f3618e6442
  - type: verifies
    target: SW-6N2S7B
    confirmed: 19719b00925d
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
